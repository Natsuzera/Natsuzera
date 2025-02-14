<html>
  <head>
    <meta charset="UTF-8">
    <title>GitHub Profile README - Daniel Moura do Nascimento</title>
    <style>
      /* Estilos Globais */
      body {
        margin: 0;
        padding: 0;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        background-color: #f4f4f4;
        color: #333;
      }
      .container {
        max-width: 1000px;
        margin: 0 auto;
        padding: 20px;
      }
      /* Cabeçalho animado com GIF */
      .header-animation {
        display: block;
        width: 100%;
        height: 150px;
      }
      /* Header principal (conteúdo) */
      .header {
        text-align: center;
        margin-top: -30px; /* sobreposição sutil com o header animado */
      }
      .animated-title {
        margin: 20px 0;
      }
      .badges a {
        margin: 0 5px;
      }
      /* Seções */
      .section {
        background: #fff;
        border-radius: 10px;
        padding: 20px;
        margin: 20px 0;
        box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      }
      .section h2 {
        color: #0B3A78;
        border-bottom: 2px solid #0B3A78;
        padding-bottom: 10px;
      }
      /* Tecnologias */
      .tech-badges {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 10px;
        margin-top: 10px;
      }
      .tech-badges img {
        transition: transform 0.3s;
      }
      .tech-badges img:hover {
        transform: scale(1.1);
      }
      /* Projetos */
      .projects-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 20px;
      }
      .project {
        background: #eaeaea;
        border-radius: 10px;
        padding: 15px;
      }
      .project h3 {
        margin: 0;
        color: #0B3A78;
      }
      .project h4 {
        margin: 5px 0;
        color: #555;
      }
      .project p {
        margin: 10px 0;
      }
      .project-tech-badges {
        display: flex;
        gap: 8px;
        flex-wrap: wrap;
      }
      /* GitHub Stats lado a lado */
      .stats-container {
        display: flex;
        justify-content: center;
        gap: 20px;
        flex-wrap: wrap;
      }
      .stats-container img {
        max-width: 48%;
        min-width: 300px;
      }
      /* Seção de Contato */
      .contact {
        text-align: center;
      }
      .contact .contact-icons {
        display: flex;
        justify-content: center;
        gap: 15px;
        flex-wrap: wrap;
        margin-top: 15px;
      }
    </style>
  </head>
  <body>
    <!-- Cabeçalho animado: substituído o canvas pelo GIF animado -->
    <img class="header-animation" src="output.gif" alt="Animated Header">
    
    <div class="container">
      <!-- Header principal -->
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
      
      <!-- Sobre Mim -->
      <div class="section about">
        <h2>🚀 Sobre Mim</h2>
        <p>
          Sou um cientista de dados apaixonado por Machine Learning, Deep Learning e soluções IoT. Atualmente, exploro o universo da Inteligência Artificial,
          combinando algoritmos inovadores e ferramentas modernas para transformar dados em soluções que impactam positivamente a sociedade.
        </p>
      </div>
      
      <!-- Tecnologias e Ferramentas -->
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
      
      <!-- Projetos -->
      <div class="section projects">
        <h2>Projetos</h2>
        <div class="projects-grid">
          <!-- Projeto 1 -->
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
          <!-- Projeto 2 -->
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
      
      <!-- GitHub Stats (lado a lado) -->
      <div class="section github-stats">
        <h2>📊 GitHub Stats</h2>
        <div class="stats-container">
          <img src="https://github-readme-stats.vercel.app/api?username=Natsuzera&show_icons=true&theme=graywhite" alt="GitHub Stats">
          <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Natsuzera&layout=compact&theme=graywhite" alt="Top Languages">
        </div>
      </div>
      
      <!-- Seção de Contato -->
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
