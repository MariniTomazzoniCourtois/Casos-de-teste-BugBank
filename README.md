 🧪 Casos de Testes - BugBank

Este repositório contém a documentação de casos de teste desenvolvidos para a aplicação BugBank, com foco na validação dos principais fluxos funcionais e não funcionais do sistema.

---

## 📌 Objetivo

Demonstrar habilidades em:
- Modelagem de casos de teste
- Organização e documentação
- Pensamento crítico em QA
- Cobertura de cenários positivos e negativos

---

## 📂 Estrutura

## Estrutura
- `Planilha de Casos de Teste - Marini.xlsx` → Planilha oficial
- `Planilha Casos de Teste.csv` → Versão em .csv

---

## 🧩 Cenários cobertos

### 🔹 Funcionais
- Cadastro de usuário (com e sem saldo inicial)
- Validação de campos obrigatórios (nome, e-mail, senha e confirmação)
- Validação de e-mail (formato inválido e duplicidade)
- Consistência de senha (validação entre senha e confirmação)

### 🔹 Não funcionais
- Performance (tempo de resposta no login)
- Carga (múltiplos usuários simultâneos)
- Segurança (expiração de sessão por inatividade)
- Usabilidade (clareza das mensagens de erro)
- Compatibilidade (execução em diferentes navegadores)

---

## ✅ Abordagem de testes

Os testes foram elaborados considerando:
- Validações de campos obrigatórios
- Regras de negócio (ex: saldo inicial, unicidade de e-mail)
- Tratamento de erros
- Cenários negativos
- Validação de consistência entre dados

---

## 🚀 Possíveis melhorias

- Automação dos cenários críticos
- Integração com pipelines de CI/CD
- Expansão de testes de borda
- Geração de dados dinâmicos para execução

---

## 🛠️ Ferramentas utilizadas

- Excel / Planilha para documentação
- GitHub para versionamento

---

## 👤 Autor

Desenvolvido por Marini Tomazzoni Courtois
Linkedin: https://www.linkedin.com/in/marini-tomazzoni-courtois/ 
---

## 📎 Observação

Este material representa o início de um planejamento de testes, com potencial de evolução para aumento de cobertura e automação.
