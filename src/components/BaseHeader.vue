<template>
  <div class="container">
      <header class="header">
          <div class="header__logo">
              <img src="../assets/img/dc-logo.png" alt="logo">
          </div>
          <nav class="header__nav">
              <ul>
                  <li v-for="(link,index) in links" :key="index" ><a :href="link.url" :class="{active : link.current}">{{link.name}}</a></li>
              </ul>
          </nav>
      </header>
  </div>
</template>

<script>
export default {
    name: "BaseHeader",
    data() {
        return {
            links:[
                {
                    name: "CHARACTERS",
                    url: "#",
                    current: false,
                },
                {
                    name: "COMICS",
                    url: "#",
                    current: true,
                },
                {
                    name: "MOVIES",
                    url: "#",
                    current: false,
                },
                {
                    name: "TV",
                    url: "#",
                    current: false,
                },
                {
                    name: "GAMES",
                    url: "#",
                    current: false,
                },
                {
                    name: "COLLECTIBLES",
                    url: "#",
                    current: false,
                },
                {
                    name: "VIDEO",
                    url: "#",
                    current: false,
                },
                {
                    name: "FANS",
                    url: "#",
                    current: false,
                },
                {
                    name: "NEWS",
                    url: "#",
                    current: false,
                },
                {
                    name: "SHOP",
                    url: "#",
                    current: false,
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    
    
    &__nav {
        ul {
            display: flex;
            list-style: none;
            gap: 1.25rem;

            li {
                a {
                    text-decoration: none;
                    color: black;
                    font-weight: 700;
                    padding: 4rem 0;
                    display: inline-block;

                    &.active {
                        color: var(--color-primary);
                        border-bottom: .25rem solid var(--color-primary);
                    }
                }
            }
        }
    }
}

</style>