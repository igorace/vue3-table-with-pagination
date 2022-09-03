<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <TableWithPagination />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import TableWithPagination from "./components/TableWithPagination.vue";

export default defineComponent({
  name: "App",
  components: {
    TableWithPagination,
  },
});
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
