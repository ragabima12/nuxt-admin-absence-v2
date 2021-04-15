<template>
  <div>
    <div class="columns is-gapless is-desktop full-height">
      <div class="column is-5 is-primary has-background-primary image-cover">
        <div class="full-height-for-image px-5">
          <div>
            <h1
              class="has-text-white is-size-3 has-text-weight-bold heading-text-cover"
            >
              Integrate Attendance System SMK NEGERI 3 BANDUNG
            </h1>
            <p class="subheading-text-cover pt-3">
              Sistem presensi terintegrasi SMK Negeri 3 Bandung
            </p>
          </div>
        </div>
      </div>
      <div class="column is-7 has-background-white">
        <div class="container is-fluid mt-5">
          <div class="columns is-desktop mt-5">
            <div class="column is-8 is-offset-2 mt-5">
              <div class="columns is-multiline mt-5">
                <div class="column is-12 mt-5">
                  <h1 class="is-size-4 heading-text has-text-weight-bold">
                    INTENS Console
                  </h1>
                  <p class="is-size-6 subheading-text has-text-weight-light">
                    Silahkan login terlebih dahulu
                  </p>
                </div>
                <div class="column is-12">
                  <b-field label="Username">
                    <b-input
                      icon="account"
                      placeholder="Silahkan masukan username akun anda"
                    ></b-input>
                  </b-field>
                  <b-field label="Password">
                    <b-input
                      icon="lock"
                      type="password"
                      placeholder="Silahkan masukan password akun anda"
                      password-reveal
                    ></b-input>
                  </b-field>
                  <b-button type="is-info" icon-left="login" class="mt-2"
                    >LOGIN</b-button
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Login",
  components: {},
};
</script>

<style scoped>
.full-height {
  position: fixed;
  height: 102%;
  width: 102%;
  top: 0;
}

.full-height-for-image {
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.452);
  display: flex;
}

.full-height-for-image > div {
  flex-basis: 100%;
  text-align: left;
  align-self: center;
}

.heading-text {
  font-family: "Poppins", sans-serif;
}
.subheading-text {
  font-family: "Open Sans", sans-serif;
}

.subheading-text-cover {
  font-family: "Open Sans", sans-serif;
  color: rgb(196, 196, 196);
}

.image-cover {
  background-image: url("https://images.unsplash.com/photo-1618356387902-245c575733f0?ixid=MnwxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHwyfHx8ZW58MHx8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60");
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
