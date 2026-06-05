## Aula 5 - CSS Avançado: Pseudo-elementos e Seletores Avançados

- Repositório: https://github.com/s-a-m-i-o/pseudo-elementos
- Projeto: Card de produto com selo de oferta e animação
- ::before e ::after: criam elementos "fantasma" antes e depois do conteúdo, sem tocar no HTML
- content é obrigatório nos pseudo-elementos, mesmo vazio content: ""
- Pseudo-elementos precisam de display: block ou display: flex pra aceitar width e height
- position: relative no pai + position: absolute no filho = filho se posiciona em relação ao pai
- Diferença entre pseudo-classes (:): representam um estado — e pseudo-elementos (::): criam uma parte do elemento

- - Seletores avançados:

- :first-child — seleciona o primeiro filho
- :last-child — seleciona o último filho
- :nth-child(n) — seleciona o filho pela posição
- :not() — seleciona todos exceto o especificado
- > — seleciona apenas filhos diretos
- + — seleciona o elemento imediatamente após outro
- ~ — seleciona todos os irmãos após um elemento