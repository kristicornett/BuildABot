<template>
  <header>
    <nav>
      <ul>
        <li class="nav-item">
          <img class="logo" src="./assets/build-a-bot-logo.png"/>
          Build-a-Bot
        </li>
      </ul>
    </nav>
  </header>
  <main>
  <Homepage />
</main>
</template>

<script>
import Homepage from './components/Homepage.vue';

export default {
  name: 'App',
  components: {
    Homepage,
  },
};
</script>

<style>
body {
  background: linear-gradient(to bottom, #555, #999);
  background-attachment: fixed;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
main{
  margin: 0 auto;
  padding: 30px;
  background-color:white;
  width: 1024px;
  min-height: 300px;
}

</style>
