<template>
  <div class="calculation-container">
    <h1>B4</h1>
    <h1>Calculator</h1>
    
    <div class="inputs">
      <input type="text" v-model.number="num1"/>
      <input type="text" v-model.number="num2"  />
    </div>
    
    <div class="results">
      <p>Cộng: {{ add(num1, num2) }}</p>
      <p>Trừ: {{ subtract(num1, num2) }}</p>
      <p>Nhân: {{ multiply(num1, num2) }}</p>
      <p>Chia: {{ divide(num1, num2) }}</p>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      num1: 0,
      num2: 0,
    };
  },
  methods: {
    add(a, b) {
      return a + b;
    },
    subtract(a, b) {
      return a - b;
    },
    multiply(a, b) {
      return a * b;
    },
    divide(a, b) {
      return b !== 0 ? a / b : 'khong chia duoc';
    },
  },
};
</script>

<style scoped>

</style>
