# Caderno de Receitas

Projeto desenvolvido para a **Avaliação da Unidade I** da disciplina de **Desenvolvimento Front-End para Web**, do **UNIPÊ**.

O projeto consiste em um **Caderno de Receitas** desenvolvido exclusivamente com **HTML5 puro**, utilizando elementos de estruturação semântica, formulários, tabelas e recursos de mídia.

## Sobre o Projeto

O site apresenta diferentes receitas de doces e bebidas, organizadas em páginas individuais. Cada receita possui informações sobre ingredientes, modo de preparo e características específicas.

O projeto também utiliza recursos do HTML5, como:

* Estrutura semântica;
* Imagens;
* Áudio;
* Vídeo;
* Tabelas;
* Formulários;
* Listas ordenadas e não ordenadas;
* Elemento `<details>` e `<summary>`;
* Indicadores de progresso;
* Comentários em HTML;
* Links entre páginas.

## Estrutura do Projeto

```text
.
├── index.html
├── README.md
│
├── audio/
│   └── vinheta.mp3
│
├── video/
│   └── preparo.mp4
│
├── img/
│   ├── torta.jpg
│   ├── brownie.jpg
│   ├── pudim.jpg
│   └── capuccino.jpg
│
└── html/
    ├── torta.html
    ├── brownie.html
    ├── pudim.html
    └── capuccino.html
```

## Páginas

### Início

**`index.html`**

Página principal do projeto, contendo:

* Apresentação do Caderno de Receitas;
* Citação relacionada à aula;
* Vídeo local;
* Áudio local;
* Formulário de avaliação.

### Pudim de Leite

**`html/pudim.html`**

Receita de pudim de leite condensado, contendo:

* Ingredientes;
* Modo de preparo;
* Tabela com informações de rendimento e tempo;
* Utilização de `rowspan`;
* Menu retrátil com `<details>`.

### Torta de Cookies

**`html/torta.html`**

Receita de torta de cookies preparada em forma de fundo removível, contendo:

* Ingredientes;
* Modo de preparo;
* Informações sobre o preparo;
* Menu retrátil com `<details>`.

### Brownie de Chocolate

**`html/brownie.html`**

Receita de brownie de chocolate, contendo:

* Ingredientes;
* Modo de preparo;
* Informações da receita;
* Comentário HTML de autoria;
* Menu retrátil com `<details>`.

### Capuccino de Panela

**`html/capuccino.html`**

Receita de capuccino preparado diretamente na panela, utilizando café solúvel, leite, canela, achocolatado e açúcar.

A página contém:

* Ingredientes;
* Modo de preparo;
* Indicadores de progresso;
* Menu retrátil com `<details>`.

## Tecnologias Utilizadas

O projeto foi desenvolvido utilizando exclusivamente:

* **HTML5**

Não foram utilizados:

* CSS;
* JavaScript;
* Frameworks;
* Bibliotecas externas;
* Pacotes ou dependências.

## Como Executar

### 1. Clonar o repositório

```bash
git clone https://github.com/SEU_USUARIO/caderno-de-receitas.git
```

### 2. Entrar na pasta do projeto

```bash
cd caderno-de-receitas
```

### 3. Abrir o projeto

Abra o arquivo `index.html` diretamente em um navegador, como:

* Google Chrome;
* Microsoft Edge;
* Mozilla Firefox;
* Safari.

Também é possível abrir a pasta do projeto no **Visual Studio Code** e utilizar a extensão **Live Server** para executar o projeto em um servidor local.

> **Observação:** não é necessária a instalação de pacotes ou dependências, pois o projeto foi desenvolvido exclusivamente com HTML5.

## 👨‍💻 Autoria

Projeto acadêmico desenvolvido para a disciplina de **Desenvolvimento Front-End para Web - UNIPÊ**.
