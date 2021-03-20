<template>
  <div class="blogs">
    <img src="" alt="" />
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla laudantium
      repudiandae, numquam enim mollitia debitis ab facere unde culpa, vel, quae
      itaque quis voluptatum omnis. Velit vel necessitatibus qui cumque!
    </p>
    <button>{{ Button }}</button>
  </div>
</template>
<script>
export default {
  name: "blog",
  data() {
    return {
      Button: "Editer",
    };
  },
};
</script>
<style scoped>
.blogs {
  width: 500px;
  border: 5px solid rgb(111, 41, 97);
  border-radius: 0.5em;
  padding: 10px;
}
</style>