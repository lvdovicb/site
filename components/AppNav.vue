<template>
  <div>
    <ul>
      <li>
        <nuxt-link exact to="/">Home</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/projects">Projects</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/more">more</nuxt-link>
      </li>
    </ul>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
// * {
//   outline: 1px solid teal;
// }
@import url("https://fonts.googleapis.com/css?family=Alatsi&display=swap");

div {
  font-family: "Alatsi", sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
  max-width: 100vw;
  height: 50px;
  font-size: 1.5rem;
  background-color: #35495e;
}
ul {
  margin: 0;
}
li {
  font-family: "Alatsi", sans-serif;
  display: inline-block;
  margin-right: 30px;

  a {
    color: #eee;
    text-decoration: none;
  }
}
.nuxt-link-active {
  border-bottom: 3px solid #ff5aa1;
  border-top: 2px solid #ff5aa1;
  text-decoration: none;
  // text-decoration: overline underline 3px solid #ff5aa1;
  // text-underline-position: under;
}
</style>
