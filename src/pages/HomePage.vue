<template>
  <div class="home flex-grow-1 d-flex flex-column align-items-center justify-content-center">
    <div class="row">
      <div class="col">
        <h1 class="my-5 mx-3 text-light p-3 rounded align-items-center">
          <span class="mx-2 text-success">Hi, my name is Jacob Gruver.</span>
        </h1>
        <h3 class="my-5 mx-3 text-success p-3 rounded align-items-center">
          I am a Full Stack Software Developer who began my programming journey attending a C++ class while working for an Electronics Technician degree. Since then I have a desire to solve problems and grow my skills as a developer.
        </h3>
      </div>
      <div class="col">
        <img src="../assets/img/node.jpg" class="my-3 mx-3 rounded-circle border border-success">
        <!-- TODO Make above image become profile pic -->
      </div>
    </div>
    <div class="row">
      <div class="col">
        <h2 class="my-4 mx-3 text-light pt-3 align-items-center">
          <span class="text-success">
            Skills
          </span>
        </h2>
      </div>
    </div>
    <p class="text-success">
      ------------------------------------------------------------------------------------------------------------------------------------------------------------------------
    </p>
    <!-- NOTE above line needs to be replaced with a reak of some kind -->
    <div class="row">
      <h4 class="pb-3 text-light align-items-center">
        <span class="text-success">
          Computer Languages
        </span>
      </h4>
    </div>
    <div class="row">
      <div class="col mx-3">
        <div class="card border border-success bg-info">
          <img class="card-img-top p-3 rounded-circle" src="../assets/img/image.jpg" alt="holder.js/100x180/">
          <div class="card-body">
            <h4 class="card-title text-success">
              HTML 5
            </h4>
            <p class="card-text text-success">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Necessitatibus asperiores labore distinctio, ex minima quas accusantium temporibus earum provident, modi suscipit quo dignissimos at doloribus. Consequuntur delectus placeat error recusandae.
            </p>
          </div>
        </div>
      </div>
      <div class="col mx-3">
        <div class="card border border-success bg-info">
          <img class="card-img-top p-3 rounded-circle" src="../assets/img/image.jpg" alt="holder.js/100x180/">
          <div class="card-body">
            <h4 class="card-title text-success">
              JavaScript
            </h4>
            <p class="card-text text-success">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid enim autem neque numquam ipsam? Deleniti, possimus perferendis earum saepe asperiores quasi! Velit voluptates unde aliquam quaerat neque aperiam quidem ipsam!
            </p>
          </div>
        </div>
      </div>
      <div class="col mx-3">
        <div class="card border border-success bg-info">
          <img class="card-img-top p-3 rounded-circle" src="../assets/img/image.jpg" alt="holder.js/100x180/">
          <div class="card-body">
            <h4 class="card-title text-success">
              CSS
            </h4>
            <p class="card-text text-success">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi veritatis maxime tempore dolorem! Distinctio harum facilis, voluptate iure temporibus, similique incidunt, aut explicabo voluptas esse illo atque eligendi culpa ullam!
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <h4 class="p-3 text-light align-items-center">
        <span class="text-success">
          Software Frameworks
        </span>
      </h4>
    </div>
    <div class="row">
      <div class="col mx-3">
        <div class="card border border-success bg-info">
          <img class="card-img-top p-3" src="../assets/img/logo.png" alt="holder.js/100x180/">
          <div class="card-body">
            <h4 class="card-title text-success">
              Vue.js
            </h4>
            <p class="card-text text-success">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam consequuntur quae, hic laudantium explicabo similique optio tenetur? Quisquam mollitia omnis dolor corporis quasi ex deleniti! Ad sed eaque assumenda officia.
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <h4 class="p-3 text-light align-items-center">
        <span class="text-success">
          Other Skills
        </span>
      </h4>
    </div>
    <div class="row">
      <div class="col mx-3">
        <div class="card border border-success bg-info">
          <img class="card-img-top p-3 rounded-circle" src="../assets/img/image.jpg" alt="holder.js/100x180/">
          <div class="card-body">
            <h4 class="card-title text-success">
              First Skill
            </h4>
            <p class="card-text text-success">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam consequuntur quae, hic laudantium explicabo similique optio tenetur? Quisquam mollitia omnis dolor corporis quasi ex deleniti! Ad sed eaque assumenda officia.
            </p>
          </div>
        </div>
      </div>
      <div class="col mx-3">
        <div class="card border border-success bg-info">
          <img class="card-img-top p-3 rounded-circle" src="../assets/img/image.jpg" alt="holder.js/100x180/">
          <div class="card-body">
            <h4 class="card-title text-success">
              Second Skill
            </h4>
            <p class="card-text text-success">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum facere pariatur eaque velit ducimus. Porro laboriosam sint facere, temporibus maxime adipisci nam minima sit repellat. Quo inventore velit veniam omnis.
            </p>
          </div>
        </div>
      </div>
      <div class="col mx-3">
        <div class="card border border-success bg-info">
          <img class="card-img-top p-3 rounded-circle" src="../assets/img/image.jpg" alt="holder.js/100x180/">
          <div class="card-body">
            <h4 class="card-title text-success">
              Third Skill
            </h4>
            <p class="card-text text-success">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis fugit minus qui quasi esse earum molestiae, veniam ipsa quo. Quidem non deserunt repudiandae ullam iste modi impedit nesciunt nulla laudantium?
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
    }
  }
}
</script>

<style scoped lang="scss">
.home{
  text-align: center;
  user-select: none;
  > img{
    display: block;
    max-width: 100%;
    height: auto;
  }
  background-color: #313130;
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
}
</style>
