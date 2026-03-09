# 🐞 Relatório de Bugs

Este documento contém os bugs identificados durante a execução dos testes no módulo de **cadastro e listagem de cursos** da aplicação.

Aplicação analisada:
https://creative-sherbet-a51eac.netlify.app/

---

## Bug 1

**Título:** Sistema permite cadastrar curso com campo obrigatório vazio

**Severidade:** Alta

**Passos para reproduzir:**

1. Acessar a página de cadastro de cursos
2. Deixar um dos campos obrigatórios vazio
3. Clicar no botão **Salvar**

**Resultado atual:**
O sistema permite salvar o curso mesmo com campos obrigatórios não preenchidos.

**Resultado esperado:**
O sistema deveria impedir o cadastro e exibir uma mensagem informando que o campo é obrigatório.

**Evidência:**
https://drive.google.com/drive/folders/1u4dqlNQ2B14SHTQoIoP7sbq_XPZxrbPG

---

## Bug 2

**Título:** Sistema permite cadastro duplicado de cursos

**Severidade:** Média

**Passos para reproduzir:**

1. Acessar a página de cadastro
2. Cadastrar um curso com determinado nome
3. Tentar cadastrar novamente com os mesmos dados

**Resultado atual:**
O sistema permite cadastrar o mesmo curso mais de uma vez.

**Resultado esperado:**
O sistema deveria impedir cadastro duplicado ou exibir mensagem informando que o curso já existe.

**Evidência:**
https://drive.google.com/drive/folders/1u4dqlNQ2B14SHTQoIoP7sbq_XPZxrbPG

---

## Bug 3

**Título:** Campos aceitam apenas espaços em branco

**Severidade:** Média

**Passos para reproduzir:**

1. Acessar a página de cadastro
2. Inserir apenas espaços em branco em um campo
3. Clicar no botão **Salvar**

**Resultado atual:**
O sistema aceita o cadastro com campos contendo apenas espaços.

**Resultado esperado:**
O sistema deveria validar o campo e impedir o cadastro.

**Evidência:**
https://drive.google.com/drive/folders/1u4dqlNQ2B14SHTQoIoP7sbq_XPZxrbPG

---

## Bug 4

**Título:** Lista de cursos não atualiza automaticamente após cadastro

**Severidade:** Baixa

**Passos para reproduzir:**

1. Acessar a página de cadastro
2. Cadastrar um novo curso
3. Ir para a página de listagem de cursos

**Resultado atual:**
O novo curso não aparece na lista imediatamente.

**Resultado esperado:**
A lista deveria atualizar automaticamente exibindo o novo curso cadastrado.

**Evidência:**
https://drive.google.com/drive/folders/1u4dqlNQ2B14SHTQoIoP7sbq_XPZxrbPG

---

## Bug 5

**Título:** Botão Deletar não deleta o curso

**Severidade:** Média

**Passos para reproduzir:**

1. Acessar painel "Listar Cursos"
2. Clicar no botão **Excluir Curso**

**Resultado atual:**
O sistema aparece o aviso de exclusão porem o curso não some do painel.

**Resultado esperado:**
O sistema deveria excluir o curso selecionado.

**Evidência:**
https://drive.google.com/drive/folders/1u4dqlNQ2B14SHTQoIoP7sbq_XPZxrbPG
