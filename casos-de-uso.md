# Casos de Uso

## UC01 - Agendar consulta

**Ator:** Paciente

**Objetivo:** Permitir que o paciente agende uma consulta em um horário disponível.

### Fluxo principal

1. O paciente acessa a opção de agendamento.
2. O sistema apresenta as datas disponíveis.
3. O paciente seleciona uma data.
4. O sistema apresenta os horários disponíveis.
5. O paciente seleciona um horário.
6. O sistema solicita a confirmação.
7. O paciente confirma o agendamento.
8. O sistema registra a consulta e apresenta a confirmação.

### Fluxo alternativo

- Caso o horário escolhido esteja indisponível, o sistema deve informar o paciente e apresentar outros horários disponíveis.

---

## UC02 - Consultar agendamentos

**Ator:** Paciente

**Objetivo:** Permitir que o paciente consulte suas consultas agendadas.

### Fluxo principal

1. O paciente acessa a opção de consultas.
2. O sistema apresenta as consultas agendadas.
3. O paciente visualiza a data e o horário de cada consulta.

---

## UC03 - Cancelar consulta

**Ator:** Paciente

**Objetivo:** Permitir que o paciente cancele uma consulta agendada.

### Fluxo principal

1. O paciente acessa suas consultas.
2. O paciente seleciona a consulta que deseja cancelar.
3. O sistema solicita a confirmação.
4. O paciente confirma o cancelamento.
5. O sistema cancela a consulta.
6. O sistema informa que o cancelamento foi realizado com sucesso.
