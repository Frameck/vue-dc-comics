<template>
  <div class="header-container">
      <header class="main-header">
          <img class="logo" src="../assets/dc-logo.png" alt="dc-logo">
          <ul>
            <li v-for="item,i in navbarItems" :key="i">
              <a 
              :href="item.href + item.text"
              :class="i === currentActive ? 'active' : ''"
              @click.prevent="currentActive = i">
                {{ item.text.toUpperCase() }}
              </a>
            </li>
          </ul>
      </header>
  </div>
</template>

<script>
export default {
  name: 'Header',
  data() {
    return {
      navbarItems: [
        {
          text: 'characters',
          href: '#'
        },
        {
          text: 'comics',
          href: '#'
        },
        {
          text: 'movies',
          href: '#'
        },
        {
          text: 'tv',
          href: '#'
        },
        {
          text: 'games',
          href: '#'
        },
        {
          text: 'collectibles',
          href: '#'
        },
        {
          text: 'videos',
          href: '#'
        },
        {
          text: 'fans',
          href: '#'
        },
        {
          text: 'news',
          href: '#'
        },
        {
          text: 'shop',
          href: '#'
        }
      ],
      currentActive: 1
    }
  }
}
</script>

<style>

</style>