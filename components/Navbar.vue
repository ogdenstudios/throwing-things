<template>
  <nav>
    <ul>
      <li>
        <nuxt-link to="/">Home</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/shows">Shows</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/contact">Contact</nuxt-link>
      </li>
    </ul>
  </nav>
</template>

<style lang="scss" scoped>
nav {
  padding: 1em;
  padding-left: 0;
  padding-top: 0;
  width: 100%;
  a {
    color: #000000;
    text-decoration: none;
  }
  ul {
    display: flex;
    line-height: 1;
    list-style: none;
    margin-left: 0;
    padding-left: 0;
    width: 100%;
    li {
      margin-left: 0;
      margin-right: 2em;
      padding: 2em 0;
    }
  }
}
</style>
