<template>
  <div id="main-banner">
    <h1>Make Your Burger</h1>
  </div>
</template>

<script>
export default {
  name: "Banner",
};
</script>

<style scoped>
#main-banner {
  background-image: url("~@/../public/img/burger.jpg");
  background-position: center center;
  background-size: cover;
  background-repeat: no-repeat;
  justify-content: flex-start;
  height: 70vh;
  min-height: 700px;
  max-height: 600px;
  display: flex;
  align-items: center;
}

#main-banner h1 {
  color: #fff;
  text-align: center;
  font-size: clamp(2.5rem, 5vw, 4rem);
  background-color: rgba(34, 34, 34, 0.8);
  padding: 20px 40px;
  border-radius: 8px;
  backdrop-filter: blur(5px);
}

/* Responsividade para telas menores */
@media (max-width: 768px) {
  #main-banner {
    height: 50vh;
    min-height: 300px;
    padding: 0 10px;
  }

  #main-banner h1 {
    font-size: clamp(1.8rem, 4vw, 2.5rem);
    padding: 15px 25px;
  }
}

/* Para telas muito grandes */
@media (min-width: 1920px) {
  #main-banner {
    height: 60vh;
    max-height: 700px;
  }

  #main-banner h1 {
    font-size: 4.5rem;
  }
}
</style>
