<template>
  <div class="header">
    <nav>
      <li class="cropped">
        <img src="../assets/download.png" alt="logo" />
      </li>
      <li>
        <RouterLink to="/">Home</RouterLink>
      </li>
      <li>
        <RouterLink to="/about">About</RouterLink>
      </li>
      <liv>
        <RouterLink to="/header">Header Only</RouterLink>
      </liv>
    </nav>
  </div>
</template>

<style>
.header {
  background-color: black;
  color: white;
}

a {
  padding: 0 10px;
  margin: 0 5px;
  border: 1px dashed gold;
}

li {
  display: inline;
  list-style: none;
  vertical-align: middle;
}

img {
  width: 40px;
  height: 40px;
}

.cropped img {
  overflow: hidden;
  border: 1px solid black;
  margin-top: 5px;
}

@media (max-width: 768px) {
  /* .header {
    background-color: cyan;
  } */
  li {
    display: inline-block;
    list-style: none;
  }
}

@media (max-width: 380px) {
  /* .header {
    background-color: yellow;
  } */
  li {
    display: inline-block;
    list-style: none;
  }
}

@media (max-width: 280px) {
  .header {
    display: none;
  }
  li {
    display: inline-block;
    list-style: none;
  }
}
</style>
