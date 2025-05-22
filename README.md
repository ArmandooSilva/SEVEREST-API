# 🧪 Testes de API com Robot Framework

Este projeto realiza testes automatizados de API REST utilizando o **Robot Framework**, com foco nas funcionalidades da aplicação **ServeRest**.

## 🚀 Tecnologias utilizadas

- [Robot Framework](https://robotframework.org/)
- [RequestsLibrary](https://github.com/MarketSquare/robotframework-requests) — Para requisições HTTP
- [Python 3.12](https://www.python.org/downloads/release/python-3120/)

---

## 📁 Estrutura do projeto

📦 APITESTING
┣ 📂 tests/                      # Casos de teste (suite de testes)
┃ └── api_testing_usuarios.robot
┣ 📂 resources/                  # Keywords
┃ └── api_testing_usuarios.resource
┣ 📂 results/                    # Relatórios gerados automaticamente
┃ ├── log.html
┃ ├── output.xml
┃ └── report.html
┣ 📜 README.md                   # Documentação do projeto
┣ 📜 .gitignore                  # Arquivos e pastas ignoradas pelo Git

---

## 🧠 Cenários Testados

1. ✅ **Cadastrar um novo usuário com sucesso na ServeRest**
2. ⚠️ **Cadastrar um usuário já existente**
3. 🔍 **Consultar os dados de um novo usuário**

---

## ▶️ Como Executar

robot -d ./results ./tests/api_testing_usuarios.robot

---

## 📜 Relatórios
Após a execução, os relatórios estarão na pasta /results:

1. log.html → Detalhes completos da execução.
2. report.html → Sumário dos testes.
3. output.xml → Arquivo de saída.

---

### 🔹 1. Clone o repositório

```bash
git clone https://github.com/ArmandooSilva/SEVEREST-API.git
cd APITESTING
