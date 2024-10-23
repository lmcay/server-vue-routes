<template>
  <div class="gallery container">
    <h1>Gallery</h1>
    <p class="lead">{{ msg }}</p>
    <div class="row">
      <div class="col-md-4">
        <img
          src="https://as1.ftcdn.net/v2/jpg/02/36/99/22/1000_F_236992283_sNOxCVQeFLd5pdqaKGh8DRGMZy7P4XKm.jpg"
          class="img-thumbnail"
          alt="Cat Image 1"
        />
      </div>
      <div class="col-md-4">
        <img
          src="https://as2.ftcdn.net/v2/jpg/02/66/72/41/1000_F_266724172_Iy8gdKgMa7XmrhYYxLCxyhx6J7070Pr8.jpg"
          class="img-thumbnail"
          alt="Cat Image 2"
        />
      </div>
      <div class="col-md-4">
        <img
          src="https://as2.ftcdn.net/v2/jpg/03/03/62/45/1000_F_303624505_u0bFT1Rnoj8CMUSs8wMCwoKlnWlh5Jiq.jpg"
          class="img-thumbnail"
          alt="Cat Image 3"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "gallery",
  data() {
    return {
      msg: "Look at this cool cats!",
    };
  },
};
</script>

<style scoped>
.gallery {
  margin-top: 30px;
}
.img-thumbnail {
  margin-bottom: 20px;
}
</style>
