<template>
  <div class="container">
    <header class="header">
      <h1>OVOS DE PÁSCOA CACAU SHOW</h1>
      <h2>Edição 2024</h2>
    </header>

    <div class="image-container">
      <img src="@/assets/cacaulogo.png" alt="Logo Cacau Show" class="logo">
    </div>

    <table class="custom-table">
      <thead>
        <tr>
          <th>Sabor</th>
          <th>Peso</th>
          <th>Preço</th>
          <th>Imagem</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Chocolate ao Leite</td>
          <td>350g</td>
          <td>R$59,90</td>
          <td><img src="@/assets/leite.png" class="img-tabela" alt="Chocolate ao Leite Ovo"></td>
        </tr>
        <tr>
          <td>Morango</td>
          <td>250g</td>
          <td>R$49,90</td>
          <td><img src="@/assets/morango.png" class="img-tabela" alt="Morango Ovo"></td>
        </tr>
        <tr>
          <td>Castanha do Pará</td>
          <td>170g</td>
          <td>R$39,90</td>
          <td><img src="@/assets/castanha.png" class="img-tabela" alt="Castanha do Pará Ovo"></td>
        </tr>
        <tr>
          <td>Ninho</td>
          <td>300g</td>
          <td>R$55,90</td>
          <td><img src="@/assets/ninho.png" class="img-tabela" alt="Ninho Ovo"></td>
        </tr>
        <tr>
          <td>Trufado</td>
          <td>220g</td>
          <td>R$45,90</td>
          <td><img src="@/assets/trufado.png" class="img-tabela" alt="Trufado Ovo"></td>
        </tr>
        <tr>
          <td>Caramelo Salgado</td>
          <td>180g</td>
          <td>R$37,90</td>
          <td><img src="@/assets/caramelo.png" class="img-tabela" alt="Caramelo Salgado Ovo"></td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
export default {
  name: 'TabelaDiversos'
}
</script>

<style scoped>
.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

.header {
  text-align: center;
  margin-bottom: 40px;
}

.header h1 {
  font-size: 40px;
  color: #42b983;
  margin-bottom: 10px;
}

.header h2 {
  font-size: 28px;
  color: #333;
}

.logo {
  width: 100%;
  max-width: 400px;
  margin: 0 auto;
  border: 2px solid #42b983;
  border-radius: 8px;
}

.custom-table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 20px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.custom-table th, .custom-table td {
  border: 1px solid #ddd;
  padding: 12px;
  text-align: center;
}

.custom-table th {
  background-color: #42b983;
  color: #fff;
  font-weight: bold;
}

.custom-table tr:nth-child(even) {
  background-color: #f9f9f9;
}

.img-tabela {
  height: 100px;
  width: auto;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}
</style>
