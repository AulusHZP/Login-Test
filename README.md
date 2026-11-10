# 🤓 Automação de Testes de Login com Playwright
![Playwright](https://img.shields.io/badge/Playwright-2E8B57?style=for-the-badge&logo=playwright&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Testes automatizados para a página de login do [Automation Practice](http://automationpractice.pl/index.php?controller=authentication&back=my-account)**


## 📚 Índice

- [🌟 Visão Geral](#-visão-geral)
- [🧩 Funcionalidades Testadas](#-funcionalidades-testadas)
- [🛠 Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [✅ Pré-requisitos](#-pré-requisitos)
- [⚙️ Configuração do Projeto](#️-configuração-do-projeto)
  - [1. Clonar o Repositório](#1-clonar-o-repositório)
  - [2. Instalar as Dependências](#2-instalar-as-dependências)
  - [3. Executar os Testes](#3-executar-os-testes)
  - [4. Gerar Relatórios](#4-gerar-relatórios)
- [📁 Estrutura do Projeto](#-estrutura-do-projeto)
- [📬 Contato](#-contato)
- [📄 Licença](#-licença)
- [🔗 Referências](#-referências)


## 🌟 Visão Geral
Este projeto tem como objetivo automatizar testes de qualidade para a página de login do site [Automation Practice](http://www.automationpractice.pl/index.php?controller=authentication&back=my-account). Utilizando o framework Playwright, os testes abrangem cenários críticos para garantir a funcionalidade essencial da aplicação.

## 🧩 Funcionalidades Testadas
| Cenário                   | Descrição                                                                 | Status |
|---------------------------|---------------------------------------------------------------------------|--------|
| Login válido              | Autenticação bem-sucedida com credenciais corretas                        | ✅     |
| E-mail inválido           | Mensagem de erro para e-mail não cadastrado                               | ✅     |
| Senha incorreta           | Mensagem de erro para senha inválida                                      | ✅     |

## 🛠 Tecnologias Utilizadas
- **Playwright**: Framework para automação de testes.
- **Node.js**: Ambiente de execução JavaScript.
- **JavaScript**: Linguagem para escrita dos testes.

---

## ✅ Pré-requisitos

- [Node.js](https://nodejs.org/) versão 14 ou superior
- [npm](https://www.npmjs.com/) versão 6 ou superior


## Configuração do Projeto

### 1. Clonar o Repositório
```bash
git clone https://github.com/AulusHZP/Login-Test.git
cd Login-Test
```
### 2. Instalar as Dependências
```bash
npm install  
```
### 3. Executar os Testes
```bash
npx playwright test  
```
### 4. Gerar Relatórios
```bash
npx playwright show-report
```

## ⚙️ Estrutura do Projeto

```bash
Login-Test/
├── tests/                             # Diretório dos testes
│   ├── login_valid.test.js            # Teste de login com credenciais válidas
│   ├── login_invalid_email.test.js    # Teste de login com email inválido
│   └── login_invalid_password.test.js # Teste de login com senha inválida
├── playwright.config.js               # Configurações do Playwright
├── package.json                       # Dependências e scripts
└── README.md                          # Documentação do projeto
```

## 📬 Contato

Para dúvidas ou sugestões, entre em contato com E-mail: [aulushzp@gmail.com](mailto:aulushzp@gmail.com) ou no LinkedIn: [linkedin.com/in/aulus-batista](https://www.linkedin.com/in/aulus-batista/)

## 📄 Licença

O `package.json` declara a licença MIT. O repositório não contém um arquivo de licença separado.

## 🔗 Referências

- [Documentação do Playwright](https://playwright.dev/docs/intro)
