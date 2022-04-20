<template>
  <div class="content">
    <Tutorial />
    <NuxtLogo />
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "IndexPage",
});
</script>

<style>
.content {
  background-color: #e5ebf1;
}
</style>