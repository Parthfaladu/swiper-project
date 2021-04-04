<template>
  <div class="home">
    <Test />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Test from '@/components/Test.vue'

export default {
  name: 'Home',
  components: {
    Test
  }
}
</script>
