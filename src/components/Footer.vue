<template>
  <footer id="footer">
    <p>Maker Your Burger &copy; 2025</p>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
#footer {
  background-color: #222;
  padding: 20px 0;
  border-top: 4px solid #111;
  color: #fcba03;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 100%;
  margin-top: auto;
}

#footer p {
  margin: 0;
  font-size: 14px;
}
</style>
