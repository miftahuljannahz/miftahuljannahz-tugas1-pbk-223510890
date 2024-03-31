<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <div class="container">
    <header>
      <div class="logo-wrapper">
        <img alt="Mita Logo" class="logo" src="./assets/mita.jpg" width="125" height="125" />
      </div>

      <div class="content-wrapper">
        <h1 class="header-title">Profil Saya</h1>
        <hr class="divider">
        <h3 class="subheading">
          Miftahuljannah59@student.uir.ac.id <br>
          223510890 | 4D<br><br>
        </h3>
      </div>
    </header>

    <main>
      <TheWelcome />
    </main>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap');

.container {
  max-width: 800px;
  margin: 0 auto;
}

header {
  background-color: grey;
  color: #ffffff;
  padding: 40px 20px;
  text-align: center;
  border-radius: 10px;
}

.logo-wrapper {
  margin-bottom: 20px;
}

.logo {
  border-radius: 50%;
}

.content-wrapper {
  font-family: 'Montserrat', sans-serif;
  text-align: center; 
}

.header-title {
  font-size: 36px;
  margin: 0;
}

.divider {
  width: 50px;
  border: 2px solid #ffffff;
  margin: 20px auto;
}

.subheading {
  font-size: 18px;
  line-height: 1.6;
}

main {
  padding: 20px;
  background-color: #f0f0f0;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}
</style>

