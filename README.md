<div id="top"></div>

# Desafio de Automação Web

## Cenário de Teste

**Scenario:** *Acessar Magazine Luiza e adicionar produto no carrinho*<br/>
**Given** *Acesso a Magazine Luiza*<br/>
**And** *Busco por produto*<br/>
**And** *Encontro o produto*<br/>
**when** *Escolho um produto*<br/>
**Then** *Adiciono o produto ao carrinho*

## Decisões

#### 1. Site de comércio Online:

*(sujestoes: Americanas, Submarino, Magazine Luiza)*

• **Magazine Luiza** por conter no código da sua estrutura (HTML) marcadores específicos de teste (*__data-testid=__*) na qual facilita para referenciar elementos que iram receber interação durante o teste.



#### 2. Ferramentas para automação:

*(Sugestões: SeIenium,Junit, Testng, cucumber e linguagens como: Ruby, Java, Python, Javascript.)*

• **Cypress** utilizando **Javascript** por já ter tido um contato introdutório com a ferramenta além de ter sido mencionado como uma ferramenta que já foi utilizada pela empresa.

## Tecnologias utilizadas
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![cypress](https://img.shields.io/badge/-cypress-%23E5E5E5?style=for-the-badge&logo=cypress&logoColor=058a5e)
![Mocha](https://img.shields.io/badge/-mochawesome-%238D6748?style=for-the-badge&logo=mocha&logoColor=white)


• **NodeJS** *(ambiente de execução Javascript)*
<br/>
• **NPM** *(Gerenciador de Pacotes)*
<br/>
• **JavaScript** *(linguagem de desenvolvimento)*
<br/>
• **Cypress** *(Ferramenta de teste)*
<br/>
• **Mochawesome** *(reporter  personalizado para estrutura de testes Javascript)*

## 
<img  alt="TesteE2E" width="700" src="https://github.com/roodrigoomendes/Teste_QA_fiabilite/blob/master/MagazineLuiza.gif?raw=true">

## Acessar o relatório Mochawesome

<a link href="https://roodrigoomendes.github.io/Teste_QA_fiabilite/cypress/reporte/mochawesome-report/mochawesome_2.html" target="_blank">![Site](https://shields.io/badge/acessar-mochawesome-green?&style=for-the-badge)</a>

## Clone para Execução

Clone este repositório para sua máquina local usando comando abaixo:

```
$ git clone https://github.com/roodrigoomendes/Teste_QA_fiabilite.git
```

### Execução na interface

Acessar a raiz do repositório
```
$ cd /{diretorio}/Teste_QA_fiabilite
```
Execute comando para instalar as dependências listadas na seção de `devDependencies` do arquivo `package.json`

```
npm install
```

Execute comando para abrir a UI do cypress
```
npx cypress open
```

Na UI do cypress
```
1. Clicar em E2E Testing
2. Clicar na opção Electron como browser
• Confirmar em Start E2E Testing in Electron

3. Selecionar qual teste deseja iniciar:

• 2COMPRASMagazineLuiza (2 compras utilizando o mesma base de teste, alterando somente o produto pesquisado)

• MagazineLuiza (executa a compra de um único produto pré definido através de variáveis no código)
  
```

>### Execução modo headless 

Acessar a raiz do repositório
```
$ cd /{diretorio}/Teste_QA_fiabilite
```
Abrir o ```git bash```
Execute comando 
```
npx cypress run
```



