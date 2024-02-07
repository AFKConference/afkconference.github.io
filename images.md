# 0x03 - Imagens

# Fotos relacionadas à conferência:
<div style="width:100%;text-align:center;">
<img src="/assets/logo.jpg" alt="logo" style="height: 200px; width:200px;"/> <img src="/assets/afk.jpeg" alt="logo" style="height: 200px; width:200px;"/>
<img src="/assets/01.jpeg" alt="01" style="height: 200px; width:200px;"/> <img src="/assets/02.jpeg" alt="02" style="height: 200px; width:200px;"/>
<img src="/assets/03.jpeg" alt="03" style="height: 200px; width:200px;"/> <img src="/assets/04.jpeg" alt="04" style="height: 200px; width:200px;"/>
<img src="/assets/05.jpeg" alt="05" style="height: 200px; width:200px;"/> <img src="/assets/06.jpeg" alt="06" style="height: 200px; width:200px;"/>
<img src="/assets/07.jpeg" alt="07" style="height: 200px; width:200px;"/>

<script>
  window.onload = function() {
    const imageContainer = document.getElementById('imageContainer');
    
    // Diretório onde as imagens estão localizadas
    const directory = "/assets/2022/";
    
    // Número total de imagens no diretório
    const totalImages = 3; // Defina o número total de imagens
    
    // Exibir cada imagem
    for (let i = 1; i <= totalImages; i++) {
      const img = document.createElement('img');
      img.src = directory + i + ".jpg"; // Caminho para cada imagem
      img.alt = "Image " + i;
      imageContainer.appendChild(img);
    }
  }
</script>
</div>
