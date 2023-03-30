<script>
export default {
  name: "TheHeader",
  data() {
    return {
      navLinks: [
        {
          href: "#characters",
          text: "Characters",
        }, {
          href: "#comics",
          text: "Comics",
        }, {
          href: "#movies",
          text: "Movies",
        }, {
          href: "#Tv",
          text: "Tv",
        }, {
          href: "#games",
          text: "Games",
        }, {
          href: "#collectible",
          text: "Collectible",
        }, {
          href: "#videos",
          text: "Video",
        }, {
          href: "#fans",
          text: "Fans",
        }, {
          href: "#news",
          text: "News",
        }, {
          href: "#shop",
          text: "Shop",
        }
      ]
    }
  }
};
</script>

<template>
  <header>
    <nav>
      <div class="brand">
        <img src="/img/dc-logo.png" alt="">
      </div>

      <ul class="navbar-links">
        <li v-for="(link, indice ) in navLinks" :key="indice"><a class="nav-link" href="link.href">{{ link.text }}</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<style scoped lang="scss">
@use "../styles/partials/variables" as *;


header {
  background-color: $color-navbar-bg;
  min-height: 20vh;
}

.brand {
  text-align: start;
  padding-top: 25px;
  padding-left: 10px;
}

.navbar-links {
  display: flex;
  justify-content: end;
  align-items: center;
  list-style: none;

  .nav-link {
    padding: .5rem 1rem;
    color: black;
    text-decoration: none;
    display: inline-block;

    &:hover {
      text-decoration: underline;
      color: $color-primary;
    }
  }
}
</style>


