# Fornari Security — Acesso Seguro com Borda Animada

Interface de autenticação moderna e responsiva construída com HTML5 semântico, CSS3 e JavaScript Vanilla. Apresenta uma animação contínua de borda neon cônica, micro-interações para os campos e suporte completo a acessibilidade.

## 🌟 Funcionalidades e UI/UX

- **Animação de Borda em Alta Performance**: Utiliza a propriedade CSS `@property --angle` combinada a gradientes cônicos triplos para criar um efeito de rotação fluida a 60fps, sem recalcular layouts pesados (*layout jank*).
- **Aura Glow Futurista**: Efeito duplo de brilho desfocado (*ambient glow*) e painel interno fosco (*glassmorphism* com `backdrop-filter`).
- **Micro-interações Aprimoradas**:
  - **Floating Labels**: Os rótulos flutuam suavemente para o topo do campo ao focar ou preencher dados.
  - **Alternância de Senha**: Botão integrado para revelar ou ocultar o texto da senha.
  - **Botão com State Spinner**: Animação de carregamento acionada durante o envio do formulário.
- **Interatividade Universal**: O cartão expande via `:hover` no desktop, `:focus-within` ao navegar via teclado e clique direto para navegação em dispositivos sensíveis ao toque (mobile).
- **Acessibilidade WCAG 2.1 AA**: Suporte a `@media (prefers-reduced-motion)` para usuários sensíveis a movimento, atributos ARIA e foco visível customizado.

## 🛠️ Como Utilizar

1. Salve o código no arquivo `Fornari_Security.html`.
2. Abra-o em qualquer navegador moderno (Chrome, Edge, Firefox, Safari). Nenhuma dependência externa ou instalador de pacotes é necessário.
