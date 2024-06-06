<template>
  <div class="search-box">
    <input type="search" @input="inputText = $event.target.value" />
  </div>
  <p>{{ inputText }}</p>
</template>
<script>
export default {
  name: "SearchBarComponent",
  data() {
    return {
      inputText: "hello",
    };
  },
};
</script>
<style></style>
