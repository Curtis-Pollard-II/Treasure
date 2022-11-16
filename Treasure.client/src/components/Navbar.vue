<template>
  <nav class="navbar navbar-expand-lg  back4 px-3">
    <router-link class="navbar-brand d-flex" :to="{ name: 'Home' }">
      <div class="d-flex flex-column align-items-center flex-row">
        <p class="hello fs-7 small p-0 m-0">Another <br> Man's <br> Treasure</p>
      </div>
    </router-link>
    <button
      class="navbar-toggler"
      type="button"
      data-bs-toggle="collapse"
      data-bs-target="#navbarText"
      aria-controls="navbarText"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarText">
      <ul class="navbar-nav me-auto">
        <li>
          <router-link :to="{ name: 'About' }" class="btn text-dark lighten-30 selectable text-uppercase">
            About
          </router-link>
        </li>
        <li>
          <router-link :to="{ name: 'Episodes' }" class="btn text-dark lighten-30 selectable text-uppercase">
            Episodes
          </router-link>
        </li>
        <li>
          <router-link :to="{ name: 'Guests' }" class="btn text-dark lighten-30 selectable text-uppercase">
            Guests
          </router-link>
        </li>

      </ul>
      <!-- LOGIN COMPONENT HERE -->
      <Login />
    </div>
  </nav>
</template>

<script>
import Login from './Login.vue'
export default {
  setup() {
    return {}
  },
  components: { Login }
}
</script>

<style scoped>
a:hover {
  text-decoration: none;
}

.nav-link {
  text-transform: uppercase;
}

.navbar-nav .router-link-exact-active {
  border-bottom: 2px solid var(--bs-success);
  border-bottom-left-radius: 0;
  border-bottom-right-radius: 0;
}

@media screen and (min-width: 768px) {
  nav {
    height: 64px;
  }
}

.small {
  font-size: small;
}
.hello {
  font-family: 'Fredoka One', cursive;
  font-family: 'Major Mono Display', monospace;
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
