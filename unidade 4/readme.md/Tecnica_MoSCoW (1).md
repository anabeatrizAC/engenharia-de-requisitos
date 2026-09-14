ALUNAS: Erica Pereira, Ana Beatriz De Almeida Ramos
# Guia Prático - Técnica MoSCoW para Priorização de Requisitos

## 11. Atividade do grupo - Matriz MOSCOW

Apliquem a técnica aos requisitos levantados no projeto. Marquem apenas uma categoria por requisito e registrem a justificativa.

| ID | Requisito | M | S | C | W | Justificativa |
| :--- | :--- | :---: | :---: | :---: | :---: | :--- |
| **RF01** | Cadastrar pacientes | **X** | | | | deve ser necessário para facilitar o atendimento. |
| **RF02** | Agendar consulta | **X** | | | | Necessário para agilizar o atendimento. |
| **RF03** | Cadastrar médicos | **X** | | | | Necessário para identificar os médicos. |
| **RF04** | Cadastrar especialidades. | **X** | | | | Necessário para direcionar o paciente para o atendimento correto. |
| **RF05** | Consultar horários disponíveis | **X** | | | | Essencial para o agendamento. |
| **RF06** | Confirmar agendamento | **X** | | | | Necessário para não ocorrer atraso ou cancelamento da consulta. |
| **RF07** | Cancelar consulta | **X** | | | | Necessário para liberar horários. |
| **RF08** | Reagendar consultas. | |**X**  | | | Deve ter para facilitar a organização das consultas. |
| **RQ01** | Sistema disponível durante o horário de funcionamento da clínica. | **X** | | | | Necessário para agilidade no atendimento. |
| **RQ02** | sistema deverá apresentar mensagens claras de erro e confirmação | **X** | | | | Necessário para não ocorrer nenhum engano. |
| **RQ03** | Privacidade e conformidade com a LGPD | **X** | | | | Deve ter para a privacidade dos dados. |
| **RQ04** | Disponibilidade do sistema | **X** | | | | Deve ter para esclarecer dúvidas e agendamento de consultas ou exames. |
| **RQ05** | Integridade e confiabilidade dos dados | **X** | | | | Necessário para priorizar a segurança dos dados do usuário. |

---

## 12. Definindo a primeira versão

**Situação-problema:** a equipe descobriu que terá apenas metade do tempo inicialmente previsto para desenvolver a primeira versão.

### Parte A - Selecione 5 requisitos indispensáveis

| Ordem | ID | Requisito | Por que precisa permanecer? |
| :---: | :--- | :--- | :--- |
| **1** | RF01 | Cadastrar pacientes | Necessário para identificar pacientes. |
| **2** | RF02 | Agendar consulta | É uma funcionalidade muito importante. |
| **3** | RF03 | Cadastrar médicos | Necessário para identificar os médicos. |
| **4** | RF04 | Cadastrar especialidades | deve ter para esclarecer dúvidas e agendamento de consultas ou exames. |
| **5** | RF05 | Consultar horários disponível | Essencial para agendamento de consultas ou exames. |

### Parte B - Selecione 3 requisitos que podem ir para uma versão futura

| ID | Requisito | Impacto de adiar |
| :--- | :--- | :--- |
| **RNF01** | Sistema disponível durante o horário de funcionamento da clínica | Não pode adiar porque os pacientes precisam do sistema para agendamento de consultas ou exames e também para a atendente agilizar o atendimento. |
| **RNF02** | Integridade e confiabilidade dos dados | Necessário para garantir que a informação não foi alterada, corrompida, violada ou destruída de forma indevida ou não autorizada durante o seu armazenamento, processamento ou transmissão. |
| **RNF03** | Privacidade e conformidade com a LGPD | Necessário para a privacidade dos dados dos pacientes. |

---

## 13. Desafio - Definindo o MVP

Observem os requisitos classificados como **Must Have** e respondam: com esses requisitos conseguimos entregar uma primeira versão que resolva o problema principal do usuário? Sim, com os requisitos classificados como Must Have, conseguimos entregar uma primeira versão que resolve o principal problema do usuário, que é facilitar e organizar o agendamento de consultas.  Se não, revisem a priorização. Se sim, vocês possuem um primeiro conjunto de requisitos candidatos à entrega inicial. 

 

---

## 14. Checklist MOSCOW

- [x] Todos os requisitos possuem uma prioridade? **sim**
- [x] Cada requisito possui apenas uma classificação? **sim**
- [x] Os Must são realmente indispensáveis? **sim**
- [x] Existe justificativa para cada prioridade? **sim**
- [x] O grupo considerou valor para o negócio e necessidades dos stakeholders? **sim**
- [x] Foram analisadas dependências, riscos e obrigações? **sim**
- [x] Requisitos de qualidade também foram priorizados? **sim**
- [x] Existem requisitos classificados como Could ou Won't? **não**
- [x] A equipe consegue explicar o impacto de retirar cada Must? **sim**
- [x] A primeira versão é viável considerando as restrições do projeto? **sim**

---

## 15. Reflexão do grupo

1. **Qual requisito foi mais difícil de priorizar? Por quê?**
   Não teve nenhum, porque necessariamente escolhemos somente os essenciais para não ocorrer confusão na hora de separar os requisitos.

2. **Houve algum requisito inicialmente considerado Must que mudou de prioridade?**
   não teve nenhuma

3. **Qual requisito gerou maior divergência entre os integrantes?**
   Não teve nenhum requisito que pudesse gerar uma divergência, pq escolhemos somente os essenciais os outro dava para adiar tranquilamente.

4. **O que aconteceria se todos os requisitos fossem classificados como Must?**
   Se todos fossem classificados como Must, o desenvolvimento ficaria mais demorado e complexo, dificultando a entrega da primeira versão. Além disso, a equipe teria dificuldade para definir o que realmente é prioridade.

5. **Quais requisitos formariam a primeira versão do sistema?**
   - **RF01** - Cadastrar pacientes;
   - **RF02** - Agendar consulta;
   - **RF03** - Cadastrar médicos;
   - **RF04** - Cadastrar especialidades;
   - **RF05** - Consultar horários disponíveis.

---

## 16. Take Away

| Categoria | Descrição |
| :--- | :--- |
| **Must** | Sem ele, a entrega não cumpre seu objetivo. |
| **Should** | É muito importante, mas pode esperar temporariamente. |
| **Could** | É desejável se houver tempo e recursos. |
| **Won't** | Não será desenvolvido nesta entrega. |

> **Regra de ouro:** Priorizar não significa apenas decidir quais requisitos são importantes. Significa decidir o que deve ser entregue primeiro para gerar o maior valor possível dentro das restrições do projeto.

---

## 17. Material de apoio

**REINEHR, Sheila.** *Requisitos de Software*. Material utilizado na disciplina Engenharia de Requisitos. O conteúdo aborda classificação dos requisitos, requisitos funcionais, requisitos de qualidade, restrições, priorização, documentação, critérios de qualidade e verificação dos requisitos.

```
