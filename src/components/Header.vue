<template>
  <h1>{{ title }}</h1>
</template>

<script>
export default {
  name: "Header",
  props: {
    title: {
      type: String,
      default: "Task Tracker",
    },
  },
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
