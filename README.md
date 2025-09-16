# Teste de Software - Trabalho Prático "DataDiver"

Um aplicativo simples de auxílio na tomada de decisões com base em dados inseridos pelo usuário.

---

## 1. Membros do Grupo
- Bruno Oliveira Souza Santos (2022037612)

---

## 2. Explicação do Sistema
O **DataDiver** é um aplicativo de apoio à decisão.  
O usuário poderá inserir:
- O problema ou contexto da decisão.
- As opções disponíveis para escolha.
- Dados ou critérios relevantes para avaliar cada opção.

O sistema, então, analisará as opções com base nos critérios fornecidos e retornará:
- A melhor opção sugerida.
- Uma explicação do porquê essa escolha se destaca entre as demais.

Esse processo ajuda a organizar informações de forma estruturada e clara, tornando a tomada de decisões mais objetiva.

O aplicativo irá salvar as decisões do usuário (bem como as opções apresentadas e a escolha indicada) para visualização posterior.

---

## 3. Tecnologias Utilizadas
Para implementar o DataDiver, algumas tecnologias que o grupo optou por utilizar são:

- **Interface:**
  - NextJS + TypeScript para aplicação
  - TailwindCSS + Shadcn/UI para maior conveniência e facilidade na construção da interface
- **Persistência de Dados:**
  - Firebase Authentication para lidar com os dados de autenticação dos usuários. 
  - Firebase Realtime Database para armazenamento das informações.
- **Testes:**  
  - `Vitest` (TypeScript) para validar as funcionalidades e demonstrar a importância dos testes na manutenção do sistema.

---
