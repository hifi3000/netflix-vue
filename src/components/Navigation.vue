<template>
  <div class="nav-bar">
    <div class="navbar_left">
      <a href="/?display=in" style="background-color: #E7E7E7;color: #B9090B;">NEW</a>
      <a href="/?display=out">LEAVING</a>
      <a href="/?display=fav">FAV</a>
    </div>
    <div class="navbar-left margin-a">
      <form action="/">
        <input type="text" name="search">
        <input type="submit" value="search">
      </form>
    </div>
    <div class="navbar_right">
      <a class="factive" href="javascript:void(0);" onclick="toggleMenu('filter')">
        FILTER
      </a>
    </div>
  </div>
</template>

<style>
.nav-bar {
  background-color: #2E2E2E;
  display: flex;
  justify-content: space-between;
  color: #FFFFFF;
  margin: auto;
  font-size: 14px;
}

.navbar_left {
  display: flex;
  width: 33.3%;
}

.margin-a {
  margin: auto;
}

.navbar_right {
  width: 33.3%;
  display: flex;
  justify-content: flex-end;
}

.nav-bar a {
  color: #FFFFFF;
  padding: 0.5rem;
}

a {
  text-decoration: none;
  color: black;
}

input[type="text" i] {
  padding: 1px 2px;
}

input[type=submit] {
  text-transform: uppercase;
  padding: 3px 5px;
  background: lightgrey;
  border: 0 none;
  cursor: pointer;
  -webkit-border-radius: 5px;
  border-radius: 0;
}
</style>