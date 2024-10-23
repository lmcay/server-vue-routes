<template>
  <div class="blog container">
    <h1>Cat Blog</h1>
    <p class="lead">{{ msg }}</p>
    <ul class="list-group">
      <li class="list-group-item">
        Post 1: The Best Cat Breeds for Apartments
      </li>
      <li class="list-group-item">
        Post 2: How to Keep Your Cat Healthy and Happy
      </li>
      <li class="list-group-item">Post 3: Understanding Your Cat's Behavior</li>
    </ul>
    <button class="btn btn-success mt-3">Read More</button>
  </div>
</template>

<script>
export default {
  name: "blog",
  data() {
    return {
      msg: "Discover tips, tricks, and stories about cats!",
    };
  },
};
</script>

<style scoped>
.blog {
  margin-top: 30px;
}
</style>
