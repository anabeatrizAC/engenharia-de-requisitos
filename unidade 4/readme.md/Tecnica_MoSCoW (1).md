# 📘 Guia Prático — Técnica MoSCoW para Priorização de Requisitos

> **Disciplina:** Engenharia de Requisitos  
> **Tema:** Priorização de Requisitos  
> **Técnica:** MoSCoW  
> **Atividade:** Projeto de Engenharia de Requisitos

---

## 🎯 Objetivo

Este guia tem como objetivo auxiliar os grupos na **priorização dos requisitos de software** identificados durante o levantamento de requisitos.

Ao final da atividade, o grupo deverá ser capaz de:

- compreender a técnica MoSCoW;
- classificar requisitos de acordo com sua importância;
- identificar requisitos essenciais para a primeira versão do sistema;
- analisar valor, necessidade, dependências e riscos;
- justificar as decisões de priorização;
- definir um conjunto viável de requisitos para a primeira entrega.

---

# 1. Por que priorizar requisitos?

Durante o levantamento de requisitos, é comum identificar muitas necessidades, funcionalidades, características de qualidade e restrições.

Entretanto, normalmente existem limitações de:

- ⏱️ tempo;
- 💰 orçamento;
- 👥 equipe;
- 🖥️ tecnologia;
- 📅 prazo;
- 📦 escopo.

Por isso, dificilmente todos os requisitos poderão ser desenvolvidos ao mesmo tempo.

A priorização ajuda a responder:

> **O que precisa ser desenvolvido primeiro?**

Ao priorizar, a equipe pode considerar fatores como:

- valor para o negócio;
- necessidade do usuário;
- dependência entre requisitos;
- riscos;
- requisitos implícitos;
- integração com outros sistemas;
- obrigações legais ou regulatórias;
- viabilidade técnica.

---

# 2. O que é a técnica MoSCoW?

A técnica **MoSCoW** é utilizada para organizar requisitos de acordo com sua importância para uma determinada entrega, versão ou *release* do sistema.

O nome **MoSCoW** representa quatro categorias:

| Letra | Categoria | Significado |
|:---:|---|---|
| 🔴 **M** | **Must Have** | Deve ter |
| 🟠 **S** | **Should Have** | Deveria ter |
| 🟢 **C** | **Could Have** | Poderia ter |
| ⚪ **W** | **Won't Have Now** | Não terá agora |

---

# 3. 🔴 M — Must Have

Os requisitos classificados como **Must Have** são indispensáveis para a entrega.

Sem eles, o sistema pode:

- não resolver o problema principal;
- não atender ao objetivo do negócio;
- impedir a execução de uma funcionalidade essencial;
- apresentar riscos críticos;
- descumprir uma obrigação legal ou regulatória;
- impedir o funcionamento de outros requisitos.

### Pergunta-chave

> **Se retirarmos este requisito, a primeira versão do sistema ainda consegue cumprir seu objetivo principal?**

Se a resposta for **não**, provavelmente estamos diante de um **Must Have**.

---

## Exemplo

Considere um sistema acadêmico.

### RF01

> O sistema deve permitir que o estudante consulte suas disciplinas matriculadas.

**Classificação:** 🔴 `M — Must Have`

**Justificativa:** consultar as informações acadêmicas é uma das funcionalidades centrais da solução.

---

# 4. 🟠 S — Should Have

Os requisitos classificados como **Should Have** são muito importantes, mas sua ausência temporária não impede que a primeira versão do sistema seja entregue.

Normalmente:

- agregam bastante valor;
- são importantes para a experiência do usuário;
- podem possuir uma solução alternativa temporária;
- podem ser desenvolvidos em uma próxima versão.

### Pergunta-chave

> **O sistema consegue ser utilizado sem este requisito durante algum tempo?**

Se a resposta for **sim**, ele poderá ser um **Should Have**.

---

## Exemplo

### RF08

> O sistema deve enviar uma notificação ao estudante quando uma nova nota for publicada.

