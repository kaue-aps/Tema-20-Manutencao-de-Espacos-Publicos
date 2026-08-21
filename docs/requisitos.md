# Especificação de Requisitos


**Legenda:**  
> - **USxx(user stories):** histórias do usuário com os casos de uso do software e o seu número de identificação.  
> - **Prioridade:** definida usando o método MoSCoW (Must have; Should have; Could have; Won't have)

---

## Requisitos Funcionais (RF)

| Identificador | Descrição | Prioridade | Requisitos Relacionados |
| :--- | :--- | :--- | :--- |
| **RF01** | O sistema deve permitir o registro de ocorrências urbanas informando descrição e localização, gerando um número de protocolo. | Must Have | US01, RF03, RF05, RNF01, RNF04 |
| **RF02** | O sistema deve exibir as ocorrências cadastradas em um mapa interativo com seus detalhes básicos e situação atual. | Could Have | US02, RF01, RNF01, RNF05 |
| **RF03** | O sistema deve permitir que o cidadão acompanhe o histórico e as atualizações das ocorrências registradas por ele. | Must Have | US03, RF01, RF05, RF10, RNF04 |
| **RF04** | O sistema deve permitir que os cidadãos curtam e comentem em ocorrências de terceiros, exibindo o acumulado das interações. | Could Have | US04, RF02, RF05, RNF05 |
| **RF05** | O sistema deve permitir a criação de conta e o login de cidadãos para autenticação e acesso às suas ocorrências. | Must Have | US05, RF01, RF03, RNF02 |
| **RF06** | O sistema deve disponibilizar uma área centralizada para o secretário visualizar e gerenciar as demandas sob sua responsabilidade. | Should Have | US06, RF01, RF09, RNF01, RNF02 |
| **RF07** | O sistema deve permitir a filtragem de ocorrências por categoria, região e período para a identificação de tendências. | Could Have | US07, RF02, RF06 |
| **RF08** | O sistema deve receber e exibir ocorrências provenientes de redes sociais e canais externos, identificando a fonte de origem. | Won't Have | US08, RF02, RF06, RNF03 |
| **RF09** | O sistema deve permitir o encaminhamento de ocorrências para órgãos ou empresas responsáveis, registrando o destinatário e a data. | Should Have | US09, RF06, RF10, RNF04 |
| **RF10** | O sistema deve atualizar e exibir a situação da ocorrência entre pendente, em andamento e resolvida. | Must Have | US10, RF01, RF03, RF09, RNF04 |

---

## Requisitos Não-Funcionais (RNF)

| Identificador | Descrição | Prioridade | Requisitos Relacionados |
| :--- | :--- | :--- | :--- |
| **RNF01** | O sistema deve apresentar interface geoespacial acessível e intuitiva para navegação em mapas interativos. | Could Have | RF01, RF02, RF06 |
| **RNF02** | O sistema deve implementar autenticação segura e controle de acesso baseado em perfis (Cidadão, Secretário e Gestor). | Must Have | RF05, RF06, RF09 |
| **RNF03** | O sistema deve prover APIs de integração para captura automática de dados externos e envio a órgãos parceiros. | Won't Have | RF08, RF09 |
| **RNF04** | O sistema deve manter registro histórico auditável com data e hora de todas as alterações de status e encaminhamentos. | Must Have | RF01, RF03, RF09, RF10 |
| **RNF05** | O sistema deve manter o tempo de resposta adequado durante a renderização do mapa e interações simultâneas. | Could Have | RF02, RF04 |