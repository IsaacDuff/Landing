<template>
  <div class="row">
    <div class="col-12 d-flex flex-column justify-content-center align-items-center heroImg">
      <img class="profilePic" src="../assets/img/ProfilePic.jpg" alt="Profile Pic">
      <h2 class="text-light">Isaac Duff</h2>
      <h4 class="text-light">Full Stack Developer</h4>
      <div class="container-fluid">
        <div class="row justify-content-center">
          <div class="col-2 d-flex justify-content-evenly">
            <a href="https://www.linkedin.com/in/duffisaac/" target="_blank"><button
                class="btn btn-primary  mdi mdi-linkedin buttonFont"></button>
            </a>
            <a href="https://github.com/IsaacDuff" target="_blank"><button
                class="btn btn-primary mdi mdi-github buttonFont"></button></a>
            <a href="https://www.facebook.com/isaac.duff.3" target="_blank"><button
                class="btn btn-primary mdi mdi-facebook buttonFont"></button></a>
            <a href="https://www.instagram.com/duffisaac/" target="_blank"><button
                class="btn btn-primary mdi mdi-instagram buttonFont"></button></a>
            <!-- <button class="btn btn-primary  mdi mdi-linkedin buttonFont"></button> -->
            <!-- <button class="btn btn-primary mdi mdi-github buttonFont"></button> -->
            <!-- <button class="btn btn-primary mdi mdi-facebook buttonFont"></button> -->
            <!-- <button class="btn btn-primary mdi mdi-instagram buttonFont"></button> -->
          </div>
        </div>
      </div>
    </div>

    <div class="row">
      <div class="col-4 p-5 d-flex justify-content-end">
        <img class="mainImg elevation-5 border border-light rounded" src="../assets/img/Isaac Duff 3.jpg" alt="big pic">
      </div>
      <div class="col-6 pt-5">
        <h3 class="text-primary">Discover</h3>
        <h2 class="border-bottom border-primary"><b>About Me</b></h2>
        <p>I am a Full-Stack Software Developer. I previously worked in the medical field for the beginning of my career
          but instead I found my true passion in full-stack web development. Be it learning a new framework or spending
          way too long getting my style to match exactly I enjoy it all. My hobbies include table-top games, video games
          and meeting up with friends. I am a life-long student who enjoys learning about all kinds of topics.</p>

        <section class="border border-primary p-2 mt-4">
          <h2 class="text-primary"><b>INFO</b></h2>
          <div class="d-flex align-items-center mb-2">
            <h5 class="m-0">Name:
            </h5>
            <p class="m-0 ms-2">Isaac Duff</p>
          </div>
          <div class="d-flex align-items-center mb-2">
            <h5 class="m-0"> <i class="mdi mdi-phone-outline"></i>
            </h5>
            <p class="m-0 ms-2">+1 208-999-8806</p>
          </div>
          <div class="d-flex align-items-center mb-2">
            <h5 class="m-0">Experience:
            </h5>
            <p class="m-0 ms-2">1 year</p>
          </div>
          <div class="d-flex align-items-center mb-2">
            <h5 class="m-0">Filler Something:
            </h5>
            <p class="m-0 ms-2">Daddy</p>
          </div>
          <div class="d-flex align-items-center mb-2">
            <h5 class="m-0">Age:
            </h5>
            <p class="m-0 ms-2">26</p>
          </div>
          <div class="d-flex align-items-center mb-2">
            <h5 class="m-0">Location:
            </h5>
            <p class="m-0 ms-2">Idaho, USA</p>
          </div>
        </section>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  setup() {
    return {}
  }
}
</script>

<style scoped lang="scss">
.profilePic {
  max-height: 18vh;
  border-radius: 50%;
  border-style: solid;
  border-width: 3px;
  border-color: white;
}

.heroImg {
  background-image: url(../assets/img/pexels-marek-piwnicki-15334615.jpg);
  height: 80vh;
  background-position: center;
  background-size: cover;
}

.mainImg {
  height: 50vh;
  width: auto;
}

.buttonFont {
  font-size: x-large;
}
</style>
