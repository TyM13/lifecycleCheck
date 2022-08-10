<template>
  <div></div>
</template>

<script>
export default {
  beforeCreate: function () {
    console.log(`Currently in beforeCreate`);
  },
  created: function () {
    console.log(`Currently in Create`);
  },
beforeMount: function () {
console.log(`Currently in beforeMount`);
},
mounted: function () {
console.log(`Currently in mounted`);
},


  name: "life-cycles-example",
};
</script>

<style scoped>
</style>