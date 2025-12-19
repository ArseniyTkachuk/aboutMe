<template>
  <headerC class="myHeader" />

</template>
<script>
import headerC from './components/headerC.vue';

export default {
  components: {
    headerC,
  },

  data() {
    return {

    }
  },
  mounted() {

  },

  methods: {

  }
}

</script>
<style scoped>
* {
  /*Загальні налаштування*/
  margin: 0;
  padding: 0;
}

:global(body) {
  /*Задній фон сайту */
  background: linear-gradient(135deg, #4d0cff, #b000f8, #ff00b3);
  background-size: 200% 200%;
  animation: gradientMove 10s ease infinite;
  font-family: "Roboto Slab", serif;
  margin: 0%;
  height: 100vh;

}

.myHeader {
  background: rgba(115, 114, 116, 0.334);
  text-align: center;
  height: 10vh;
}
</style>