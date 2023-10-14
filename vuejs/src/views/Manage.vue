<template>
  <div>
    <Header />
    <Sidebar />
  
   
  </div>
</template>

<script>
import { defineComponent } from 'vue';

// Components
import Header from '../components/Admin/Header.vue';
import Sidebar from '../components/Admin/Sidebar.vue';



export default defineComponent({
  name: 'Manage',

  components: {
    Header,
    Sidebar,


 
  },
});
</script>