**Classificação:** 🟠 `S — Should Have`

### Justificativa

A notificação melhora a experiência, mas o estudante ainda poderá acessar o sistema e consultar suas notas.

---

# 5. 🟢 C — Could Have

Os requisitos classificados como **Could Have** são desejáveis.

Eles podem:

- melhorar a experiência;
- agregar algum valor;
- aumentar a satisfação;
- diferenciar o produto.

Entretanto, possuem menor impacto sobre o objetivo principal da primeira versão.

### Pergunta-chave

> **Se tivermos tempo e recursos adicionais, seria interessante implementar este requisito?**

Se a resposta for **sim**, provavelmente estamos diante de um **Could Have**.

---

## Exemplo

### RF12

> O sistema deve permitir que o estudante personalize a imagem do seu perfil.

**Classificação:** 🟢 `C — Could Have`

### Justificativa

A personalização pode melhorar a experiência do usuário, mas não é necessária para realizar as atividades acadêmicas principais.

---

# 6. ⚪ W — Won't Have Now

Os requisitos classificados como **Won't Have Now** não serão implementados na versão atual.

Isso **não significa que o requisito foi descartado definitivamente**.

Ele poderá ser considerado em uma versão futura.

Alguns motivos:

- falta de tempo;
- orçamento limitado;
- alta complexidade;
- dependência de outras funcionalidades;
- necessidade de maior investigação;
- risco tecnológico;
- baixo valor para a versão atual.

### Pergunta-chave

> **Podemos deixar este requisito para uma versão futura sem comprometer o objetivo da primeira entrega?**

---

## Exemplo

### RF15

> O sistema deve disponibilizar um assistente baseado em Inteligência Artificial para recomendar disciplinas aos estudantes.

**Classificação:** ⚪ `W — Won't Have Now`

### Justificativa

A funcionalidade exige maior investigação, dados, infraestrutura e recursos tecnológicos.

Ela poderá ser planejada para uma versão futura.

---

# 7. Comparando as quatro categorias

| Categoria | Importância | Entra na primeira versão? | Consequência de retirar |
|---|---|:---:|---|
| 🔴 **Must** | Essencial | ✅ Sim | Compromete a entrega |
| 🟠 **Should** | Muito importante | Preferencialmente | Impacto relevante, mas administrável |
| 🟢 **Could** | Desejável | Se houver recursos | Pequeno impacto |
| ⚪ **Won't** | Futuro | ❌ Não | Sem impacto crítico nesta versão |

---

# 8. Como aplicar a técnica MoSCoW

O grupo deverá analisar **cada requisito levantado**.

Para cada requisito, sigam os passos abaixo.

---

## Passo 1 — Analisar o valor

Perguntem:

> **Quanto valor este requisito entrega ao usuário ou ao negócio?**

Requisitos que entregam grande valor podem receber prioridade maior.

---

## Passo 2 — Analisar a necessidade

Perguntem:

> **O sistema consegue cumprir seu objetivo principal sem este requisito?**

Se não consegue, existe um forte indicativo de **Must Have**.

---

## Passo 3 — Identificar dependências

Perguntem:

> **Existem outros requisitos que dependem deste requisito?**

### Exemplo

Para permitir:

> `Realizar compra`

talvez seja necessário anteriormente:

> `Cadastrar usuário`

> `Selecionar produto`

> `Cadastrar endereço`

> `Selecionar forma de pagamento`

Portanto, a priorização precisa considerar as dependências.

---

# 9. Passo 4 — Analisar os riscos

Perguntem:

> **O que acontece se este requisito não for implementado agora?**

Considerem:

- risco financeiro;
- risco operacional;
- risco de segurança;
- risco para o usuário;
- risco legal;
- risco tecnológico.

Quanto maior o impacto, maior poderá ser a prioridade.

---

# 10. Passo 5 — Verificar obrigações

Alguns requisitos podem estar associados a:

- legislação;
- regulamentações;
- contratos;
- políticas institucionais;
- regras obrigatórias de negócio.

Perguntem:

