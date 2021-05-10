<template>
  <div
    class="home flex-grow-1 d-flex flex-column align-items-center justify-content-center"
  >
    <div class="row">
      <div class="col">
        <h1 class="my-5 mx-3 text-light p-3 rounded align-items-center">
          <span class="mx-2 text-success">Hi, my name is Jacob Gruver.</span>
        </h1>
        <h3 class="my-5 mx-3 text-success p-3 justify-content-start">
          <p>
            I am a Full Stack Software Developer who loves to expand my
            creativity and knowledge in developing fantastic web applications.
          </p>
          <p>
            Web applications should follow several industry standards which
            include,
          </p>
          <ul>
            <li>Design that is professionally pleasing to visit,</li>
            <li>
              Functionality that promotes ease of excess and is simple for all
              users,
            </li>
            <li>And visual animations that make the app feel alive!</li>
          </ul>
        </h3>
      </div>
      <div class="col">
        <div
          class="my-3 mx-3 rounded-circle border border-success img-over-img"
        >
          <img
            src="../assets/img/profile-pic.png"
            class="my-3 mx-3 rounded-circle border border-success prof-pic"
          />
        </div>
        <!-- TODO Make above image become profile pic -->
      </div>
    </div>
    <!-- <div class="row">
      <h4 class="p-3 text-light align-items-center">
        <span class="text-success">
          Apps I Made
        </span>
      </h4>
    </div>
    <div class="row">
      <div class="col mx-3">
        <div class="card app bg-dark">
          <img class="card-img-top p-3" src="../assets/img/bootstrap.png" alt="holder.js/100x180/">
          <div class="card-body">
            <h4 class="card-title text-success">
              Transformers Stats
            </h4>
            <p class="card-text text-success">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam consequuntur quae, hic laudantium explicabo similique optio tenetur? Quisquam mollitia omnis dolor corporis quasi ex deleniti! Ad sed eaque assumenda officia.
            </p>
          </div>
        </div>
      </div>
      <div class="col mx-3">
        <div class="card app bg-dark">
          <img class="card-img-top p-3" src="../assets/img/image.jpg" alt="holder.js/100x180/">
          <div class="card-body">
            <h4 class="card-title text-success">
              Node.js
            </h4>
            <p class="card-text text-success">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum facere pariatur eaque velit ducimus. Porro laboriosam sint facere, temporibus maxime adipisci nam minima sit repellat. Quo inventore velit veniam omnis.
            </p>
          </div>
        </div>
      </div>
      <div class="col mx-3">
        <div class="card app bg-dark">
          <img class="card-img-top p-3" src="../assets/img/image.jpg" alt="holder.js/100x180/">
          <div class="card-body">
            <h4 class="card-title text-success">
              mongoDB
            </h4>
            <p class="card-text text-success">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis fugit minus qui quasi esse earum molestiae, veniam ipsa quo. Quidem non deserunt repudiandae ullam iste modi impedit nesciunt nulla laudantium?
            </p>
          </div>
        </div>
      </div>
    </div>-->
    <div class="row">
      <div class="col">
        <h2 class="my-4 mx-3 pt-3 align-items-center">
          <span class="text-success"> Skills </span>
        </h2>
      </div>
    </div>
    <hr class="solid" />
    <!-- NOTE above line needs to be replaced with a break of some kind -->
    <div class="row">
      <h4 class="pb-3 text-light align-items-center">
        <span class="text-success"> Computer Languages </span>
      </h4>
    </div>
    <div class="row">
      <div class="col mx-3">
        <div class="app card border border-success bg-info">
          <div class="card-body text-success">
            <h1>
              <i class="fa fa-html5 fa-lg pb-2" aria-hidden="true"></i>
            </h1>
            <h4 class="card-title">HTML 5</h4>
            <p class="card-text">
              Strong proficiency in html 5 & implemented html with bootstrap &
              font-awesome.
            </p>
          </div>
        </div>
      </div>
      <div class="col mx-3">
        <div class="app card border border-success bg-info">
          <div class="card-body text-success">
            <h1>
              <i class="fa fa-coffee fa-lg pb-2" aria-hidden="true"></i>
            </h1>
            <h4 class="card-title">JavaScript</h4>
            <p class="card-text">
              I use JavaScript with frontend app scripting as well as backend
              Node.js server scripting. I am also familiar with backend dev tool
              mongoDB.
            </p>
          </div>
        </div>
      </div>
      <div class="col mx-3">
        <div class="app card border border-success bg-info">
          <div class="card-body text-success">
            <h1>
              <i class="fa fa-css3 fa-lg pb-2" aria-hidden="true"></i>
            </h1>
            <h4 class="card-title">CSS 3</h4>
            <p class="card-text">
              I also implement CSS & SCSS within my apps to make them user
              friendly and visually pleasing.
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <h4 class="p-3 text-light align-items-center">
        <span class="text-success"> Vue.js Frameworks </span>
      </h4>
    </div>
    <div class="vue-frame row rounded mx-3 row border border-success bg-info">
      <div class="col-4">
        <img
          class="p-3"
          src="../assets/img/logo.png"
          alt="holder.js/100x180/"
        />
      </div>
      <div class="col-8 pt-5">
        <h3 class="text-success">
          I use the Vue 3 Framework to build my apps. I began using MVP & DOM
          JavaScript patterns before learning and using Vue and have a desire to
          learn more frameworks to expand my proficiency in JavaScript.
        </h3>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>

<style scoped lang="scss">
.home {
  text-align: center;
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
    height: 438px;
    width: 294px;
  }
  hr.solid {
    border-top: 3px solid #bbb;
  }
  .app:hover {
    transition: transform 1s;
    transform: scale(1.05);
  }
  .vue-frame:hover {
    transition: transform 1s;
    transform: scale(1.02);
  }
  .img-over-img {
    background-image: url(../assets/img/node.jpg);
  }
  background-color: #313130;
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
}
</style>
