# Landing Page — Projeto Pessoal

Página única (HTML + CSS puro, sem framework) para apresentar um projeto
pessoal fictício ("TaskFlow"). Usa Flexbox para o layout e é responsiva.

## Estrutura

- **Hero** (`.hero`): título, descrição curta e um botão, tudo centralizado
  com `display: flex`.
- **Sobre o projeto** (`#sobre`): texto explicando o projeto.
- **Rodapé** (`.rodape`): copyright + links para GitHub e LinkedIn (troque
  as URLs pelas suas).

## Responsividade

- O layout já funciona em qualquer largura porque usa `flex-direction: column`
  por padrão (empilha tudo verticalmente — bom para celular).
- No `@media (min-width: 768px)` (telas maiores, tipo desktop), o rodapé
  passa a usar `flex-direction: row` (itens lado a lado) e o título do hero
  fica maior.
- `max-width` nos containers (`.hero-conteudo`, `.sobre`) evita que o texto
  fique esticado demais em telas muito largas.

## Como ver

Basta abrir o `index.html` direto no navegador (duplo clique no arquivo),
ou usar a extensão "Live Server" do VS Code, se tiver instalada.

## Possíveis melhorias futuras
- Adicionar uma seção de "funcionalidades" com ícones.
- Trocar os links do rodapé pelos seus próprios GitHub/LinkedIn.
- Adicionar uma fonte customizada do Google Fonts.
