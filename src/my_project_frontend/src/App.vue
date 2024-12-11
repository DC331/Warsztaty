<template>

<Header/>
</template>

<script>
import header from "./components/header.vue";
import calculator from "./components/calculator.vue";

export default {
  name:"App",
  components:{
    Header,
    calculator,
  },
};
</script>