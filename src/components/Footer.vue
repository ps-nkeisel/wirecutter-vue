<template>
  <div class="footer text-center p-2 fixed-bottom bg-light">
    <span class="mr-5">Copyright 2020 SiteName</span>
    <b-link href="#">Privacy Policy</b-link>
  </div>
</template>

<script>
export default {
  name: 'Footer',
}
</script>

<style>
.footer {
  z-index: 1;
  box-shadow: 0 8px 17px 0 rgba(0,0,0,0.2), 0 6px 20px 0 rgba(0,0,0,0.19);
}
</style>
