<template>
  <div class="main-container">
      <main class="main">
          <div>Content goes here</div>
      </main>
  </div>
</template>

<script>
import jsonData from '../database/dc-comics.json'

export default {
    name: 'Main',
    data() {
        return {
            dcList: jsonData
        }
    }
}
</script>

<style>

</style>