## 📋 Tarefas de Desenvolvimento

### 🛠️ Estrutura Inicial e Migrations

- [x] Criar a migration inicial para as tabelas:
  - `accounts`
  - `tags`
  - `transactions`
- [ ] Embutir as migrations no binário usando o `embed` (`//go:embed`)
- [ ] Implementar execução automática de migrations no startup (se necessário)
- [ ] Instalar shadcn/ui e configurar o frontend

---

### 🧱 Infraestrutura

- [ ] Criar query contas
- [ ] Criar query tags
- [ ] Criar query transações

---

### 🗂️ Front-end

- [ ] Pagina inicial
    - [ ] Listagem de contas com saldo
    - [ ] Modal para criar conta
    - [ ] Botão para criar conta
    - [ ] Botão para excluir conta
- [ ] Página principal
    - [ ] Editar conta
    - [ ] Listagem de transações
    - [ ] Botão para criar transação
    - [ ] Modal para criar transação
    - [ ] Botão para criar tag

---

### 📡 Handlers

- [ ] Criar handler para listar contas
- [ ] Criar handler para criar conta
- [ ] Criar handler para listar tags
- [ ] Criar handler para criar tag
- [ ] Criar handler para listar transações
- [ ] Criar handler para criar transação
- [ ] Criar handler para atualizar status de pagamento de transação
- [ ] Criar handler para deletar transação

---

### 🔁 Regras de Negócio / Validações

- [ ] Validar tipo da transação (`INCOME` ou `EXPENSE`)
- [ ] Validar existência de conta e tag ao criar transação
- [ ] Atualizar saldo da conta automaticamente

---

### 📌 Funcionalidades Avançadas

- [ ] Filtro de transações por período, tag ou tipo
- [ ] Exportação de extrato em PDF ou CSV
- [ ] Cobranças recorrentes

### ✅ Conclusão

- [ ] Atualizações automáticas do wails