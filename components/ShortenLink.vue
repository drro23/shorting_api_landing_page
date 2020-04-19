<template>
  <div class="container shorten-bg">
    <div class="shorten-container">
      <input class="shorten-input" type="text" placeholder="Shorten a link here..." />
      <button type="button">Shorten It!</button>
      <p class="error">Please add a link</p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.shorten-bg {
  border-radius: 10px;
  background-color: hsl(260, 8%, 14%);
  background-image: url("~assets/images/bg-shorten-desktop.svg") no-repeat;
  height: 130px;
}
.shorten-input {
    width: 100%;
}
.error {
  color: red;
  display: none;
}
</style>