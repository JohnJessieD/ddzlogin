<template>
  <div>
    <h1>Welcome to the Home View</h1>

    <!-- Include the LoginView component -->
    <LoginView />

    <!-- Other content of the HomeView component -->
    <HelloWorld />
  </div>
</template>

<script>
import { defineComponent } from 'vue';

// Components
import HelloWorld from '../components/HelloWorld.vue';
import LoginComponent from '../components/Login.vue'; // Adjust the path as needed

export default defineComponent({
  name: 'HomeView',

  components: {
    HelloWorld,
    Login,
  },
});
</script>
