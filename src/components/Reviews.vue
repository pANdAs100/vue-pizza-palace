<template>
  <div class="reviews">
    <ul>
      <li>REVIEW1</li>
      <li>REVIEW2</li>
      <li>REVIEW3</li>
    </ul>
  </div>
</template>

<script>
  export default {
    name: 'Reviews',
  }
</script>

<style scoped>
  .reviews{
    color: var(--elite-bgColor);
    background: url('../assets/fresh-out-the-oven.jpg');
    background-size: 100% 100%;
    height: 12rem;
  }
  ul{
    text-align: left;
  }
  li{
    display: inline;
    list-style-type: none;
    margin-left: 1em;
  }
</style>