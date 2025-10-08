<template>
  <Banner/>
  <div class="main-container">
    <h1>Monte seu Burger</h1>
    <Formulario />
  </div>
</template>

<script>
import Banner from '@/components/Banner.vue';
import Formulario from '@/components/Formulario.vue';

export default {
  nome: "Home",
  components: {
    Banner,
    Formulario,
  }
}
</script>




