# Painel de Foco - Módulo de Gestão de Prioridades

Um componente web minimalista e acessível desenvolvido em HTML5, CSS3 puro e JavaScript vanilla (ES6+), projetado com foco em desempenho, acessibilidade (WCAG 2.1 AA) e arquitetura modular.

## 🚀 Funcionalidades

- **Gerenciamento de Metas**: Adição, conclusão e remoção de tarefas em tempo real.
- **Interface Minimalista Dark Mode**: Tokens CSS centralizados para fácil personalização de temas.
- **Acessibilidade Nativa**:
  - Suporte completo a navegabilidade por teclado (`Tab`, `Space`, `Enter`).
  - Anúncios dinâmicos para leitores de tela via regiões `aria-live`.
  - Animações desativadas automaticamente se `prefers-reduced-motion` estiver ativo.
- **Micro-cópia Guiada (UX Copy)**: Rótulos e estados vazios diretos e informativos.

## 🛠️ Arquitetura e Engenharia

O projeto adota o padrão **Module Pattern** com renderização reativa baseada em estado (**State-Driven Rendering**):

1. **Gestão de Estado**: O estado das metas é mantido em uma estrutura imutável de memória (`state`) isolada do DOM.
2. **Delegação de Eventos**: Utiliza um único ouvinte de eventos na lista pai (`#taskList`) para capturar alterações e exclusões, reduzindo o uso de memória.
3. **Segurança (XSS)**: Sanitização automática de strings inseridas pelo usuário antes da renderização no DOM.

## 💻 Como Executar

1. Baixe o arquivo `index.html`.
2. Abra-o em qualquer navegador moderno. Não requer dependências externas ou transpilação.
