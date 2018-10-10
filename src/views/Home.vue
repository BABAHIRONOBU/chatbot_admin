<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/chat.png">
    <HelloWorld msg="환영합니다. 루비봇입니다.^^"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