> **Existe alguma obrigação que torne este requisito indispensável?**

Se existir, ele poderá precisar ser classificado como **Must Have**.

---

# 11. Passo 6 — Avaliar a viabilidade

Perguntem:

> **É possível implementar este requisito com o tempo, orçamento, equipe e tecnologia disponíveis?**

Um requisito pode entregar muito valor e, mesmo assim, ser inviável para a primeira versão.

Nesse caso, a equipe deverá discutir se ele deve ser:

- simplificado;
- dividido;
- adiado;
- transferido para outra versão.

---

# 12. Exemplo completo

Considere um projeto para desenvolver um:

## 🏥 Sistema de Agendamento de Consultas

Após o levantamento de requisitos, a equipe identificou:

| ID | Requisito | MoSCoW | Justificativa |
|---|---|:---:|---|
| RF01 | Cadastrar paciente | 🔴 M | Necessário para identificar o paciente |
| RF02 | Consultar horários disponíveis | 🔴 M | Essencial para realizar o agendamento |
| RF03 | Agendar consulta | 🔴 M | Funcionalidade principal |
| RF04 | Cancelar consulta | 🔴 M | Necessário para liberar horários |
| RF05 | Enviar confirmação por e-mail | 🟠 S | Importante, mas existe alternativa |
| RF06 | Enviar lembrete da consulta | 🟠 S | Pode reduzir faltas |
| RF07 | Personalizar foto do perfil | 🟢 C | Melhora a experiência |
| RF08 | Recomendar médicos utilizando IA | ⚪ W | Pode ser planejado para uma versão futura |

---

# 13. Atenção aos Requisitos de Qualidade

A técnica MoSCoW não deve ser aplicada apenas aos requisitos funcionais.

Os **requisitos de qualidade também precisam ser priorizados**.

Por exemplo:

### RQ01 — Segurança

> O sistema deve bloquear a conta após cinco tentativas consecutivas de autenticação inválida.

Dependendo do contexto:

**Classificação:** 🔴 `Must Have`

---

### RQ02 — Desempenho

> O sistema deve responder às consultas em até 2 segundos para 95% das requisições.

Dependendo da criticidade:

**Classificação:** 🔴 `Must Have`

ou

**Classificação:** 🟠 `Should Have`

---

# 14. ⚠️ Cuidado: "Tudo é Must"

Um erro comum durante a priorização é afirmar:

> **"Todos os requisitos são importantes. Portanto, todos são Must."**

Se tudo possui prioridade máxima, **não existe priorização**.

Para cada **Must**, o grupo deve conseguir responder:

> **Por que este requisito obrigatoriamente precisa estar na primeira versão?**

E também:

> **O que aconteceria se ele fosse retirado?**

---

# 15. Atividade do grupo

Agora a equipe deverá aplicar a técnica MoSCoW aos requisitos levantados no projeto.

Preencham a matriz:

| ID | Requisito | M | S | C | W | Justificativa |
|---|---|:---:|:---:|:---:|:---:|---|
| RF01 | | ☐ | ☐ | ☐ | ☐ | |
| RF02 | | ☐ | ☐ | ☐ | ☐ | |
| RF03 | | ☐ | ☐ | ☐ | ☐ | |
| RF04 | | ☐ | ☐ | ☐ | ☐ | |
| RF05 | | ☐ | ☐ | ☐ | ☐ | |
| RF06 | | ☐ | ☐ | ☐ | ☐ | |
| RF07 | | ☐ | ☐ | ☐ | ☐ | |
| RF08 | | ☐ | ☐ | ☐ | ☐ | |
| RQ01 | | ☐ | ☐ | ☐ | ☐ | |
| RQ02 | | ☐ | ☐ | ☐ | ☐ | |
| RQ03 | | ☐ | ☐ | ☐ | ☐ | |
| RQ04 | | ☐ | ☐ | ☐ | ☐ | |
| RQ05 | | ☐ | ☐ | ☐ | ☐ | |

---

# 16. Definindo a primeira versão do sistema

