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