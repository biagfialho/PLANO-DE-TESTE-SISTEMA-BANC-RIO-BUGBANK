# BugBank – Projeto de Testes Manuais e Automatizados

Este repositório contém um projeto de **Quality Assurance (QA)** desenvolvido para a aplicação **BugBank**, um sistema bancário de testes utilizado para fins educacionais.

O objetivo do projeto é aplicar conceitos de **testes manuais**, **planejamento de testes** e **automação de testes E2E**, demonstrando boas práticas de QA em um cenário realista.

## Objetivo do Projeto

- Validar funcionalidades críticas de um sistema bancário
- Praticar análise de requisitos e criação de plano de testes
- Desenvolver casos de teste manuais
- Implementar testes automatizados utilizando Python e Selenium
- Executar testes de extrato e login
- Evoluir o projeto com Playwright como framework moderno de automação

## Funcionalidades Testadas

- Login
- Cadastro de usuário
- Transferência bancária
- Visualização de extrato e saldo

## Tipos de Testes Aplicados

- Testes Funcionais
- Testes de Validação de Campos
- Testes de Interface (UI)
- Testes de Integração
- Testes Automatizados End-to-End (E2E)

## Tecnologias e Ferramentas Utilizadas

- Python
- Selenium WebDriver
- Pytest
- WebDriver Manager
- VS Code
- PyCharm
- Git e GitHub
- Plataforma Teste.ia
- Playwright (projeto complementar)

Como Executar os Testes Automatizado

## 1 Pré-requisitos

-Python 3.9 ou superior
-Google Chrome instalado
-Pip atualizado

## 2 Instalação das Dependências

```
pip install selenium
pip install pytest
pip install webdriver-manager
```

## 3 Executar os Testes

Para executar todos os testes:
```
pytest
```
Ou executar um teste específico:
```
pytest login.py
pytest extrato.py
```
### Evidências de Teste

Durante a execução dos testes foram geradas evidências como:
*Prints de execução
*Logs de erro
*Resultados no terminal do VS Code
Essas evidências comprovam a execução e validação dos cenários propostos.

### Evolução do Projeto

Como evolução do aprendizado, foi iniciado um projeto adicional utilizando Playwright, aplicando conceitos modernos de automação de testes E2E, com foco em estabilidade, legibilidade e boas práticas.

### Referências

*https://bugbank.netlify.app
*https://www.selenium.dev
*https://docs.pytest.org
*https://playwright.dev


