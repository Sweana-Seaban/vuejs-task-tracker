<template>
  <header>
    <h1>{{ title }}</h1>
    <Button text="Add Task" color="green"></Button>
    <Button text="Edit Task" color="blue"></Button>
    <Button text="Delete Task" color="red"></Button>
  </header>
</template>

<script>
import Button from "./Button";
export default {
  name: "Header",
  props: {
    title: String,
  },
  //register as a component
  components: {
    Button,
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
