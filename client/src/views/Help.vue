<template>
<div class="container mt-lg-5">
<div class="row align-items-center">
<div class="col">
<div class="card" style="width: 22rem;">
  <img src="../../public/MCFig.jpg" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">Module Coordinator</h5>
    <p class="card-text">
      Some quick example text to build on the card title and make up the bulk of the card's content.
      </p>
      <router-link :to="{name: 'MC Help'}">
    <a href="#" class="btn btn-primary">Details</a>
      </router-link>
  </div>
</div>
</div>
<div class="col">
<div class="card" style="width: 22rem;">
  <img src="../../public/STUFig.jpg" class="card-img-top" alt="..." style="height: 14rem;">
  <div class="card-body">
    <h5 class="card-title">Student</h5>
    <p class="card-text">
      Some quick example text to build on the card title and make up the bulk of the card's content.
      </p>
      <router-link :to="{name: 'Student Help'}">
    <a href="#" class="btn btn-primary">Details</a>
      </router-link>
  </div>
</div>
</div>
<div class="col">
<div class="card" style="width: 22rem;">
  <img src="../../public/TAFig.jpg" class="card-img-top" alt="Teacher Assistant">
  <div class="card-body">
    <h5 class="card-title">Teacher Assistant</h5>
    <p class="card-text">
      Some quick example text to build on the card title and make up the bulk of the card's content.
      </p>
      <router-link :to="{name: 'TA Help'}">
    <a href="#" class="btn btn-primary">Details</a>
      </router-link>
  </div>
</div>
</div>
</div>
</div>

</template>
