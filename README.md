# AluGames Alura

Projeto desenvolvido como estudo de JavaScript na Alura, simulando uma interface simples de aluguel de boardgames.

A aplicação exibe uma lista de jogos e permite alternar o status de cada item entre **Alugar** e **Devolver**, manipulando classes CSS e elementos da página com JavaScript.

## Sobre o projeto

O **AluGames-Alura** é uma página web estática criada para praticar conceitos fundamentais de HTML, CSS e JavaScript.

A proposta do projeto é simular o controle visual de jogos alugados. Ao clicar no botão de um jogo, o JavaScript altera o estado do card, muda o texto do botão e aplica estilos diferentes para indicar se o jogo está disponível ou alugado.

## Funcionalidades

- Exibição de jogos de tabuleiro;
- Botão para alugar um jogo;
- Botão para devolver um jogo alugado;
- Confirmação antes de devolver um jogo;
- Alteração visual do card conforme o status;
- Contagem de jogos alugados exibida no console;
- Manipulação do DOM com JavaScript.

## Tecnologias utilizadas

- HTML5;
- CSS3;
- JavaScript.

## Estrutura do repositório

```text
AluGames-Alura/
├── css/
│   └── Arquivos de estilo do projeto
├── img/
│   └── Imagens utilizadas na interface
├── js/
│   └── Script principal da aplicação
├── index.html
├── LICENSE
└── .gitattributes
```

## Como executar

1. Clone o repositório:

```bash
git clone https://github.com/thamiscoder/AluGames-Alura.git
```

2. Acesse a pasta do projeto:

```bash
cd AluGames-Alura
```

3. Abra o arquivo `index.html` no navegador.

Também é possível usar uma extensão como **Live Server** no VS Code para visualizar o projeto localmente.

## O que foi praticado

- Seleção de elementos com `document.getElementById`;
- Uso de `querySelector`;
- Manipulação de classes com `classList`;
- Alteração de textos com `textContent`;
- Eventos de clique;
- Confirmação com `confirm`;
- Execução de código após o carregamento do DOM;
- Organização básica de arquivos front-end.

## Objetivo de estudo

Este projeto foi feito com foco em aprendizado, servindo como prática de lógica de programação aplicada ao navegador e manipulação visual de elementos com JavaScript.

## Licença

Este projeto está sob a licença MIT.