Depois da classificação, imaginem a seguinte situação:

> 🚨 **A equipe acaba de descobrir que terá apenas metade do tempo inicialmente previsto para desenvolver a primeira versão do sistema.**

O grupo deverá revisar sua classificação.

---

## Parte A — O que permanece?

Selecionem apenas **5 requisitos indispensáveis**.

| Ordem | ID | Requisito | Por que precisa permanecer? |
|:---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |
| 4 | | | |
| 5 | | | |

---

## Parte B — O que pode esperar?

Selecionem **3 requisitos que podem ser transferidos para uma versão futura**.

| ID | Requisito | Impacto de adiar |
|---|---|---|
| | | |
| | | |
| | | |

---

# 17. Desafio — Definindo o MVP

Agora observem apenas os requisitos classificados como **Must Have**.

Perguntem:

> **Com esses requisitos conseguimos entregar uma primeira versão que resolva o problema principal do usuário?**

Se a resposta for **não**, revisem a priorização.

Se a resposta for **sim**, vocês possuem um primeiro conjunto de requisitos candidatos à entrega inicial.

---

# 18. Checklist MoSCoW

Antes de finalizar, verifiquem:

- [ ] Todos os requisitos possuem uma prioridade?
- [ ] Cada requisito possui apenas uma classificação?
- [ ] Os requisitos Must são realmente indispensáveis?
- [ ] Existe uma justificativa para cada prioridade?
- [ ] O grupo considerou valor para o negócio?
- [ ] O grupo considerou as necessidades dos stakeholders?
- [ ] Foram analisadas dependências?
- [ ] Foram analisados riscos?
- [ ] Foram consideradas obrigações legais ou regulatórias?
- [ ] Requisitos de qualidade também foram priorizados?
- [ ] Existem requisitos classificados como Could ou Won't?
- [ ] O grupo consegue explicar o impacto de retirar cada Must?
- [ ] A primeira versão é viável considerando as restrições do projeto?

---

# 19. Reflexão do grupo

Respondam:

### 1. Qual requisito foi mais difícil de priorizar? Por quê?

**Resposta:**

---

### 2. Houve algum requisito inicialmente considerado Must que mudou de prioridade?

**Resposta:**

---

### 3. Qual requisito gerou maior divergência entre os integrantes?

**Resposta:**

---

### 4. O que aconteceria se todos os requisitos fossem classificados como Must?

**Resposta:**

---

### 5. Quais requisitos formariam a primeira versão do sistema?

**Resposta:**

---

# 20. Take Away

> ## 🔴 Must
> Sem ele, a entrega não cumpre seu objetivo.

> ## 🟠 Should
> É muito importante, mas pode esperar temporariamente.

> ## 🟢 Could
> É desejável se houver tempo e recursos.

> ## ⚪ Won't
> Não será desenvolvido nesta entrega.

---

# 💡 Regra de ouro

**Priorizar não significa simplesmente decidir quais requisitos são importantes.**

Priorizar significa decidir:

> **O que deve ser entregue primeiro para gerar o maior valor possível dentro das restrições do projeto?**

---

## 📚 Material de apoio

REINEHR, Sheila. **Requisitos de Software.** Material da disciplina Engenharia de Requisitos.

O material de estudo aborda:

- classificação dos requisitos;
- requisitos funcionais;
- requisitos de qualidade;
- restrições;
- priorização;
- critérios de qualidade dos requisitos;
- documentação e verificação dos requisitos.

---

## 📦 Entregável do grupo

Ao final da aplicação da técnica MoSCoW, o grupo deverá possuir:

- requisitos classificados em **Must, Should, Could e Won't**;
- justificativa para a priorização;
- identificação das dependências;
- seleção dos requisitos essenciais;
- definição do conjunto de requisitos da primeira versão do sistema.

---

**Disciplina:** Engenharia de Requisitos  
**Atividade:** Projeto de Engenharia de Requisitos  
**Tema:** Priorização de Requisitos com MoSCoW
