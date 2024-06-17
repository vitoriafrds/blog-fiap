# Seja bem-vindo ao Blog FIAP!

Esse repositório contém o código necessário para finalizar o blog da Fiap que teve sua construção iniciada em aula.

## 🚀 Começando

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.

### 📋 Pré-requisitos

Do que é necessário para subir o ambiente local na sua máquina?

* Node 20
* Git bash instalado e configurado.
* Visual Studio Code versão 1.9.x ou Alguma IDE de sua preferência.

#### Clonar o projeto localmente:

Primeiro você precisa clonar o projeto para a sua máquina local:

```bash
git clone https://github.com/vitoriafrds/blog-fiap.git
```

#### Configuração de variáveis de ambiente do Contentful no projeto:

* Crie um arquivo com o nome: .env.local na raiz do projeto.
* Dentro dele atribua as seguintes propriedades, com o ID e token correspondentes, gerados nos passos anteriores:
```
VITE_SPACE_ID=[Space ID]
VITE_ACCESS_TOKEN=[Content Delivery API - access token]
```

***Atenção: Não é recomendado realizar o push desse arquivo para o repositório devido ao conteúdo sensível (credenciais)***


### 🔧 Instalação
Para a execução do projeto execute o comando abaixo:

```bash
npm run dev
```

O servidor retornará uma URL local que poderá ser acessada para interagir com o sistema, mas normalmente é a seguinte: http://localhost:5173/

## 📦 Deploy 

Para implantar este sistema, você vai precisar da pasta dist que será gerada após o comando:

```bash
npm run build
```

## 🛠️ Ferramentas utilizadas nesse projeto

* [ViteJS](https://vitejs.dev/) - A ferramenta de construção usada.
* [React](https://react.dev/) - O framework usado para desenvolvimento.
* [Node](https://nodejs.org/en) - Ambiente de execução utilizado.
* [NPM](https://www.npmjs.com/) - Gerenciador de dependências.
* [Contentful](https://www.contentful.com/) - CMS usado para conteúdo dinâmico.
* [Netlify](https://www.netlify.com/) - Cloud usada para fazer [deploy do projeto](https://glistening-trifle-7ffbe3.netlify.app/).
