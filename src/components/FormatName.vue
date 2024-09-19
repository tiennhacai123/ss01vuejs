<template>
  <div >
    <h2>B6</h2>
    <h3>Ho va ten: {{ formatName(user) }}</h3>
  </div>
</template>

<script>
export default {
  data() {
    return {
      user: {
        firstName: "Le Dien",
        lastName: "Tien",
      },
    };
  },
  methods: {
    formatName(user) {
      return `${user.firstName} ${user.lastName}`;
    },
  },
};
</script>

<style scoped>

</style>
