<template></template>

<script>
import ComponentA from "./components/componentA";
import ComponentB from "./components/componentB";
// export default {
//   components: {
//     ComponentA,
//     ComponentB,
//   },
// };

var app = new Vue({
  el: "#app",
  components: {
    ComponentA: ComponentA,
    ComponentB: ComponentB,
  },
});
</script>

