# ihcux-racha-ai-prototipo
# RachaAí — Protótipo de Baixa Fidelidade (IHC & UX)

---

## 👤 Nome do aluno/equipe
- Nome: Lucas Gonçalves 32617617

---

## 🎯 Persona (para quem o sistema foi projetado?)

O RachaAí foi projetado principalmente para:

### 🧑‍🎓 Estudantes universitários que moram em repúblicas

Características da persona:
- Idade entre 18 e 28 anos
- Compartilham despesas com colegas de casa
- Possuem renda limitada ou variável
- Precisam dividir contas com frequência (aluguel, mercado, internet, contas de casa)
- Têm pouco tempo e querem evitar conflitos financeiros

Também pode atender:
- Casais que dividem despesas
- Amigos em viagens compartilhadas

---

## 🧠 Heurística de Nielsen em foco

A heurística mais priorizada neste protótipo foi:

### 👁️ Visibilidade do status do sistema

### Justificativa:
O sistema foi projetado para sempre deixar claro:

- Quem pagou
- Quem deve
- Quanto falta pagar
- Status das transações (pendente, pago, em análise)

### Aplicação no protótipo:
- Dashboard com saldo geral visível
- Extrato de dívidas com status claro
- Feedback imediato após ações (ex: pagamento realizado)
- Indicação visual com cores:
  - 🔴 deve
  - 🟢 recebe
  - 🟡 pendente

---

## 🔁 Fluxo de tarefa: Cadastro de conta de luz e divisão entre 3 pessoas

### 📌 Objetivo da tarefa:
Registrar uma conta de luz e dividir igualmente entre três moradores.

---

### 🪜 Passo a passo:

```plaintext
1. Usuário acessa o Dashboard
        ↓
2. Clica em “+ Novo Gasto”
        ↓
3. Abre a tela “Adicionar Gasto”
        ↓
4. Preenche os dados:
   - Descrição: Conta de luz
   - Valor: R$ 150,00
        ↓
5. Seleciona o grupo: “Casa”
        ↓
6. Escolhe os participantes:
   - Pessoa 1
   - Pessoa 2
   - Pessoa 3
        ↓
7. Seleciona tipo de divisão:
   - Igual (50/50/50)
        ↓
8. Clica em “Confirmar”
        ↓
9. Sistema registra o gasto
        ↓
10. Atualiza automaticamente:
   - saldo de cada pessoa
   - total do grupo
        ↓
11. Usuário é redirecionado para o Dashboard
        ↓
12. Visualiza atualização do saldo geral
