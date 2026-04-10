<div align="center">
  <h2>🖥️ Visualização do Sistema</h2>
  <img src="https://github.com/user-attachments/assets/3127f784-6d83-4be5-ac3e-f0ee04cc0f52" alt="Print da interface interna do projeto" width="900">
  
  <p align="center">
    <em>Captura de tela da área interna, demonstrando o layout e as funcionalidades principais.</em>
  </p>
</div>


Dê vida aos seus cursos armazenados localmente. O NexusHub foi desenvolvido para superar as limitações de plataformas arcaicas que não oferecem acompanhamento visual. Com ele, você transforma seus arquivos offline em uma biblioteca organizada, gamificada e com um dashboard elegante para acompanhar sua evolução em tempo real.

**🎬 NexusHub — Biblioteca de Cursos Local**
Organize e assista seus cursos offline diretamente no navegador. Sem instalação, sem internet, sem login.

**✨ O que é o NexusHub?**
NexusHub é um player focados em cursos offline feito em HTML puro. Basta abrir o arquivo index.html no navegador e importar sua pasta de cursos — o sistema organiza tudo automaticamente, salva seu progresso e permite retomar de onde parou, sem depender de nenhum servidor ou conexão com a internet.

**🚀 Funcionalidades**
📁 Importação inteligente de pastas — detecta automaticamente se você está importando uma pasta mestre com vários cursos ou um único curso com módulos

🎯 Progresso salvo — o avanço de cada aula é guardado no localStorage do navegador e persiste entre sessões

📊 Dashboard visual — cards com barra de progresso, tempo total e aulas concluídas por curso

🎬 Player integrado — reproduz vídeos localmente com controles de anterior/próximo e marcação de aulas concluídas

📂 Playlist em árvore — navegue pelos módulos e aulas em uma sidebar com estrutura de pastas expansível

🔍 Filtros de biblioteca — filtre cursos por Todos, Não Iniciados, Em Andamento ou Concluídos

🖱️ Drag & Drop — arraste pastas diretamente para a janela do navegador

➕ Adicionar conteúdo — adicione novos cursos ou aulas a qualquer momento sem perder o progresso existente

🗑️ Remoção granular — remova cursos, módulos ou aulas individuais

💾 Zero dependências externas — funciona 100% offline após o primeiro carregamento


**📦 Como usar**
1. Baixe o projeto
bashgit clone https://github.com/matheuspereirafx/nexushub.git
Ou simplesmente baixe o arquivo index.html direto pelo GitHub.
2. Abra no navegador
Dê dois cliques no arquivo index.html — nenhuma instalação necessária.
3. Importe seus cursos
Arraste sua pasta de cursos para a janela, ou clique em "Selecionar Pasta de Cursos" e escolha a pasta.

**🗂️ Estrutura de pastas suportada**
O NexusHub detecta automaticamente dois formatos:
Pasta mestre com múltiplos cursos:

📁 Meus Cursos/

├── 📁 Curso de Python/

│   ├── 📁 Módulo 1/

│   │   ├── aula01.mp4

│   │   └── aula02.mp4

│   └── 📁 Módulo 2/

│       └── aula01.mp4
└── 📁 Curso de JavaScript/
    └── aula01.mp4
    
Pasta de curso único com módulos:
📁 Curso de Python/

├── 📁 Módulo 1 - Introdução/

│   ├── aula01.mp4

│   └── aula02.mp4

└── 📁 Módulo 2 - Variáveis/
    └── aula01.mp4
    
Formatos de vídeo suportados: .mp4, .mkv, .webm e demais formatos suportados pelo navegador.


**🧭 Navegação**
ÍconeFunção☰Biblioteca — todos os seus cursos▶Player — volta ao curso em reprodução＋Adicionar conteúdo👤Página do criador

**🛠️ Tecnologias**
Tecnologia Uso HTML5 Estrutura e APIs de arquivo (File API, webkitdirectory)CSS3 Estilização, animações e layout (@keyframes, gradient, transition)JavaScript (ES6+)Lógica de negócio, detecção de pastas, árvore de playlistTailwind CSS (CDN)Classes utilitárias de apoioGoogle FontsTipografia (Syne + Inter)localStoragePersistência do progresso sem backend

**💡 Como o progresso é salvo?**
O NexusHub usa o localStorage do navegador para guardar:

Quais aulas foram marcadas como concluídas
A duração de cada vídeo
O índice da última aula assistida por curso

Os dados ficam salvos por navegador e por máquina. Se você usar em outro computador, o progresso não é sincronizado (é totalmente local).

**⚠️ Limitações conhecidas**

Funciona apenas em navegadores modernos baseados em Chromium (Chrome, Edge, Brave) que suportam webkitdirectory
O progresso é salvo por navegador — não há sincronização entre dispositivos
Não suporta streaming ou arquivos remotos — apenas arquivos locais

**🤝 Contribuindo**
Contribuições são bem-vindas! Sinta-se à vontade para:

Fazer um fork do projeto
Criar uma branch para sua feature (git checkout -b feature/minha-feature)
Fazer o commit das alterações (git commit -m 'feat: adiciona minha feature')
Fazer o push para a branch (git push origin feature/minha-feature)
Abrir um Pull Request

👤 Autor
Matheus Pereira

<p>Feito com ♥ para quem estuda offline</p>

