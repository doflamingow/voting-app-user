<template>
  <div class="footer">
    Copyright @ Abdur Rahim {{ new Date().getFullYear() }}
  </div>
</template>

<script>
export default {
  name: 'Footer',
}
</script>

<style>
.footer {
  background-color: #4c6ef5;
  color: rgb(216, 204, 204);
  text-align: center;
  padding: 1.2rem 0;
  position: fixed;
  width: 100%;
  bottom: 0;
  left: 0;
  height: 3.5rem;
}
</style>