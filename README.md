<html>
  <head>
    <meta charset="UTF-8">
    <title>GitHub Profile README - Daniel Moura do Nascimento</title>
    <style>
      /* Estilos Globais */
      body {
        margin: 0;
        padding: 0;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; /* Mantendo a fonte original */
        background-color: #f4f4f4; /* Cor de fundo levemente acinzentada */
        color: #333; /* Cor do texto principal mais escura */
        line-height: 1.6; /* Aumentando o espaçamento entre linhas para melhor leitura */
      }
      .container {
        max-width: 1000px; /* Largura máxima para o conteúdo */
        margin: 20px auto; /* Margem superior e inferior e centralização horizontal */
        padding: 20px; /* Espaçamento interno dentro do container */
        background-color: #fff; /* Fundo branco para o container principal */
        border-radius: 10px; /* Bordas arredondadas para o container */
        box-shadow: 0 0 10px rgba(0,0,0,0.1); /* Sombra suave para destacar o container */
      }
      /* Cabeçalho animado com GIF */
      .header-animation {
        display: block;
        width: 100%;
        max-height: 150px; /* Altura máxima para o header animado, ajustando para max-height */
        object-fit: cover; /* Garante que o GIF cubra o espaço sem distorcer */
        border-radius: 10px 10px 0 0; /* Arredonda apenas as bordas superiores do GIF */
      }
      /* Header principal (conteúdo) */
      .header {
        text-align: center;
        margin-top: 10px; /* Reduzindo a sobreposição e alinhando melhor */
        padding: 20px 0; /* Adicionando padding vertical */
      }
      .animated-title {
        margin: 10px 0 20px; /* Ajustando as margens do título animado */
      }
      .badges a {
        margin: 0 5px;
        display: inline-block; /* Melhora o alinhamento dos badges */
        transform: translateY(-3px); /* Pequeno ajuste vertical para alinhar com o título */
      }
      /* Seções */
      .section {
        background: #fff;
        border-radius: 10px;
        padding: 25px; /* Aumentando o padding interno das seções */
        margin: 25px 0; /* Aumentando a margem vertical das seções */
        box-shadow: 0 2px 7px rgba(0,0,0,0.08); /* Sombra mais suave e leve */
        border: 1px solid #eee; /* Adicionando uma borda sutil */
      }
      .section h2 {
        color: #0B3A78;
        border-bottom: 3px solid #0B3A78; /* Aumentando a espessura da linha inferior do título */
        padding-bottom: 12px; /* Aumentando o padding inferior do título */
        margin-bottom: 20px; /* Aumentando a margem inferior do título */
        font-size: 2em; /* Aumentando o tamanho da fonte do título da seção */
      }
      /* Tecnologias */
      .tech-badges {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 12px; /* Aumentando o espaçamento entre os badges de tecnologia */
        margin-top: 15px; /* Aumentando a margem superior */
      }
      .tech-badges img {
        transition: transform 0.3s;
        border-radius: 5px; /* Arredondando os badges de tecnologia */
      }
      .tech-badges img:hover {
        transform: scale(1.1);
      }
      /* Projetos */
      .projects-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); /* Ajustando o tamanho mínimo dos projetos */
        gap: 25px; /* Aumentando o espaçamento na grade de projetos */
      }
      .project {
        background: #f9f9f9; /* Cor de fundo mais clara para os projetos */
        border-radius: 12px; /* Arredondando mais as bordas dos projetos */
        padding: 20px;
        border: 1px solid #eee; /* Adicionando uma borda sutil aos projetos */
        transition: all 0.3s ease; /* Transição suave para hover */
      }
      .project:hover {
        box-shadow: 0 5px 15px rgba(0,0,0,0.15); /* Sombra mais pronunciada no hover */
        transform: translateY(-3px); /* Pequeno efeito de elevação no hover */
      }
      .project h3 {
        margin: 0 0 10px; /* Adicionando margem inferior ao título do projeto */
        color: #0B3A78;
        font-size: 1.5em; /* Aumentando o tamanho da fonte do título do projeto */
      }
      .project h4 {
        margin: 8px 0;
        color: #777; /* Cor do subtítulo do projeto levemente mais clara */
        font-weight: 500; /* Diminuindo a espessura da fonte do subtítulo */
      }
      .project p {
        margin: 15px 0;
        color: #555;
      }
      .project-tech-badges {
        display: flex;
        gap: 10px;
        flex-wrap: wrap;
        margin-top: 15px;
      }
      /* GitHub Stats lado a lado */
      .stats-container {
        display: flex;
        justify-content: space-around; /* Espaçamento igual entre os stats */
        gap: 25px; /* Aumentando o espaçamento entre os containers de stats */
        flex-wrap: wrap;
        margin-top: 20px;
      }
      .stats-container img {
        max-width: 100%; /* Imagens de stats ocupam 100% do container pai */
        height: auto; /* Altura automática para manter a proporção */
        border-radius: 8px; /* Arredondando as bordas das imagens de stats */
        box-shadow: 0 2px 5px rgba(0,0,0,0.05); /* Adicionando uma sombra leve às imagens de stats */
      }
      /* Seção de Contato */
      .contact {
        text-align: center;
        padding: 30px 0; /* Aumentando o padding vertical da seção de contato */
      }
      .contact h2 {
        margin-bottom: 30px; /* Aumentando a margem inferior do título de contato */
      }
      .contact .contact-icons {
        display: flex;
        justify-content: center;
        gap: 20px; /* Aumentando o espaçamento entre os ícones de contato */
        flex-wrap: wrap;
        margin-top: 20px;
      }
      .contact .contact-icons img {
        transform: scale(1.1); /* Ícones de contato ligeiramente maiores */
      }
    </style>
  </head>
  <body>
        <img class="header-animation" src="https://raw.githubusercontent.com/seu-usuario/seu-repositorio/main/output.gif" alt="Animated Header">
    
    <div class="container">
            <div class="header">
        <div class="animated-title">
          <img src="https://readme-typing-svg.demolab.com?font=Operator+Mono&size=48&duration=2800&pause=2000&color=0B3A78&center=true&vCenter=true&width=940&height=50&lines=Daniel+Moura+do+Nascimento;Cientista+de+Dados;Explorando+a+IA" alt="Animated Title">
        </div>
        <div class="badges" style="margin-bottom:20px;">
          <a href="https://github.com/Natsuzera">
            <img src="https://img.shields.io/badge/-PORTFÓLIO-0B3A78?style=for-the-badge&logo=github&logoColor=white" alt="Portfolio">
          </a>
          <a href="mailto:daniel_7799@live.com">
            <img src="https://img.shields.io/badge/-EMAIL-0B3A78?style=for-the-badge&logo=microsoft-outlook&logoColor=white" alt="Email">
          </a>
        </div>
      </div>
      
            <div class="section about">
        <h2>🚀 Sobre Mim</h2>
        <p>
          Sou um cientista de dados apaixonado por Machine Learning, Deep Learning e soluções IoT. Atualmente, exploro o universo da Inteligência Artificial,
          combinando algoritmos inovadores e ferramentas modernas para transformar dados em soluções que impactam positivamente a sociedade.
        </p>
      </div>
      
            <div class="section tech">
        <h2>🖥️ Tecnologias e Ferramentas</h2>
        <div class="tech-badges">
          <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
          <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow">
          <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch">
          <img src="https://img.shields.io/badge/SciKit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="SciKit-Learn">
          <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
          <img src="https://img.shields.io/badge/YOLO-FF5733?style=for-the-badge&logo=opencv&logoColor=white" alt="YOLO">
          <img src="https://img.shields.io/badge/Ollama-5B2C6F?style=for-the-badge&logo=appveyor&logoColor=white" alt="Ollama">
          <img src="https://img.shields.io/badge/HuggingFace-05A4D8?style=for-the-badge&logo=huggingface&logoColor=white" alt="HuggingFace">
          <img src="https://img.shields.io/badge/Transformers-007ACC?style=for-the-badge&logo=huggingface&logoColor=white" alt="Transformers">
          <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV">
          <img src="https://img.shields.io/badge/C++-0B3A78?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++">
          <img src="https://img.shields.io/badge/C-0B3A78?style=for-the-badge&logo=c&logoColor=white" alt="C">
          <img src="https://img.shields.io/badge/Arduino-0B3A78?style=for-the-badge&logo=arduino&logoColor=white" alt="Arduino">
          <img src="https://img.shields.io/badge/ESP32-0B3A78?style=for-the-badge&logo=espressif&logoColor=white" alt="ESP32">
          <img src="https://img.shields.io/badge/IoT-0B3A78?style=for-the-badge&logo=internetofthings&logoColor=white" alt="IoT">
        </div>
      </div>
      
            <div class="section projects">
        <h2>Projetos</h2>
        <div class="projects-grid">
                    <div class="project">
            <h3>🔍 Projeto Destaque</h3>
            <h4>DriveBehaviour</h4>
            <p>
              Sistema de análise de comportamento de direção utilizando Random Forest, KMeans e PCA com 92% de acurácia.
              Desenvolvido com Python e SciKit-Learn.
            </p>
            <div class="project-tech-badges">
              <img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python" alt="Python">
              <img src="https://img.shields.io/badge/-Machine_Learning-FF6F00?style=flat-square&logo=tensorflow" alt="Machine Learning">
            </div>
          </div>
                    <div class="project">
            <h3>🤖 Impacto Social</h3>
            <h4>Um Robô Por Aluno</h4>
            <p>
              Iniciativa educacional para ensino de robótica e IoT em escolas públicas, promovendo inclusão digital e soluções práticas para problemas reais.
            </p>
            <div class="project-tech-badges">
              <img src="https://img.shields.io/badge/-Arduino-0B3A78?style=flat-square&logo=arduino" alt="Arduino">
              <img src="https://img.shields.io/badge/-IoT-0B3A78?style=flat-square&logo=internetofthings&logoColor=white" alt="IoT">
            </div>
          </div>
        </div>
      </div>
      
            <div class="section github-stats">
        <h2>📊 GitHub Stats</h2>
        <div class="stats-container">
          <img src="https://github-readme-stats.vercel.app/api?username=Natsuzera&show_icons=true&theme=graywhite" alt="GitHub Stats">
          <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Natsuzera&layout=compact&theme=graywhite" alt="Top Languages">
        </div>
      </div>
      
            <div class="section contact">
        <h2>⤵️ Onde Me Encontrar</h2>
        <div class="contact-icons">
          <a href="mailto:daniel_7799@live.com">
            <img src="https://img.shields.io/badge/Gmail-0B3A78?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
          </a>
          <a href="https://www.linkedin.com/in/danielmouranasc">
            <img src="https://img.shields.io/badge/LinkedIn-0B3A78?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
          </a>
          <a href="https://github.com/Natsuzera">
            <img src="https://img.shields.io/badge/GitHub-0B3A78?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
          </a>
        </div>
      </div>
    </div>
  </body>
</html>
