<template>
  <div>
    <div class="page">
      <h1>Creer une nouvelle page de blog</h1>
      <div>
        <label for="Titre de la page">Titre de la page</label
        ><input type="text" />

        <br /><br />

        <label for="Titre de la page">Meta Title</label><input type="text" />

        <br /><br />

        <label for="Titre de la page">Meta Description</label
        ><input type="text" />
      </div>
      <div class="img">
        <form id="avatar" method="post" action="">
          <img href="default/avatar.jpg" />
          <input type="file" name="file1" />
        </form>
      </div>
    </div>
    <br />
    <div class="post">
      <div>
        <label for="Corps du Post"><h3>Corps du Post</h3></label>
      </div>
      <div>
        <input type="text" class="champ" />
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "pageCreation",
};
</script>
<style scoped>
.page {
  overflow: hidden;
}
.page div {
  width: 50%;
  float: left;
}
.post {
  overflow: hidden;
}
.post div {
  width: 50%;
  float: left;
}
.champ {
  width: 600px;
  height: 200px;
}
</style>