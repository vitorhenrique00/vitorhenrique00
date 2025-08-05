## 🧑‍💻 Vitor henrique
      
       

Me chamo Vitor Henrique, tenho 23 anos e sou natural de São Paulo. Concluí o ensino médio, sou formado em Criminologia. Atualmente, estou cursando Análise e Desenvolvimento de Sistemas na Unifran. Sou apaixonada por tecnologia, sou iniciante na aréa de TI espero adquirir novos conhecimentos e passar adiante futuramente.
    
<a href="https://github.com/vitorhenrique00?tab=followers">
    <img 
        alt="Seguidores" 
        title="Me siga no GitHub" 
        src="https://custom-icon-badges.demolab.com/github/followers/vitorhenrique00?color=236ad3&labelColor=1155ba&style=for-the-badge&logo=github&label=Seguidores&logoColor=white" 
    />
</a>
<a href="https://www.linkedin.com/in/vitor-henrique-290905286/" target="_blank">
  <img 
    src="https://img.shields.io/badge/LinkedIn-Vitor%20Henrique-blue?style=for-the-badge&logo=linkedin&logoColor=white" 
    alt="LinkedIn - Vitor Henrique"
  />
</a>
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Botão Discord</title>
</head>
<body>

<!-- Botão com ícone e texto -->
<button id="discordBtn" style="border:none; background:none; cursor:pointer; display: flex; align-items: center; font-family: Arial, sans-serif; font-size: 16px;">
  <img src="https://cdn-icons-png.flaticon.com/512/2111/2111370.png" alt="Discord" width="30" height="30" style="margin-right: 8px;">
  Meu Discord
</button>

<!-- Script que faz a cópia -->
<script>
  document.getElementById('discordBtn').addEventListener('click', function() {
    const discordUsername = "rifa1337";

    // Verifica se a API está disponível
    if (navigator.clipboard) {
      navigator.clipboard.writeText(discordUsername)
        .then(() => alert("Usuário do Discord copiado: " + discordUsername))
        .catch(err => alert("Erro ao copiar. Tente novamente."));
    } else {
      // Fallback para navegadores mais antigos
      const tempInput = document.createElement("input");
      tempInput.value = discordUsername;
      document.body.appendChild(tempInput);
      tempInput.select();
      try {
        document.execCommand("copy");
        alert("Usuário do Discord copiado: " + discordUsername);
      } catch (err) {
        alert("Erro ao copiar. Tente novamente.");
      }
      document.body.removeChild(tempInput);
    }
  });
</script>

</body>
</html>



📈 Estatísticas de Contribuição

![Contribuições do GitHub](https://github-readme-stats.vercel.app/api?username=vitorhenrique00&show_icons=true)
 


