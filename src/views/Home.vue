<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'Home',
  components: {
    HelloWorld,
  },
  // created() {
  //   // this.$http.get('/herokuapp/api/movie/list.php')
  //   // .then((response) => {
  //   //   console.log(response.data)
  //   // })
  //   // console.log("hk4g4");
    
  // },
};
</script>
