<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <router-link class="navbar-brand d-flex" :to="{ name: 'Home' }">
      <div
        class="app my-2 d-flex p-2 flex-column align-items-center rounded border border-success"
      >
        <span class="font-italic">
          <h3>Jacob A. Gruver</h3>
        </span>
      </div>
    </router-link>
    <div class="d-flex collapse navbar-collapse" id="navbarText">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <!-- <router-link :to="{ name: 'About' }" class="nav-link">
            <i class="app-2 fa fa-user fa-lg" aria-hidden="true"></i>
          </router-link> -->
        </li>
      </ul>
      <span class="navbar-text">
        <div>
          <a
            class="linkedin-route btn btn-outline-primary text-primary mr-3"
            href="https://www.linkedin.com/in/jacob-gruver-6777a61b1/"
          >
            <h5>
              Check out my Linkedin Account -->
              <i class="fa fa-linkedin-square fa-lg"></i>
            </h5>
          </a>
        </div>
      </span>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
  data() {
    return {};
  },
};
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
.nav-link {
  text-transform: uppercase;
}
.nav-item .nav-link.router-link-exact-active {
  color: var(--success);
}
.linkedin-route:hover {
  transition: transform 1.5s;
  transform: scale(1.05);
}
.app:hover {
  transition: transform 1.5s;
  transform: scale(1.1);
}
.app-2:hover {
  transition: transform 1.5s;
  transform: scale(1.5);
}
</style>
