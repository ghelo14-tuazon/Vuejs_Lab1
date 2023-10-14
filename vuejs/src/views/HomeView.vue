<template>
  <div>
    <HelloWorld />
    <Main />
    <Footer />
  </div>
</template>

<script>
import { defineComponent } from 'vue';

// Components
import HelloWorld from '../components/HelloWorld.vue';
import Footer from '../components/Footer.vue';
import Main from '../components/Main.vue';

export default defineComponent({
  name: 'HomeView',

  components: {
    HelloWorld,
    Footer,
    Main,
  },
});
</script>
