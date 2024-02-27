<template>
  <header><h1>Task Tracker</h1></header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<!--scoped style means any style mentioned here is for this specific component named header-->
<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
}
</style>
