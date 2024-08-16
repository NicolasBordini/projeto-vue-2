<template>
  <div class="hello">
    <bemvindo>Bem-vindo ao meu Primeiro Projeto Front-End - Desenvolvimento Responsivo</bemvindo>
    <h1>OVOS DE PÁSCOA CACAU SHOW</h1>
    <h2>Edição 2024</h2>

    <div class="image-container">
      <img src="@/assets/cacaulogo.png" alt="Logo Cacau Show" style="width: 100%; border: 2px solid #42b983;">
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
          <td><img src="@/assets/leite.png" class="imgTabela" alt="Chocolate ao Leite Ovo"></td>
        </tr>
        <tr>
          <td>Morango</td>
          <td>250g</td>
          <td>R$49,90</td>
          <td><img src="@/assets/morango.png" class="imgTabela" alt="Morango Ovo"></td>
        </tr>
        <tr>
          <td>Castanha do Pará</td>
          <td>170g</td>
          <td>R$39,90</td>
          <td><img src="@/assets/castanha.png" class="imgTabela" alt="Castanha do Pará Ovo"></td>
        </tr>
        <tr>
          <td>Ninho</td>
          <td>300g</td>
          <td>R$55,90</td>
          <td><img src="@/assets/ninho.png" class="imgTabela" alt="Ninho Ovo"></td>
        </tr>
        <tr>
          <td>Trufado</td>
          <td>220g</td>
          <td>R$45,90</td>
          <td><img src="@/assets/trufado.png" class="imgTabela" alt="Trufado Ovo"></td>
        </tr>
        <tr>
          <td>Caramelo Salgado</td>
          <td>180g</td>
          <td>R$37,90</td>
          <td><img src="@/assets/caramelo.png" class="imgTabela" alt="Caramelo Salgado Ovo"></td>
        </tr>
      </tbody>
    </table>

    <iframe src="https://www.youtube.com/embed/QZWg_n1YAts?si=E5LwDNgLX3yOTMDO" width="100%" height="400px" frameborder="0" allowfullscreen></iframe>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped>
.bemvindo {
  color: #42b983;
  font-size: 24px;
  margin-bottom: 10px;
}

h1 {
  font-size: 36px;
}

h2 {
  font-size: 24px;
}

.image-container {
  text-align: center;
  margin-bottom: 20px;
}

.custom-table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 20px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.custom-table th, .custom-table td {
  border: 1px solid #ddd;
  padding: 10px;
  text-align: center;
}

.custom-table th {
  background-color: #f2f2f2;
}

.imgTabela {
  height: 80px;
  width: auto;
}

iframe {
  margin-top: 20px;
}
</style>
