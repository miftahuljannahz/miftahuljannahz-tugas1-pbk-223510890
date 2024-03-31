<template>
  <div class="greetings">
    <h1>{{ msg }}</h1>
    <h3>Welcome to my profile!</h3>
  </div>
</template>

<script>
export default {
  data() {
    return {
      msg: "Hello, World!"
    };
  }
};
</script>

<style scoped>
.greetings {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
}

h1 {
  font-weight: 500;
  font-size: 2.6rem;
  margin-top: -10px;
}

h3 {
  font-size: 1.2rem;
}

@media (min-width: 1024px) {
  .greetings {
    justify-content: flex-start;
  }
}
</style>
