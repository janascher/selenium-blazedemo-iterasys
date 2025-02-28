<div  align="center">
	<h1>
		✈️ Automação de Testes com Selenium – BlazeDemo
	</h1>
</div>

## 🧐 Descrição

Este repositório contém o código gerado a partir da automação do fluxo de compra de passagens no site [BlazeDemo](https://blazedemo.com/), um site simples desenvolvido para treino de automações de teste.

O projeto faz parte do curso "Formação em Teste de Software" da [Iterasys](https://iterasys.com.br/pt) e demonstra a criação, exportação e adaptação de um teste gravado com Selenium IDE para execução no VS Code, utilizando Selenium WebDriver e Mocha.

## 📚 Sobre a Automação
O teste automatizado cobre as seguintes etapas:

- Seleção da cidade de origem e destino
- Escolha de um voo disponível
- Preenchimento dos dados de compra (dados fictícios)
- Confirmação da compra

Durante a automação, foram incluídas asserções em todas as etapas para validar o funcionamento correto do fluxo.

## 📚 Tecnologias Utilizadas

- **IDE:** VS Code
- **Linguagem:** JavaScript (Node.js)
- **Gravador de Passos:** Selenium IDE
- **Framework de Automação:** Selenium WebDriver
- **Framework de Teste de Unidade:** Mocha
- **Gerenciador de Pacotes:** npm
- **Ferramenta de Formatação:** Prettier

## ⚙️ Configurar o Ambiente

### 1️⃣ Instalar o Node.js (caso necessário)  

Se não tiver o Node.js instalado, faça o download da versão **22.14.0** pelo site [Node.js](https://nodejs.org/).

### 2️⃣ Definir a versão do Node.js (caso necessário)
Caso ainda não esteja na versão correta, utilize:
```sh
nvm use 22.14.0
```

Ou crie o arquivo `.nvmrc` para definir a versão do Node.js do projeto:
```sh
echo "22.14.0" > .nvmrc
```

### 3️⃣ Instalar as dependências do projeto
No terminal, dentro da pasta do projeto, execute:
```sh
npm install
```

### 4️⃣ Instalar o Selenium WebDriver
```sh
npm i selenium-webdriver
```

### 5️⃣ Instalar o Mocha
```sh
npm i mocha
```

## 🚀 Executar os Testes
Para rodar os testes automatizados, utilize:
```sh
npx mocha
```

## 🦸🏻‍♀️ Autor

<div>
	<a  href="https://github.com/janascher">
		<img  src="https://avatars.githubusercontent.com/u/79182711?v=4"  width="100px;"  alt="Janaína Scher"/>
		<br />
		<sub>
			<b>Janaína Scher</b> 👩🏻‍💻
		</sub>
	</a>
</div>

