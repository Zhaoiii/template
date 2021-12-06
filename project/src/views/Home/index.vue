<template>
  <div class="home">
  <HelloWorldVue msg='hello v3'/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import HelloWorldVue from '@/components/Home/HelloWorld.vue'

export default defineComponent({
  name: 'Home',
  components: {
    HelloWorldVue
  }
})
</script>
