# User Stories — Sistema de Ocorrências Urbanas - UrbanReporter

> **Legenda:**  
> - **SP (Story Point):** estimativa de complexidade definida durante o Planning Poker.  
> - **Prioridade:** definida usando o método MoSCoW (Must have; Should have; Could have; Won't have)

---

## US01 — Registrar ocorrência urbana

**Como** cidadão,  
**desejo** registrar ocorrências relacionadas a problemas de infraestrutura pública,  
**para** contribuir para a melhoria da vivência cotidiana e informar o poder público sobre problemas existentes.

- **SP:** 5
- **Prioridade:** M

### Critérios de aceitação

1. O sistema deve permitir que o cidadão registre uma ocorrência informando, no mínimo, **descrição do problema e localização**.
2. Após o registro, o sistema deve **confirmar o envio da ocorrência** e disponibilizar um identificador para que ela possa ser posteriormente consultada.

---

## US02 — Visualizar ocorrências urbanas

**Como** cidadão,  
**desejo** visualizar as ocorrências urbanas registradas por outros cidadãos de forma visual e organizada,  
**para** identificar problemas existentes e evitar inconveniências em determinadas regiões.

- **SP:** 8
- **Prioridade:** C

### Critérios de aceitação

1. O sistema deve apresentar as ocorrências de maneira **visual, preferencialmente em um mapa**, permitindo identificar sua localização.
2. O cidadão deve poder **consultar os detalhes básicos de uma ocorrência**, como categoria, descrição, localização e situação atual.

---

## US03 — Acompanhar ocorrência registrada

**Como** cidadão,  
**desejo** acompanhar o andamento das ocorrências que registrei,  
**para** fiscalizar as providências tomadas pelo poder público.

- **SP:** 3
- **Prioridade:** M

### Critérios de aceitação

1. O sistema deve permitir que o cidadão consulte suas ocorrências e visualize o **status atual de cada uma**.
2. O sistema deve apresentar as **atualizações de status** realizadas pelos responsáveis pela ocorrência.

---

## US04 — Interagir com ocorrências

**Como** cidadão,  
**desejo** interagir com as solicitações e ocorrências registradas por outros cidadãos,  
**para** demonstrar apoio às demandas e contribuir para a pressão por ações governamentais.

- **SP:** 5
- **Prioridade:** C

### Critérios de aceitação

1. O sistema deve permitir que o cidadão **curta e comente** em outras ocorrências.
2. O sistema deve contabilizar e exibir a quantidade de **curtidas e comentários** recebidos por cada ocorrência.

---

## US05 — Criar conta e realizar login

**Como** cidadão,  
**desejo** criar uma conta e realizar login no sistema,  
**para** manter o registro das ocorrências que enviei e acompanhar seu andamento.

- **SP:** 2
- **Prioridade:** M

### Critérios de aceitação

1. O sistema deve permitir que o cidadão **crie uma conta** informando os dados necessários para sua identificação e autenticação.
2. O sistema deve permitir que o cidadão **realize login e acesse suas ocorrências registradas**.

---

## US06 — Centralizar demandas urbanas

**Como** secretário de infraestrutura,  
**desejo** acessar uma área centralizada para visualizar e gerenciar as demandas urbanas registradas,  
**para** acompanhar as solicitações da população de forma organizada.

- **SP:** 8
- **Prioridade:** S

### Critérios de aceitação

1. O sistema deve disponibilizar ao secretário uma área que apresente **todas as ocorrências registradas** que estejam sob sua responsabilidade.
2. O secretário deve poder **consultar os detalhes e o status** de cada ocorrência a partir dessa área centralizada.

---

## US07 — Identificar tendências de ocorrências

**Como** secretário de infraestrutura,  
**desejo** acompanhar as principais tendências de reclamações e ocorrências registradas pelos cidadãos,  
**para** direcionar recursos limitados de forma mais eficiente.

- **SP:** 5
- **Prioridade:** C

### Critérios de aceitação

1. O sistema deve apresentar **informações filtradas sobre as ocorrências**, como quantidade por categoria, região ou período.
2. O sistema deve permitir identificar **categorias ou regiões com maior concentração de ocorrências**.

---

## US08 — Centralizar ocorrências de fontes externas

**Como** gestor público,  
**desejo** receber e visualizar ocorrências provenientes de fontes externas, como redes sociais e outros canais de comunicação, em um único local,  
**para** ampliar e centralizar a coleta de informações sobre problemas urbanos.

- **SP:** 13
- **Prioridade:** W

### Critérios de aceitação

1. O sistema deve permitir o **recebimento de ocorrências provenientes de fontes externas**, identificando sua origem.
2. As ocorrências externas devem ser **apresentadas junto às demais ocorrências**, mantendo informações que permitam distinguir sua fonte.

---

## US09 — Encaminhar ocorrência para órgão responsável

**Como** gestor público,  
**desejo** encaminhar ocorrências registradas para órgãos ou empresas externas responsáveis pela solução do problema,  
**para** garantir que a demanda seja direcionada ao responsável adequado.

- **SP:** 5
- **Prioridade:** S

### Critérios de aceitação

1. O sistema deve permitir que o gestor **selecione o órgão ou empresa responsável** e encaminhe a ocorrência.
2. Após o encaminhamento, o sistema deve registrar **para qual órgão a ocorrência foi encaminhada e a data do encaminhamento**.

---

## US10 — Consultar situação da ocorrência

**Como** cidadão,  
**desejo** saber se uma ocorrência foi resolvida ou se ainda está em andamento,  
**para** acompanhar a situação da demanda e ter uma percepção sobre a eficiência dos serviços públicos.

- **SP:** 2
- **Prioridade:** M

### Critérios de aceitação

1. O sistema deve apresentar o **status da ocorrência**, indicando se ela está pendente, em andamento ou resolvida.
2. Quando uma ocorrência for marcada como resolvida, o sistema deve **atualizar seu status para "Resolvida"** e disponibilizar essa informação para os cidadãos.

---

## Resumo

| US | Funcionalidade | SP | Prioridade |
|---|---|---:|---|
| **US01** | Registrar ocorrência urbana | 5 | M |
| **US02** | Visualizar ocorrências urbanas | 8 | C |
| **US03** | Acompanhar ocorrência registrada | 3 | M |
| **US04** | Interagir com ocorrências | 5 | C |
| **US05** | Criar conta e realizar login | 2 | M |
| **US06** | Centralizar demandas urbanas | 8 | S |
| **US07** | Identificar tendências de ocorrências | 5 | C |
| **US08** | Centralizar ocorrências de fontes externas | 13 | W |
| **US09** | Encaminhar ocorrência para órgão responsável | 5 | S |
| **US10** | Consultar situação da ocorrência | 2 | M |
