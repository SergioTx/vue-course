<template>
  <div>
    <p>Server Stratus: {{ status }}</p>
    <hr />
    <button @click="changeStatus">Change</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      status: 'Critical'
    };
  },
  methods: {
    changeStatus() {
      this.status = 'Normal';
    }
  }
};
</script>
