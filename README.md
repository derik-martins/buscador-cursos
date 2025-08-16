# Buscador de Cursos Alura

![PHP Version](https://img.shields.io/badge/PHP-%3E%3D7.4-blue)
![License](https://img.shields.io/badge/license-MIT-green)

Um projeto PHP simples que busca e lista cursos disponíveis no site da Alura na categoria de programação PHP.

## 📋 Sobre o Projeto

Este projeto utiliza web scraping para extrair informações dos cursos de PHP disponíveis no site da Alura. Ele faz uma requisição HTTP para a página de cursos e utiliza um DOM crawler para extrair os nomes dos cursos disponíveis.

## 🚀 Tecnologias Utilizadas

- **PHP** - Linguagem principal
- **GuzzleHTTP** - Cliente HTTP para fazer requisições
- **Symfony DOM Crawler** - Para navegar e extrair dados do HTML
- **Symfony CSS Selector** - Para seleção de elementos CSS
- **Composer** - Gerenciador de dependências

## 📦 Instalação

### Pré-requisitos

- PHP >= 7.4
- Composer

### Passos para instalação

1. Clone o repositório:
```bash
git clone https://github.com/derik-martins/buscador-cursos.git
cd buscador-cursos
```

2. Instale as dependências via Composer:
```bash
composer install
```

## 🔧 Como usar

Execute o script principal para buscar os cursos:

```bash
php index.php
```

O script irá:
1. Fazer uma requisição para a página de cursos PHP da Alura
2. Extrair os nomes de todos os cursos disponíveis
3. Exibir a lista de cursos no terminal

### Exemplo de saída:
```
PHP para Web: conhecendo a linguagem
Orientação a Objetos com PHP: Classes, métodos e atributos
PHP Strings: manipulando textos com PHP
PHP Arrays: trabalhando com coleções
...
```

## 📁 Estrutura do Projeto

```
buscador-cursos/
├── composer.json          # Configuração do Composer
├── composer.lock         # Lock das versões das dependências
├── index.php            # Script principal
├── vendor/              # Dependências do Composer
└── README.md           # Este arquivo
```
