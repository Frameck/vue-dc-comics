<template>
  <div class="main-container">
      <main class="main">
          <div class="banner">
              <h4>CURRENT SERIES</h4>
          </div>

          <CardsContainer></CardsContainer>

          <button><a href="#">LOAD MORE</a></button>
      </main>
  </div>
</template>

<script>
import CardsContainer from '../components/CardsContainer.vue'

export default {
    name: 'Main',
    components: {
        CardsContainer
    }
}
</script>

<style>

</style>