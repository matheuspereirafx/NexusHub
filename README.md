<div align="center">
  <img src="https://github.com/user-attachments/assets/3127f784-6d83-4be5-ac3e-f0ee04cc0f52" alt="NexusHub Banner" width="100%">

  # 🎬 NexusHub — Biblioteca de Cursos Local
  
  **Dê vida aos seus cursos offline com uma biblioteca organizada, gamificada e elegante.**

  [![GitHub license](https://img.shields.io/github/license/matheuspereirafx/nexushub?style=for-the-badge&color=blue)](https://github.com/matheuspereirafx/nexushub)
  [![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
  [![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
  [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

  <p align="center">
    <a href="#-o-que-é">O que é</a> •
    <a href="#-funcionalidades">Funcionalidades</a> •
    <a href="#-tecnologias">Tecnologias</a> •
    <a href="#-como-usar">Como usar</a> •
    <a href="#-autor">Autor</a>
  </p>
</div>

---

## ✨ O que é o NexusHub?
O **NexusHub** foi desenvolvido para superar as limitações de plataformas arcaicas que não oferecem acompanhamento visual. É um player focado em cursos offline feito em **HTML puro**, focado em **UI/UX**.

Com ele, você transforma seus arquivos locais em uma interface moderna. Basta abrir o arquivo `index.html` no navegador e importar sua pasta — o sistema organiza tudo automaticamente, salva seu progresso e permite retomar de onde parou, **sem depender de servidor ou internet**.

---

## 🚀 Funcionalidades

| Recurso | Descrição |
| :--- | :--- |
| 📁 **Importação Inteligente** | Detecta automaticamente pastas mestres ou cursos únicos com módulos. |
| 🎯 **Progresso Salvo** | O avanço é guardado no `localStorage` e persiste entre sessões. |
| 📊 **Dashboard Visual** | Cards com barra de progresso, tempo total e aulas concluídas. |
| 🎬 **Player Integrado** | Playlist em árvore com navegação fluída e marcação de aulas. |
| 🔍 **Filtros de Biblioteca** | Organize por: *Todos*, *Não Iniciados*, *Em Andamento* ou *Concluídos*. |
| 🖱️ **Drag & Drop** | Arraste pastas diretamente para a janela para adicionar conteúdo. |
| 💾 **Zero Dependências** | Funciona 100% offline após o primeiro carregamento. |

---

## 🛠️ Tecnologias

O projeto utiliza uma stack focada em independência e performance:

* **HTML5:** Estrutura e APIs de arquivo (`File API`, `webkitdirectory`).
* **CSS3 & Tailwind CSS:** Estilização moderna e layout responsivo via CDN.
* **JavaScript (ES6+):** Lógica de detecção de pastas e persistência de dados.
* **Google Fonts:** Tipografia selecionada (Syne + Inter).
* **localStorage:** Banco de dados local para salvar seu progresso.

---

## 🗂️ Estrutura de Pastas Suportada

O sistema reconhece automaticamente estas hierarquias:

### 1. Pasta Mestre (Múltiplos Cursos)
```text
📁 Meus Cursos/
├── 📁 Curso de Python/
│   ├── 📁 Módulo 1/
│   │   ├── aula01.mp4
│   │   └── aula02.mp4
│   └── 📁 Módulo 2/
└── 📁 Curso de JavaScript/
```

### 2. Curso Único
```text
📁 Curso de React/
├── 📁 01 - Introdução/
│   ├── aula01.mp4
└── 📁 02 - Hooks/
```

---

## 📦 Como usar

1. **Baixe o projeto:**
   ```bash
   git clone [https://github.com/matheuspereirafx/nexushub.git](https://github.com/matheuspereirafx/nexushub.git)
   ```

2. **Abra no navegador:**
   Dê dois cliques no arquivo `index.html`. Nenhuma instalação ou servidor é necessário.

3. **Importe seus cursos:**
   Arraste sua pasta de cursos para a janela, ou clique em **"Selecionar Pasta de Cursos"** e escolha a pasta desejada.

---

## 💡 Informações Importantes

* **Persistência:** O progresso é salvo por navegador. Se você limpar o cache ou trocar de computador, o progresso local não será mantido por ser uma aplicação 100% local.
* **Navegadores:** Recomendado o uso em navegadores baseados em **Chromium** (Chrome, Edge, Brave) para suporte total à API de leitura de diretórios.

---

## 🤝 Contribuindo

Sinta-se à vontade para colaborar:
* 🍴 Faça um **Fork** do projeto.
* 🌿 Crie uma **Branch** para sua feature (`git checkout -b feature/minha-feature`).
* 💾 Faça o **Commit** das alterações (`git commit -m 'feat: minha nova feature'`).
* 🚀 Faça o **Push** para a sua Branch (`git push origin feature/minha-feature`).
* 🔃 Abra um **Pull Request**.

---

<div align="center">
  <p>Desenvolvido com ♥ por <a href="https://github.com/matheuspereirafx">Matheus Pereira</a></p>
  
  <p>
    <a href="https://github.com/matheuspereirafx">
      <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
  </p>
</div>
