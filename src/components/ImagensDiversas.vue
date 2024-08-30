<template>
  <div class="imagens-container">
    <h1>Galeria de Imagens</h1>
    <div class="gallery">
      <img src="@/assets/leite.png" alt="Chocolate ao Leite" class="gallery-item">
      <img src="@/assets/morango.png" alt="Morango" class="gallery-item">
      <img src="@/assets/castanha.png" alt="Castanha do Pará" class="gallery-item">
      <img src="@/assets/ninho.png" alt="Ninho" class="gallery-item">
      <img src="@/assets/trufado.png" alt="Trufado" class="gallery-item">
      <img src="@/assets/caramelo.png" alt="Caramelo Salgado" class="gallery-item">
    </div>
  </div>
</template>

<script>
export default {
  name: 'ImagensDiversas'
}
</script>

<style scoped>
.imagens-container {
  text-align: center;
  padding: 20px;
}

h1 {
  font-size: 36px;
  margin-bottom: 20px;
}

.gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.gallery-item {
  width: 150px;
  height: auto;
  margin: 10px;
  border: 2px solid #42b983;
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
}
</style>
