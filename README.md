# 🚚 Dashboard de Gestão Logística

Projeto de análise e acompanhamento de operações logísticas desenvolvido com Excel e Power BI.

A solução foi estruturada para acompanhar o fluxo dos romaneios desde a separação até a expedição, permitindo visualizar indicadores operacionais, produtividade, transportadoras e distribuição das cargas.

---

## 🎯 Objetivo

Desenvolver uma ferramenta de acompanhamento da operação logística, centralizando informações de romaneios e transformando os dados operacionais em indicadores e análises visuais.

O projeto busca facilitar o acompanhamento da operação e permitir uma visão mais clara sobre:

- Volume de romaneios
- Quantidade de volumes
- Peso movimentado
- Status da operação
- Produtividade da separação e conferência
- Desempenho das transportadoras
- Distribuição das cargas por estado e região
- Acompanhamento diário da operação

---

## 🛠️ Tecnologias utilizadas

- **Excel** — estruturação e organização dos dados operacionais
- **VBA** — automação de rotinas no ambiente Excel
- **Power BI** — criação dos dashboards e análises
- **DAX** — criação de medidas e indicadores
- **Análise de dados** — tratamento, cruzamento e interpretação das informações
- **KPIs logísticos** — acompanhamento de indicadores operacionais

---

## 🗂️ Estrutura dos dados

A base principal é organizada em uma estrutura de acompanhamento de romaneios.

### Linha Mestre

A tabela principal contém informações como:

- Romaneio
- Data
- Status
- Separador
- Conferente
- Expedidor
- Transportadora
- Volumes
- Peso
- Início da operação
- Fim da operação
- Tempo total
- Situação final
- Estado

### Eventos

Também existe uma estrutura de eventos operacionais contendo informações de:

- Data e hora
- Romaneio
- Setor
- Usuário
- Conferente
- Status
- Volumes
- Peso
- Transportadora
- Estado

Essa estrutura permite acompanhar diferentes etapas da operação e utilizar os dados para análises no Power BI.

---

## 📊 Indicadores

O dashboard apresenta indicadores relacionados a:

- Total de romaneios
- Total de volumes
- Romaneios separados
- Romaneios conferidos
- Romaneios expedidos
- Romaneios pendentes
- Produtividade por separador
- Produtividade por conferente
- Volumes movimentados
- Distribuição por transportadora
- Distribuição por estado
- Distribuição por região

---

## 📈 Estrutura do Dashboard

O projeto foi dividido em diferentes páginas para facilitar a análise.

### Dashboard Executivo

Visão geral da operação com indicadores de:

- Romaneios
- Separações
- Conferências
- Expedições
- Volumes
- Transportadoras
- Evolução ao longo do período

### Mapa & Distribuição

Análise da distribuição das cargas por:

- Estado
- Região
- Transportadora
- Quantidade de volumes
- Cobertura geográfica

### Detalhamento por Região

Permite aprofundar a análise de uma determinada região, apresentando:

- Estados atendidos
- Transportadoras
- Volumes
- Romaneios
- Volume médio
- Evolução por período

### Consulta Diária

Página destinada ao acompanhamento operacional diário, permitindo consultar informações de:

- Romaneio
- Data
- Volumes
- Transportadora
- Separador
- Conferente
- Status

### Produtividade

Análise do desempenho operacional, incluindo:

- Romaneios por separador
- Volumes por separador
- Romaneios por conferente
- Volumes por conferente
- Comparação de produtividade

### Detalhamento

Permite consultar informações individuais dos romaneios e seus respectivos dados operacionais.

---

## 🔎 Análises realizadas

O projeto permite transformar os dados operacionais em análises como:

### Operação

Acompanhamento da quantidade de romaneios e volumes movimentados ao longo do período.

### Status

Monitoramento do fluxo dos romaneios entre as etapas de separação, conferência e expedição.

### Transportadoras

Comparação da quantidade de romaneios e volumes movimentados por transportadora.

### Produtividade

Análise da quantidade de romaneios e volumes processados por cada operador.

### Distribuição geográfica

Identificação dos estados e regiões atendidos pela operação.

### Análise temporal

Acompanhamento da evolução da operação por data e período.

---

## 💡 Aplicação prática

O projeto demonstra como dados operacionais podem ser transformados em informações para acompanhamento de desempenho e apoio à tomada de decisão.

A utilização de indicadores, filtros, detalhamentos e análises por diferentes dimensões permite uma visão mais completa da operação logística.

---

## 🖥️ Visualização

### Dashboard Executivo

> Imagem do dashboard será adicionada aqui.

### Mapa e Distribuição

> Imagem do dashboard será adicionada aqui.

### Produtividade

> Imagem do dashboard será adicionada aqui.

---

## 👨‍💻 Projeto de Portfólio

Projeto desenvolvido com foco em **análise de dados aplicada à logística**, utilizando dados operacionais para construção de indicadores, dashboards e análises de desempenho.

**Tecnologias:** Excel | VBA | Power BI | DAX | Análise de Dados
