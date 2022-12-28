<template>
  <div class=" row back1">
    <div class="offset-2 col-6 font-weight-bold fs-1 hello">Another <br> Man's <br> Treasure</div>
    <div class="p-3 col-4 text-center text-light tShadow"><span class="fs-2">⬆️</span>Help us decide  <br> what content we do next
      <div class="p-3">
        <img class="rounded-circle m-2 profile img-fluid" src="https://media-exp1.licdn.com/dms/image/C5603AQH0A7CqLa9eZg/profile-displayphoto-shrink_200_200/0/1660330660476?e=1675296000&v=beta&t=Ibt-G2F0OG5KCEhF8XacS2OlJWA89Cr1VjhfTHKexWk" alt="">
        <img class="rounded-circle m-2 profile img-fluid" src="https://media-exp1.licdn.com/dms/image/C4E03AQHSR_xKSLKnEQ/profile-displayphoto-shrink_200_200/0/1516359104134?e=1675296000&v=beta&t=-NuOOescrq_uh3WUobTyHWreOTIx94jFPgsz5Ey38I8" alt="">

      </div>
    </div>

  </div>
  <div class="row d-flex justify-content-center">
    <div class="col-3 m-2 back2 rounded EpisodeBox">Episode 1</div>
    <div class="col-3 m-2 back2 rounded EpisodeBox">Episode 2</div>
    <div class="col-3 m-2 back2 rounded EpisodeBox">Episode 3</div>

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
@import url("https://fonts.googleapis.com/css2?family=Fredoka+One&family=Major+Mono+Display&display=swap");

.EpisodeBox {
  height: 125px;
}

.tShadow {
  text-shadow: 1px 1px rgb(137, 176, 174);
}

.hello {
  font-family: 'Fredoka One', cursive;
  font-family: 'Major Mono Display', monospace;
  text-shadow:  1px 1px 2px rgb(255, 214, 186);
}

.profile {
  max-width: 55px;
}

.back1 {
  background-color: rgb(85, 91, 110);
}
.back2 {
  background-color: rgb(137, 176, 174);
}
.back3 {
  background-color: rgb(190, 227, 219);
}
.back4 {
  background-color: rgb(250, 249, 249);
}
.back5 {
  background-color: rgb(255, 214, 186);
}

</style>
