<template>
  <div>
    <HelloWorld />
    <Footer />
  </div>
</template>

<script>
import { defineComponent } from 'vue';

// Components
import HelloWorld from '../components/HelloWorld.vue';
import Footer from '../components/Footer.vue';

export default defineComponent({
  name: 'HomeView',

  components: {
    HelloWorld,
    Footer,
  },
});
</script>
