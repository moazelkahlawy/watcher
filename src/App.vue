<template>
  <TheNave />
  <router-view />
  <TheFooter/>
</template>

<script>
import TheNave from "@/components/TheNave.vue";
import TheFooter from "@/components/TheFooter.vue";
export default {
  components: {
    TheNave,
    TheFooter
  },
};
</script>

<style>
#app {
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
  color: #000000;
  background-color: #ffffff;
}

#app a,
#app a:hover,
#app a:focus {
  text-decoration: none;
}

/* #app a:hover,
#app a:focus {
  color: initial;
} */

#app .btn,
#app .btn:focus {
  outline: none !important;
  -webkit-box-shadow: none;
          box-shadow: none;
}
</style>
