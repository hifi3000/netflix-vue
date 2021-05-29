<template>
  <div class="topnav">
  <a href="/" class="active">netflix: hifibrown</a>
  <div id="myLinks">
      <a href="/?user=default">[X]</a>
      <a href="/?user=hifibrown">hifibrown</a><a href="/?user=annerose">annerose</a><a href="/?user=colin">colin</a>  </div>
  <a href="javascript:void(0);" class="icon" onclick="toggleMenu('myLinks')">
      <i class="fa fa-bars"></i>
  </a>
  </div>
</template>

<style scoped>
.topnav {
  overflow: hidden;
  background-color: #454545;
  position: relative;
}

.topnav a {
  color: #B9090B;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
  display: block;
}

.active {
  background-color: #FFFFFF;
  color: white;
}

a {
  text-decoration: none;
  color: black;
}

.topnav #myLinks {
  display: none;
  color: #FFFFFF;
}

.topnav #myLinks a {
  color: #FFFFFF;
}

.topnav a {
  color: #B9090B;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
  display: block;
}

.topnav a.icon {
  background: #454545;
  display: block;
  position: absolute;
  right: 0;
  top: 0;
}
</style>