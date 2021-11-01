<template>
  <div class="home container">
    <Calculate msg="Welcome to Your Vue.js App" />
    <Todolist title="My todo list" />
  </div>
</template>

<script>
// @ is an alias to /src
import Calculate from "@/components/Calculate.vue";
import Todolist from "../components/todolist.vue";

export default {
  name: "Home",
  components: {
    Calculate,
    Todolist
},
};
</script>
