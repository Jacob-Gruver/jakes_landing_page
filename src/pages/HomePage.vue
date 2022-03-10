
<template>
  <div class="home flex-grow-1 d-flex flex-column">
    <div class="row">
      <div class="col-5">
        <h3 class="my-5 mx-3 text-success p-3 pt-5">
          <p>
            I am a software developer who loves to expand my
            creativity and knowledge in developing fantastic web applications.
          </p>
          <p>
            I believe web applications should follow several industry standards which
            include:
          </p>
          <ul>
            <li class="pt-2">
              Design that is professional and pleasing to visit
            </li>
            <li class="pt-2">
              Functionality that promotes ease of access for all
              users
            </li>
            <li class="pt-2">
              Visual animations that make the app feel alive!
            </li>
          </ul>
        </h3>
      </div>
      <div class="col-7 text-center">
        <div class="rounded-circle img-over-img">
          <img
            src="../assets/img/profile-pic.png"
            class="m-3 mt-4 p-1 rounded-circle border border-success prof-pic"
          />
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col">
        <h2 class="my-4 mx-3 pt-3 text-center">
          <span class="text-success"> Apps I Made </span>
        </h2>
      </div>
    </div>
    <!-- App section -->
    <div class="row">
      <div class="col mx-3">
        <div class="card apps">
          <div class="card-body">
            <h4 class="card-title text-success">
              Super Moon!
            </h4>
            <p class="card-text text-success">
              This simple JavaScript game is loads of fun building and playing.
            </p>
          </div>
        </div>
      </div>
      <div class="col mx-3">
        <div class="card apps">
          <div class="card-body">
            <h4 class="card-title text-success">
              App 2
            </h4>
            <p class="card-text text-success">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum facere pariatur eaque velit ducimus. Porro laboriosam sint facere, temporibus maxime adipisci nam minima sit repellat. Quo inventore velit veniam omnis.
            </p>
          </div>
        </div>
      </div>
      <div class="col mx-3">
        <div class="card apps">
          <div class="card-body">
            <h4 class="card-title text-success">
              App 3
            </h4>
            <p class="card-text text-success">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis fugit minus qui quasi esse earum molestiae, veniam ipsa quo. Quidem non deserunt repudiandae ullam iste modi impedit nesciunt nulla laudantium?
            </p>
          </div>
        </div>
      </div>
    </div>
    <!-- End Section -->
    <div class="row">
      <div class="col">
        <h2 class="my-4 mx-3 pt-3 text-center">
          <span class="text-success"> Skills </span>
        </h2>
      </div>
    </div>
    <div class="row justify-content-center">
      <h4 class="pb-3 text-light">
        <span class="text-success"> Computer Languages </span>
      </h4>
    </div>
    <div class="row">
      <div class="col-4">
        <div class="app-card card border border-success bg-info">
          <div class="card-body text-success">
            <div class="text-center">
              <h1>
                <i class="fa fa-html5 fa-lg pb-2" aria-hidden="true"></i>
              </h1>
              <h4 class="card-title">
                HTML 5
              </h4>
            </div>
            <h5 class="card-text">
              Strong proficiency in html 5, bootstrap and
              font-awesome.
            </h5>
          </div>
        </div>
      </div>
      <div class="col-4">
        <div class="app-card card border border-success bg-info ">
          <div class="card-body text-success">
            <div class="text-center">
              <h1>
                <i class="fa fa-coffee fa-lg pb-2" aria-hidden="true"></i>
              </h1>
              <h4 class="card-title">
                JavaScript
              </h4>
            </div>
            <h5 class="card-text">
              I use JavaScript, backend
              Node.js server scripting, mongoDB database, and I am familiar with backend dev tool
              Postman.
            </h5>
          </div>
        </div>
      </div>
      <div class="col-4">
        <div class="app-card card border border-success bg-info">
          <div class="card-body text-success">
            <div class="text-center">
              <h1>
                <i class="fa fa-css3 fa-lg pb-2" aria-hidden="true"></i>
              </h1>
              <h4 class="card-title">
                CSS 3
              </h4>
            </div>
            <h5 class="card-text">
              I implement CSS & SCSS within my apps to make them user
              friendly and visually pleasing.
            </h5>
          </div>
        </div>
      </div>
    </div>
    <div class="row justify-content-center">
      <h4 class="p-3 text-light">
        <span class="text-success"> Vue.js Frameworks </span>
      </h4>
    </div>
    <div class="vue-frame align-self-center row rounded mx-3 row border border-success bg-info">
      <div class="col-4 text-center">
        <img
          class="p-3"
          src="../assets/img/logo.png"
          alt="holder.js/100x180/"
        />
      </div>
      <div class="col-8 pt-5">
        <h3 class="text-success">
          I am familiar with Vue 3.
          I use the Vue 3 Framework using MVC & DOM JavaScript patterns before learning and using Vue and have a desire to
          learn more frameworks to expand my proficiency in JavaScript.
        </h3>
      </div>
    </div>
  </div>
</template>

<script></script>

<style scoped lang="scss">
.home {
  // text-align: center;
  user-select: none;
  animation: fadeInAnimation ease 3s;
  animation-iteration-count: 1;
  animation-fill-mode: forwards;
  @keyframes fadeInAnimation {
    0% {
      opacity: 0;
    }
    100% {
      opacity: 1;
    }
  }
  > img {
    display: block;
    max-width: 20%;
    height: auto;
  }
  .prof-pic {
    text-align: center;
    height: 520px;
    width: 360px;
    background-color: #3fb44f;
  }

  .app-card {
    margin: auto;
    width: 500px;
    height: 220px;
  }

  .app-card:hover {
    transition: transform 1s;
    transform: scale(1.05);
  }
  .apps {
    background-color: aqua;
    margin: auto;
    width: 480px;
    height: 250px;
  }
  .apps:hover {
    transition: transform 1s;
    transform: scale(1.05);
  }
  .vue-frame {
    width: 1420px;
    height: 230px;
  }
  .vue-frame:hover {
    transition: transform 1s;
    transform: scale(1.05);
  }
  .img-over-img {
    background-image: url(../assets/img/node.jpg);
    margin: auto;
    width: 750px;
    height: 562px;
    box-shadow: 0 0 20px 20px #313130 inset;
  }

  background-color: #313130;
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
}
</style>
