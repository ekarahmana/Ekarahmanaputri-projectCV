<template>
    <main>
     <nav class="navbar">
    <div class="container">
      <div class="logo">
        <a href="#">Eka Rahmana Putri</a>
      </div>
      <div class="menu">
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Skill</a></li>
        </ul>
      </div>
    </div>
  </nav>
    </main>
</template>
<style scoped>
.navbar {
  background-color: #776a6a;
  color: #fff;
  padding: 10px 0;
}

.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
  font-size: 1.2em;
}

.menu ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

.menu ul li {
  display: inline;
}

.menu ul li a {
  color: #fff;
  text-decoration: none;
  padding: 10px;
}

.menu ul li a:hover {
  background-color: #555;
}
</style>