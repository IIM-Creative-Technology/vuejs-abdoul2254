
<template>
  <div>
    <button><a href="/pageCreation">Créer une page</a></button>
    <blog />
    <blog />
    <blog />
    <blog />
    <blog />
  </div>
</template>
<script>
import blog from "../components/blog";

export default {
  name: "Home",

  components: {
    blog,
  },
};
</script>
<style scoped>
button {
  color: blanchedalmond;
  width: 150px;
  height: 50px;
}

:hover button {
  color: rgb(5, 5, 4);
}
a {
  color: black;
}
</style>