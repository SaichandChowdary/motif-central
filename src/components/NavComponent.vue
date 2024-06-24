<template>
  <nav class="navbar navbar-expand-lg navbar-dark navbg">
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="#">Proteins</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavComponent",
};
</script>

<style>
.navbg {
  background-color: #001798ee;
  height: 60px;
}
</style>
