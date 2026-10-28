# Requisitos e Regras do Sistema

Guia direto e simplificado do que o sistema precisa ter e como ele funciona.

---

## 1. O que vai no Cadastro da Demanda?

Ao cadastrar uma nova demanda, os campos são:

| Campo | Obrigatório? | O que é? |
| :--- | :---: | :--- |
| **Data** | Sim | Data em que a demanda chegou. |
| **Descrição** | Sim | Resumo do que precisa ser feito. |
| **Origem** | Sim | Se veio de fora (Externa) ou de dentro do IPEM (Interna). |
| **Destinatários** | Sim | Quem ou qual setor precisa receber/saber dessa demanda. |
| **Processo SEI** | Não | Número do processo no SEI (se já existir). |
| **Processo Interno** | Não | Número de controle interno (se houver). |
| **Prazo Final** | Não | Data limite para responder ou resolver. |
| **Tipo Cíclico** | Não | Se é uma demanda anual do Estado (PPA, LOA, LDO). |

---

## 2. Como a demanda anda no Quadro (Kanban)?

As demandas ficam em colunas visuais:

1. **Recebida:** A demanda acabou de entrar no sistema.
2. **Em triagem:** O responsável está avaliando o que fazer e quem vai fazer.
3. **Em execução:** A equipe está trabalhando para resolver a demanda.
4. **Em validação:** O trabalho foi feito e está com o Checador para conferir.
5. **Respondida:** A resposta oficial já foi enviada (ex: ofício ou memorando no SEI).
6. **Encerrada:** Demanda 100% finalizada e arquivada.

---

## 3. Regras Principais (Como o trabalho funciona)

- **Todo mundo pode mover cartões:** Qualquer usuário pode arrastar o cartão para a coluna certa no dia a dia. Isso **não** muda quem é o responsável pela demanda.
- **Só o dono decide a execução:** Apenas o *Destinatário Original* pode trocar quem é o executor e concluir a demanda.
- **Demandas só de "Ciência":** Se uma demanda for apenas para os servidores tomarem conhecimento, ela se encerra automaticamente assim que todos os destinatários confirmarem ciência.
- **Checagem antes de fechar:** O *Checador* indicado analisa o que foi feito. Se estiver bom, aprova. Se faltar algo, devolve para ajustes.
- **Tarefas são opcionais:** Se for algo simples e rápido, não precisa criar várias subtarefas.

---

## 4. Planejamento das Tarefas (5W2H e PDCA)

Para demandas maiores, o responsável pode dividir a demanda em tarefinhas usando o **5W2H**:
- **O quê (What):** O que tem que fazer.
- **Quem (Who):** Quem vai fazer.
- **Quando (When):** Prazo da tarefa (deve ser antes do prazo final da demanda).
- **Por quê (Why):** Motivo.
- **Onde (Where):** Local ou setor.
- **Como (How):** Como deve ser feito.
- **Quanto custa (How much):** Custo ou recursos (se houver).

Tudo isso segue o ciclo natural **PDCA**:  
**Planejar** a tarefa ➔ **Executar** o trabalho ➔ **Checar** o resultado ➔ **Concluir** ou **Ajustar**.

---

## 5. Demandas Cíclicas

O sistema terá uma marcação fácil para demandas recorrentes do orçamento e planejamento do Estado:
- **PPA** (Plano Plurianual)
- **LDO** (Diretrizes Orçamentárias)
- **LOA** (Orçamento Anual)
