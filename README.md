# 📊 Análise de Evasão de Clientes (Churn) - Telecom X

Este projeto contém uma **análise resumida do índice de evasão de clientes da Telecom X**.  
O objetivo é identificar os principais fatores que levam os clientes a cancelar seus serviços (churn)  
e propor ações estratégicas para melhorar a retenção.

## 📌 Tópicos

- [📊 Análise de Evasão de Clientes (Churn) - Telecom X](#-análise-de-evasão-de-clientes-churn---telecom-x)
  - [📌 Tópicos](#-tópicos)
  - [📈 Visão Geral](#-visão-geral)
  - [📊 Análise Detalhada dos Fatores de Churn](#-análise-detalhada-dos-fatores-de-churn)
  - [📌 Principais Conclusões](#-principais-conclusões)
  - [📈 Recomendações](#-recomendações)
  - [📂 Arquivos](#-arquivos)
  - [🔧 Requisitos](#-requisitos)
  - [🧑‍💼 Autor](#-autor)

---

## 📈 Visão Geral

A análise inicial revela que, do total de clientes, a **maioria não apresentou Churn (5174 clientes)**,  
enquanto **1869 clientes indicaram Churn**.

Este projeto aprofunda-se nos fatores demográficos, contratuais e de uso que influenciam essa taxa de desistência.

## 📊 Análise Detalhada dos Fatores de Churn

Esta seção detalha as observações sobre a distribuição de Churn com base nas variáveis analisadas:

- **Churn por Gênero:** A distribuição de Churn entre gêneros é **muito similar**  
  (939 clientes femininos e 930 clientes masculinos churnaram), sugerindo que o **gênero não é um fator preponderante** para a desistência.

- **Churn por Senioridade (Idoso):** A **proporção de Churn é visivelmente maior entre clientes considerados "Idosos"**  
  (476 churnaram de um grupo menor, comparado a 1393 não idosos que churnaram de um grupo muito maior).

- **Churn por Estado Civil (Parceiro):** Clientes **sem parceiro(a) ('No') churnam em número significativamente maior (1200 clientes)**  
  do que clientes com parceiro(a) ('Yes') (669 clientes), indicando que ter um parceiro(a) pode estar associado a uma **menor propensão a Churn**.

- **Churn por Dependentes:** Clientes **sem dependentes ('No') apresentaram um número consideravelmente maior de Churn (1543 clientes)**  
  em comparação com aqueles que possuem dependentes ('Yes') (326 clientes), sugerindo que a presença de dependentes também pode estar  
  relacionada a uma **menor taxa de desistência**.

- **Churn por Tempo de Contrato (Tenure_faixa):** A **maioria dos eventos de Churn ocorre nos primeiros meses de contrato**,  
  especialmente na faixa de **"0-6 meses"**. Clientes novos são os mais vulneráveis.

- **Churn por Tipo de Contrato:** A **maioria esmagadora dos casos de Churn (1655 clientes) está associada a contratos "Month-to-month" (mês a mês)**.  
  Contratos de um ou dois anos apresentam números de Churn muito menores.

- **Churn por Forma de Pagamento:** A forma de pagamento **"Electronic check" (cheque eletrônico) se destaca com um número expressivamente alto**  
  de clientes que churnaram (1071 clientes).

- **Churn por Faixa de Gasto Mensal (Charges.Monthly):** A **porcentagem de Churn aumenta significativamente para clientes com gastos mensais mais altos**  
  (especialmente nas faixas de R$ 70-79, R$ 80-89 e R$ 90-99), com quase 40% de churn na faixa de R$ 70-79.

- **Churn por Faixa de Gasto Total (Charges.Total):** A **maior taxa de Churn (36.99% e 1070 clientes) ocorre na faixa de menores gastos totais (R$ 0-999)**.  
  À medida que o gasto total aumenta, a porcentagem de Churn diminui drasticamente.

## 📌 Principais Conclusões

Com base na análise, os **principais fatores associados a um alto Churn** são:

- Estar nos **primeiros meses de contrato (0-6 meses)**.
- Ter um **contrato "Month-to-month"**.
- Utilizar **"Electronic check" como método de pagamento**.
- Ter **gastos mensais mais elevados**.
- Ter **menor gasto total acumulado**.
- Fatores como ser **idoso**, **não ter parceiro(a)** ou **não ter dependentes** também indicam uma maior propensão ao Churn.

## 📈 Recomendações

Para mitigar o Churn, as seguintes ações estratégicas podem ser implementadas:

- **Programa de Onboarding Robusto:** Implementar um **programa de onboarding proativo e personalizado** nos primeiros 6 meses de contrato  
  para garantir a satisfação e demonstrar o valor do serviço.

- **Incentivo a Contratos de Longa Duração:** Criar **incentivos claros e atraentes para a migração de contratos "Month-to-month"**  
  para planos anuais ou bianuais, como descontos ou benefícios adicionais.

- **Análise e Otimização do "Electronic Check":** Investigar a causa da correlação entre o uso de **"Electronic check" e o Churn**  
  e **incentivar ativamente a mudança para formas de pagamento automáticas** (transferência bancária ou cartão de crédito).

- **Estratégias de Valor para Clientes de Alto Gasto Mensal:** Para clientes com mensalidades elevadas, focar em **atendimento ao cliente premium ou dedicado**,  
  acesso a **serviços exclusivos** ou **programas de fidelidade de alto nível** para demonstrar o valor agregado.

- **Programas de Retenção Segmentados:** Desenvolver **programas de retenção específicos** para clientes idosos (focando em suporte simplificado)  
  e para aqueles sem parceiro(a) ou dependentes (focando em valor individualizado e flexibilidade).

## 📂 Arquivos

- [`TelecomX_Data.json`](https://raw.githubusercontent.com/alura-cursos/challenge2-data-science/refs/heads/main/TelecomX_Data.json): Base de dados utilizada na análise.
- `TelecomX_BR.ipynb`: Notebook contendo os códigos Python para a análise.
- Outros gráficos e documentos da análise podem ser adicionados aqui conforme o projeto avança.

## 🔧 Requisitos

Nenhum requisito técnico necessário para visualização do conteúdo.  
O relatório principal está em formato PDF.

## 🧑‍💼 Autor

Relatório preparado por João Costa, para fins educacionais.
