<template>
  <div class="my-page">
    <my-component class="my-page__component" />
    <br>
    <p>The box above is blue (correct) on a dev environment and red (wrong) after building the project.</p>
  </div>
</template>

<script>
import MyComponent from '~/components/MyComponent.vue'

export default {
  components: {
    MyComponent
  }
}
</script>

<style>
.my-page {
  margin: 5rem;
}
.my-page__component {
  background-color: blue;
}
</style>
