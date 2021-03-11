<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <router-link class="navbar-brand d-flex" :to="{ name: 'Home' }">
      <div class="my-2 d-flex p-2 flex-column align-items-center rounded border border-success">
        <span class="font-italic">
          <h3>
            Jacob A. Gruver
          </h3>
        </span>
      </div>
    </router-link>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarText"
      aria-controls="navbarText"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon" />
    </button>
    <div class="collapse navbar-collapse" id="navbarText">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <router-link :to="{ name: 'Home' }" class="nav-link">
            <i class="fa fa-home fa-lg"></i>
          </router-link>
        </li>
        <li class="nav-item">
          <router-link :to="{ name: 'About' }" class="nav-link">
            <i class="fa fa-user fa-lg"></i>
          </router-link>
        </li>
      </ul>
      <span class="navbar-text">
        <!-- <a href="gruvinbro@Gmail.com">
          <i class="fa fa-envelope-o fa-lg"></i>
        </a> -->
        <!-- <p class="text-success"> Email: gruvinbro@Gmail.com </p> -->
        <div>
          <a class="linkedin-route btn btn-outline-primary text-primary mr-3" href="https://www.linkedin.com/in/jacob-gruver-6777a61b1/">
            <h5>
              Check out my Linkedin Account --> <i class="fa fa-linkedin-square fa-lg"></i>
            </h5>
          </a>
        </div>

        <!-- <div class="dropdown">
          <div
            class="dropdown-toggle"
            @click="state.dropOpen = !state.dropOpen"
          >
            <img
              :src="user.picture"
              alt="user photo"
              height="40"
              class="rounded"
            />
            <span class="mx-3">{{ user.name }}</span>
          </div>
          <div
            class="dropdown-menu p-0 list-group w-100"
            :class="{ show: state.dropOpen }"
            @click="state.dropOpen = false"
          >
            <router-link :to="{ name: 'Account' }">
              <div class="list-group-item list-group-item-action hoverable">
                Account
              </div>
            </router-link>
            <div
              class="list-group-item list-group-item-action hoverable"
              @click="logout"
            >
              logout
            </div>
          </div>
        </div> -->
      </span>
    </div>
  </nav>
</template>

<script>
// import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
// import { faCoffee } from '@fortawesome/free-solid-svg-icons'

export default {
  name: 'Navbar',
  // components: { FontAwesomeIcon },
  data() {
    return {
      // show: false,
      // coffeeCup: faCoffee.icon
    }
  }
}
</script>

<style scoped>
.dropdown-menu {
  user-select: none;
  display: block;
  transform: scale(0);
  transition: all 0.15s linear;
}
.dropdown-menu.show {
  transform: scale(1);
}
.hoverable {
  cursor: pointer;
}
a:hover {
  text-decoration: none;
}
.nav-link{
  text-transform: uppercase;
}
.nav-item .nav-link.router-link-exact-active{
  color: var(--success);
}
.linkedin-route:hover{
  transition: transform 1.5s;
  transform: scale(1.1);
}
</style>
