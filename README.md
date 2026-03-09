# DESAFIO-QA-BEEDOO-2026

## 📌 Sobre o desafio

Este repositório contém a análise, criação e execução de testes para o módulo de **cadastro e listagem de cursos** da aplicação disponibilizada no desafio técnico.

O objetivo deste desafio é avaliar a capacidade de análise da aplicação, criação de cenários de teste, identificação de possíveis problemas e documentação clara dos resultados.

Aplicação analisada:

https://creative-sherbet-a51eac.netlify.app/

---

# 🔎 Análise inicial da aplicação

## 🎯 Objetivo da aplicação

A aplicação aparenta ter como objetivo permitir o **gerenciamento de cursos**, possibilitando que o usuário realize o cadastro de novos cursos e visualize uma lista com os cursos já cadastrados.

O sistema oferece uma interface simples onde o usuário pode inserir informações sobre um curso e posteriormente visualizar esses cursos em uma listagem.

---

## 🔄 Principais fluxos disponíveis

Durante a exploração da aplicação foram identificados os seguintes fluxos principais:

* Cadastro de novos cursos
* Visualização da lista de cursos cadastrados
* Validação de campos no formulário de cadastro
* Atualização da lista após o cadastro de um novo curso

Esses fluxos representam as funcionalidades centrais da aplicação e foram considerados como base para a criação dos cenários de teste.

---

## ⚠️ Pontos críticos para teste

Os pontos considerados mais críticos para teste foram:

* Validação dos campos obrigatórios no formulário de cadastro
* Comportamento do sistema ao inserir dados inválidos
* Atualização correta da lista após o cadastro de um novo curso
* Exibição correta das informações dos cursos cadastrados
* Tratamento de erros e mensagens exibidas ao usuário

Esses pontos são importantes pois impactam diretamente na integridade dos dados e na experiência do usuário.

---

# 🧪 Estratégia de testes

Para a criação dos cenários de teste foram considerados os principais fluxos da aplicação, priorizando funcionalidades críticas.

Os testes foram estruturados considerando:

* Cenários positivos (fluxo esperado)
* Cenários negativos
* Validação de campos obrigatórios
* Possíveis comportamentos inesperados

Os cenários e casos de teste foram documentados em uma planilha para facilitar a organização e rastreabilidade.

📊 Planilha de cenários de teste:

https://docs.google.com/spreadsheets/d/1h5BiavC2oMrQ-m_iP-scNmpXJsaWzTC4ooBfSKEahtw/edit?usp=sharing

---

# ▶️ Execução dos testes

Após a criação dos cenários de teste, os testes foram executados diretamente na aplicação.

Durante a execução foram registrados:

* Resultado obtido
* Evidências da execução
* Possíveis falhas identificadas

📂 Evidências da execução dos testes:

https://drive.google.com/drive/folders/1u4dqlNQ2B14SHTQoIoP7sbq_XPZxrbPG


---

# 🐞 Relatório de bugs

Durante a execução dos testes foram identificados alguns comportamentos inesperados.

O relatório detalhado de bugs encontrados está disponível em:

📄 bugs.md

Cada bug contém:

* Título
* Passos para reprodução
* Resultado atual
* Resultado esperado
* Severidade ou impacto

---

# 🤖 Uso de Inteligência Artificial

Ferramentas de Inteligência Artificial foram utilizadas como apoio durante a organização da documentação e estruturação dos relatórios.

As decisões relacionadas à análise da aplicação, criação dos cenários de teste e identificação de bugs foram realizadas com base na exploração manual da aplicação e avaliação crítica dos resultados.

---

# 📌 Conclusão

A análise realizada permitiu validar os principais fluxos da aplicação e identificar possíveis melhorias relacionadas à validação de dados e comportamento do sistema.

A documentação dos testes e bugs busca apresentar de forma clara os resultados obtidos durante o desafio.
