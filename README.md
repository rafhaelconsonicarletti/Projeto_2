# Projeto Esperança — Entrega II (CSS3)

## Como executar
Abra `index.html` no navegador (ou use Live Server no VS Code). Não precisa de instalação.

## Estrutura
- `index.html`, `projetos.html`, `cadastro.html`
- `css/`: `style.css` (importa os demais), `tokens.css`, `base.css`, `components.css`, `responsive.css`, `feedback.css`
- `js/script.js`: máscaras (CPF, telefone, CEP), validação, menu hambúrguer, dropdown, modais, toast
- `imagens/`: **imagens provisórias** geradas automaticamente. Substitua pelas originais mantendo os nomes (`logo.png`, `ong.jpg`, `voluntarios.jpg`, `projeto-1.jpg`, `projeto-2.jpg`, `projeto-3.jpg`).

## O que funciona
- Variáveis CSS: 12 cores, 6 tamanhos de fonte, espaçamentos de 8 a 64px, sombras e raios.
- Layout com CSS Grid e Flexbox; utilitários de grid de 12 colunas (`.grid-12`, `.col-span-*`, `.col-md-*`), usado na seção de contato da página inicial.
- Breakpoints: 480, 600, 768, 900 e 1200px.
- Menu hambúrguer (abaixo de 768px) e dropdown "Projetos" (clique, Esc e clique fora fecham).
- Cards, botões com hover/focus/active/disabled, badges, alertas, toast e modais (documentos na home; termos no cadastro).
- Formulário com validação visual e mensagem de sucesso + toast (os dados não são enviados a nenhum servidor).

## Pendências conhecidas
- Links de redes sociais e relatórios ainda são `#` (relatórios abrem um modal "em breve").
- Imagens são provisórias.
