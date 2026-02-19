# Desafio Semana 2 - Landing Page de Loções (Lúmina Care)

Este repositório contém a solução do desafio técnico da Semana 2, focado em desenvolvimento Shopify, versionamento via GitHub e dinamismo com objetos Liquid.

## Apresentação da solução do desafio
<video controls src="apresentacao-do-desafio.mp4" title="Title"></video>

## 🚀 O que foi implementado

- **Template Exclusivo**: Criação do arquivo `templates/page.lotion-lp.json`.
- **Seção Dinâmica**: Criação da section `sections/lotion-lp.liquid` centralizando toda a lógica.
- **Schema Dinâmico**: Configuração de seletores para o cliente escolher o **Produto em Destaque** e a **Coleção** diretamente pelo Admin.
- **Navegação Flexível**: Implementação de menus via `linklists` para Header e Footer.
- **Metodologia BEM**: Organização do CSS no arquivo `assets/lotion-lp.css`.
- **Objetos Shopify**: Uso correto dos objetos globais `page`, `product`, `collection` e 
`shop`.

## 🛠️ Pré-requisitos

Antes de clonar e rodar o projeto, você precisa garantir que as ferramentas base do ecossistema Shopify estejam instaladas em sua máquina:

### 1. Ruby
O Shopify CLI é construído em Ruby. 
Recomendado usar o [RubyInstaller](https://rubyinstaller.org/) (versão 3.0 ou superior).

Para verificar se já possui instalado, rode:
```bash
ruby -v
```

### 2. Shopify CLI
O Shopify CLI é a ferramenta de linha de comando oficial para desenvolver temas. Para instalar, utilize o gerenciador de pacotes do Node.js (npm):

```bash
npm install -g @shopify/cli@latest
```
ou
```bash
yarn global add @shopify/cli@latest
```

## 👥 Como clonar e configurar o projeto

Siga os passos abaixo para ter uma cópia do projeto em sua máquina local e conectá-la à sua loja de teste:

**Como clonar e rodar o projeto:**
  ```bash
  git clone https://github.com/DaniloSreis/shakers-semana-2-lp-lotions.git
  ```
  ```bash
  cd shakers-semana-2-lp-lotions
  ```
  ```bash
  shopify theme dev
  ```

**⌨️ Atalhos do Terminal Shopify**
Ao rodar o comando `shopify theme dev`, o terminal exibirá links de visualização do tema.

Você pode:

- Pressionar a tecla e para abrir automaticamente o Theme Editor
- Ou segurar `Ctrl + Clique` no link do Theme Editor para abrir manualmente no navegador

**🖥️ Visualizando a página**
1. Clique no botão **Home Page**

2. Selecione a opção **Pages**

3. Procure pela página `lotion-lp`

4. No canto esquerdo, clique em **Lotion LP Section**

**⚙️ Configurações da seção**
A seção possui dois campos principais:

**🏷️ Produto em destaque** - exibido no header da página

**🧴 Coleção de loções** - exibida na listagem de produtos

Configure esses campos conforme necessário para visualizar corretamente a landing page.