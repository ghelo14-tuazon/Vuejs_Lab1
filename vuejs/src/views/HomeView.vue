<template>
  <div>
    <Header />
    <Main />
    <Footer />
  </div>
</template>

<script>
import { defineComponent } from 'vue';

// Components
import Header from '../components/User/Header.vue';
import Footer from '../components/User/Footer.vue';
import Main from '../components/User/Main.vue';

export default defineComponent({
  name: 'HomeView',

  components: {
    Header,
    Footer,
    Main,
  },
});
</script>
