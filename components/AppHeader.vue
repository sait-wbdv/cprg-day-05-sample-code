<template>
  <header>
    <div>LOGO</div>
    <nav>
      <NuxtLink to="login">Log In</NuxtLink>
      <NuxtLink to="signup">Sign Up</NuxtLink>
    </nav>
    <div>
      <Logout />
    </div>
  </header>
</template>

<style scoped>
header {
  background-color: black;
  display: flex;
  justify-content: space-between;
  padding: 1rem;
}
nav {
  display: flex;
  justify-content: space-around;
  gap: 2rem;
}
a,
div {
  color: white;
  text-decoration: none;
}
a:hover {
  color: lightblue;
}
</style>
