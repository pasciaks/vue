<template>
  <div class="header">
    <nav>
      <li>
        <img id="github-image" src="../assets/download.png" alt="logo" />
      </li>
      <li>
        <RouterLink to="/">Home</RouterLink>
      </li>
      <li>
        <RouterLink to="/about">About</RouterLink>
      </li>
      <li>
        <RouterLink to="/info">Info</RouterLink>
      </li>
    </nav>
  </div>
</template>

<style>
.header {
  background-color: black;
  color: white;
}

#github-image {
  width: 40px;
  height: 40px;
  overflow: hidden;
  margin-top: -10px;
  margin-left: 10px;
}

a {
  margin: 15px 15px;
}

li {
  display: inline;
  list-style: none;
  vertical-align: top;
  padding-top: 15px;
}

@media (max-width: 768px) {
  li {
    display: inline-block;
    list-style: none;
  }
}

@media (max-width: 180px) {
  header {
    width: 180px;
  }
}

@media (min-width: 1024px) {
  .header {
    display: block;
    background-color: transparent;
    color: black;
    margin: 10px;
    padding: 10px;
  }
}
</style>
