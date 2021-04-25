<template>
  <div class="bg-warning text-primary p-2">
    <h2>{{ message }}</h2>
  </div>
</template>

<script>
export default {
  name: "hijoComponent",
  data() {
    return {
      message: "Soy el hijo",
    };
  },
};
</script>
