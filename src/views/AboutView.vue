<template>
  <div class="about bg-dark">
    <navbar/>
    <h1>This is an about page</h1>
  </div>
</template>

<script>
// bagian untuk import componnent (componen buat isi tampilan navbar,dll)
import Navbar from '@/components/Navbar.vue';

// untuk memanggil variable import diatas
export default {
    name: 'AboutHome',
    components: {
        Navbar,
    }
}
</script>