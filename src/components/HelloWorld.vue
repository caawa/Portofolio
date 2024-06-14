<template>
  <nav>
    <div class="navbar">
      <a>Cawwa!</a>

      <i class="cx bx-menu" id="menu-icon"></i>

      <ul>
        <li href="#Home">Home</li>
        <li href="#About">About</li>
        <li href="#Skill">Skill</li>
        <li href="#Project">Project</li>
        <li href="#Project">Contact</li>
      </ul>
    </div>
  </nav>
</template>

<style scoped>
.navbar{
  width: 90%;
  height: 80px;
  margin: 0 auto;
  color: #C46285;
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-family: "Poppins";
  cursor: pointer;
}
.navbar a{
  font-size: clamp(10px, 30px, 30px);
}
.navbar ul{
  list-style-type: none;
  display: flex;
}
.navbar li{
  display: inline;
  margin-right: clamp(10px, 50px, 50px);
}
</style>