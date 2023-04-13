<script>

export default {
 name: "AppHeader",
 data() {
  return {
    links: [
      {
        text: "CHARACTERS",
        url: "#",
        current: false
      },
      {
        text: "COMICS",
        url: "#",
        current: true
      },
      {
        text: "MOVIES",
        url: "#",
        current: false
      },
      {
        text: "TV",
        url: "#",
        current: false
      },
      {
        text: "GAMES",
        url: "#",
        current: false
      },
      {
        text: "COLLECTIBLES",
        url: "#",
        current: false
      },
      {
        text: "VIDEOS",
        url: "#",
        current: false
      },
      {
        text: "FANS",
        url: "#",
        current: false
      },
      {
        text: "NEWS",
        url: "#",
        current: false
      },
      {
        text: "SHOP",
        url: "#",
        current: false
      },
    ]
  }
 }
}

</script>

<template>

  <header>

    <div class="container">
      <img src="../assets/img/dc-logo.png" alt="logo">
      <nav class="navigation">
              <ul class="header-nav">
                  <li v-for="link in links" :class="link.current ? 'active' : ''">
                      <a :href="link.url">{{ link.text }}</a>
                      <span class="underline"></span>
                  </li>
              </ul>
          </nav>
    </div>

  </header>


</template>

<style scoped lang="scss">

header {
  margin-top: 20px;
  display: flex;
}
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.header-nav {
  list-style-type: none;
  display: flex;
  li {
    margin: 0 .5rem;
    padding: .5rem;
    a {
      color: black;
      text-decoration: none;
    }
      &.active {
        color: #0282F9;
      }
      &:hover a {
        color: #0282F9;
        padding-bottom: 59px;
        border-bottom: 4px solid #0282F9;
      }
  }
}


</style>