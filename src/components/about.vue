<template>
  <div class="about container">
    <h1>About Us</h1>
    <p class="lead">{{ msg }}</p>
    <p>
      We are passionate about everything feline! From sharing tips on how to
      care for your cat, to understanding their behavior, we’re dedicated to
      helping cat lovers build a stronger bond with their furry friends.
    </p>
    <button class="btn btn-primary">Learn More</button>
  </div>
</template>

<script>
export default {
  name: "about",
  data() {
    return {
      msg: "Learn more about our love for cats and how we help cat owners.",
    };
  },
};
</script>

<style scoped>
.about {
  margin-top: 30px;
}
</style>
