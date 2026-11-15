<h1 align="center">
  <br>
  🔗 Link Hub
</h1>

<p align="center">
  Um agregador de links moderno, interativo e totalmente responsivo para centralizar perfis profissionais, projetos e redes sociais.
</p>

<p align="center">
  <a href="https://samlcss.github.io/link-hub/">
    <img src="https://img.shields.io/badge/Demo-Deploy%20no%20GitHub%20Pages-brightgreen?style=for-the-badge&logo=githubpages" alt="Demonstração no GitHub Pages" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Responsive-Design-blueviolet?style=for-the-badge" alt="Design Responsivo" />
</p>

<div align="center">

| Modo Dark | Modo Light |
| :---: | :---: |
| <img src="./assets/avatar.png" width="90" alt="Avatar Dark" /><br><sub>Fundo Escuro & Estrelas</sub> | <img src="./assets/avatar-light.png" width="90" alt="Avatar Light" /><br><sub>Fundo Claro & Sol</sub> |

</div>

---

## 📌 Sobre o Projeto

O **Link Hub** funciona como um cartão de visitas digital ou página de links (estilo *Linktree*), permitindo que desenvolvedores e criadores compartilhem seus principais projetos, repositórios e canais de contato em um único lugar.

O projeto foi construído com foco em **boas práticas de front-end**, design responsivo e experiência do usuário (UX), incluindo uma transição suave entre temas claro e escuro.

> 🚀 **Acesse o projeto online:** [samlcss.github.io/link-hub](https://samlcss.github.io/link-hub/)

---

## ✨ Funcionalidades

- 🌓 **Dark / Light Mode**:
  - Interruptor (*switch*) interativo com animação fluida de transição.
  - Troca dinâmica do avatar e ícone do switch (lua / sol).
  - Troca automática das imagens de fundo conforme o tema ativo.
- 📱 **Totalmente Responsivo**:
  - Estrutura construída no conceito *Mobile-First*.
  - *Media Queries* adaptando o layout e a imagem de fundo para telas desktop a partir de `700px`.
- 🎨 **Estilização Moderna**:
  - Paleta baseada em variáveis CSS (`:root` e `.light`).
  - Efeito *Glassmorphism* com `backdrop-filter: blur(4px)`.
  - Animações CSS com `@keyframes` e efeitos de *hover*.
- 🔗 **Links & Redes Sociais**:
  - Acesso direto a projetos destacados (como *Snake Game* e *CRUD APIRest Java*).
  - Ícones vetoriais modernos importados via **Ionicons**.

---

## 🛠️ Tecnologias Utilizadas

- **[HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML)**: Marcação semântica e acessível.
- **[CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS)**:
  - Variáveis Customizadas (*CSS Custom Properties*)
  - Flexbox para alinhamentos
  - Media Queries para responsividade
  - Keyframes para animação do botão switch
- **[JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)**: Lógica de alternância de classes no elemento raiz (`html.classList.toggle`) e troca de imagem do perfil.
- **[Google Fonts (Inter)](https://fonts.google.com/specimen/Inter)**: Tipografia limpa e moderna.
- **[Ionicons](https://ionic.io/ionicons)**: Pacote de ícones para redes sociais.

---

## 📁 Estrutura de Arquivos

```text
link-hub/
├── assets/
│   ├── avatar.png              # Foto de perfil (tema escuro)
│   ├── avatar-light.png        # Foto de perfil (tema claro)
│   ├── bg-mobile.jpg           # Fundo mobile escuro
│   ├── bg-mobile-light.jpg     # Fundo mobile claro
│   ├── bg-desktop.jpg          # Fundo desktop escuro
│   ├── bg-desktop-light.jpg    # Fundo desktop claro
│   ├── moon-stars.svg          # Ícone de lua do interruptor
│   └── sun.svg                 # Ícone de sol do interruptor
├── index.html                  # Estrutura HTML principal
├── style.css                   # Folha de estilos e variáveis CSS
├── script.js                   # Lógica JS do toggle de tema
└── README.md                   # Documentação do projeto
```

---

## 💻 Como Executar Localmente

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/samlcss/link-hub.git
   ```

2. **Acesse a pasta do projeto:**
   ```bash
   cd link-hub
   ```

3. **Abra o projeto:**
   * Basta abrir o arquivo `index.html` em qualquer navegador; ou
   * Utilize a extensão **Live Server** no VS Code / Antigravity IDE para visualizar com recarregamento automático.

---

## 👤 Autor

Desenvolvido por **Samuel Colpaert**.

* GitHub: [@samlcss](https://github.com/samlcss)
* Instagram: [@samlcss](https://instagram.com/samlcss)

---

<p align="center">
  Projeto desenvolvido para fins de aprendizado e portfólio.
</p>
