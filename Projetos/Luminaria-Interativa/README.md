# 💡 Login com Luminária Interativa
 
Tela de login em **um único arquivo HTML**. O formulário fica escondido no escuro: puxe a corrente da luminária, a luz acende e o cartão de acesso aparece. 🔦
 
## 🚀 Como usar
 
1. Abra o arquivo `login-luminaria.html` no navegador.
2. Acenda a luz de um destes jeitos:
   - 🖱️ arraste a corrente para baixo;
   - 👆 clique ou toque na argola;
   - ⌨️ use `Tab` para focar a corrente e aperte `Enter` ou `Espaço`.
3. Puxe de novo para **apagar a luz** e esconder o login. 🌙
4. Preencha e-mail (ou usuário) e senha com **6 caracteres ou mais**.
> ⚠️ É uma **demonstração**: nenhum dado é enviado e o login é simulado.
 
## ✨ O que tem
 
| | Recurso |
|---|---|
| 🪔 | Luminária articulada em SVG, preta com juntas em latão |
| 🔆 | Feixe de luz que sai da cúpula e ilumina o cartão de login |
| 🔗 | Corrente com mola e efeito sonoro de clique |
| 📄 | Cartão de papel com campos sublinhados e validação em português |
| 🔑 | Janela "Esqueci a senha" com `<dialog>` nativo |
| ⏸️ | Botão **Pausar efeitos** e suporte a `prefers-reduced-motion` |
 
## ♿ Acessibilidade
 
- ✅ Navegação completa por teclado e foco sempre visível
- ✅ Erros descritos em texto, com foco no primeiro campo inválido
- ✅ Alvos de toque de pelo menos 44 px
- ✅ Contraste mínimo de 4,5:1 nos textos
## 🛠️ Tecnologias
 
HTML, CSS e JavaScript puros, sem dependências. As fontes (Young Serif e Instrument Sans) vêm do Google Fonts, com alternativas do sistema.
 
## 🔜 Próximo passo
 
Trocar o login simulado por uma chamada real à sua API no evento `submit` do formulário. 🔌
 
