<template>
  <div class="p-5 bg-primary text-white">
    <h2>{{ message }}</h2>
    <hijo-component />
  </div>
</template>

<script>
import hijoComponent from "./Hijo.vue";

export default {
  name: "padreComponent",
  data() {
    return {
      message: "Soy el padre",
    };
  },
  components: {
    hijoComponent,
  },
};
</script>
