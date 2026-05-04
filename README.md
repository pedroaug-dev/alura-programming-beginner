# Lógica de Programação: Praticando com Desafios

Projeto desenvolvido durante os estudos na Alura, com foco na prática de lógica de programação utilizando JavaScript, HTML e CSS. O repositório reúne diferentes desafios independentes, criados para exercitar manipulação do DOM, eventos, funções, arrays, validações, condicionais, laços de repetição e atualização dinâmica de elementos na página.

## Sobre o projeto

Este projeto foi desenvolvido como parte do processo de aprendizagem em lógica de programação, aplicando conceitos fundamentais por meio de pequenos sistemas interativos. Cada pasta representa um desafio diferente, com uma proposta prática para reforçar o raciocínio lógico e a construção de funcionalidades no navegador.

Os desafios foram implementados com JavaScript puro, sem uso de frameworks, permitindo compreender melhor a base da programação web e a interação entre estrutura HTML, estilização CSS e comportamento dinâmico com JavaScript.

## Desafios desenvolvidos

### AluGames

Sistema simples de aluguel de boardgames. O usuário pode alterar o status de um jogo entre disponível e alugado, modificando visualmente o botão e a imagem do item selecionado.

Principais conceitos praticados:

- Manipulação de classes CSS com JavaScript;
- Seleção de elementos pelo DOM;
- Alteração de textos dinamicamente;
- Controle de estado visual de elementos.

### Amigo Secreto

Aplicação para cadastro de participantes e realização de sorteio de amigo secreto. O sistema permite adicionar nomes, impedir nomes duplicados, validar quantidade mínima de participantes, embaralhar a lista e gerar os pares do sorteio.

Principais conceitos praticados:

- Uso de arrays;
- Validação de campos;
- Estruturas condicionais;
- Laços de repetição;
- Manipulação de conteúdo com `textContent` e `innerHTML`;
- Criação de algoritmo de embaralhamento.

### Carrinho de Compras

Simulação de carrinho de compras, permitindo selecionar produtos, informar quantidade, calcular subtotal e atualizar o valor total da compra.

Principais conceitos praticados:

- Captura de valores de formulários;
- Separação de informações usando `split`;
- Cálculos com valores numéricos;
- Atualização dinâmica da lista de produtos;
- Controle de total acumulado.

### e-Ticket

Sistema de compra de ingressos com controle de quantidade disponível por tipo de ingresso. O usuário seleciona o setor, informa a quantidade desejada e o sistema valida se há ingressos suficientes antes de concluir a compra.

Principais conceitos praticados:

- Condicionais com múltiplas possibilidades;
- Conversão de valores com `parseInt`;
- Validação de disponibilidade;
- Atualização de estoque na interface;
- Organização da lógica em funções específicas.

### Sorteador de Números

Aplicação para sortear números aleatórios dentro de um intervalo definido pelo usuário. O sistema permite informar a quantidade de números, o intervalo inicial e final, evitando números repetidos no resultado.

Principais conceitos praticados:

- Geração de números aleatórios com `Math.random`;
- Criação de funções reutilizáveis;
- Uso de arrays para armazenar resultados;
- Verificação de valores repetidos;
- Manipulação de botões e estados visuais.

## Tecnologias utilizadas

- HTML5;
- CSS3;
- JavaScript;
- Manipulação do DOM;
- Estruturação de páginas web;
- Lógica de programação aplicada ao front-end.

## Estrutura do projeto

```text
logica-de-programacao-praticando-com-desafios/
├── alugames/
│   ├── css/
│   ├── img/
│   ├── js/
│   └── index.html
├── amigo-secreto/
│   ├── assets/
│   ├── js/
│   ├── index.html
│   └── style.css
├── carrinho-compras/
│   ├── assets/
│   ├── js/
│   ├── index.html
│   └── style.css
├── ingresso/
│   ├── assets/
│   ├── js/
│   ├── styles/
│   └── index.html
└── sorteador-numeros/
    ├── img/
    ├── app.js
    ├── index.html
    └── style.css
```

## Como executar

1. Clone o repositório:

```bash
git clone <url-do-repositorio>
```

2. Acesse a pasta do projeto:

```bash
cd logica-de-programacao-praticando-com-desafios
```

3. Abra o arquivo `index.html` do desafio desejado diretamente no navegador.

Também é possível utilizar a extensão Live Server no Visual Studio Code para executar os projetos localmente com recarregamento automático.

## Aprendizados

Durante o desenvolvimento dos desafios, foram reforçados conceitos essenciais para a construção de aplicações web interativas. O projeto contribuiu para o desenvolvimento do raciocínio lógico, da organização do código em funções, da manipulação de dados em arrays e da atualização dinâmica da interface conforme as ações do usuário.

Além disso, os exercícios ajudaram a consolidar a base necessária para avançar em tecnologias mais robustas do desenvolvimento front-end e back-end, como frameworks JavaScript, integração com APIs e construção de sistemas mais completos.
