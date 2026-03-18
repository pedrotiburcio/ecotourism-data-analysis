# 📊 Análise de Dados no Setor de Ecoturismo

Este projeto apresenta uma análise de dados focada no **desempenho financeiro, comportamento de clientes e sustentabilidade de ofertas no setor de ecoturismo**.

A análise foi desenvolvida utilizando **SQL para exploração e tratamento de dados** e **Power BI para construção de dashboards interativos**, permitindo identificar padrões de receita, comportamento de clientes e adoção de práticas sustentáveis.

---

## 🎯 Objetivos da análise

- Analisar a **evolução da receita ao longo do tempo**
- Identificar diferenças de comportamento entre **clientes novos e recorrentes**
- Avaliar **ticket médio e taxa de fidelização**
- Entender a **popularidade das ofertas**
- Investigar o nível de **adoção de práticas sustentáveis**

---

## 🛠️ Ferramentas utilizadas

- **SQL (BigQuery)** — exploração e consultas analíticas  
- **Power BI** — visualização de dados e construção de dashboards  
- **GitHub** — organização e documentação do projeto  

---

## 🧩 Modelo de Dados

O modelo de dados foi estruturado no Power BI com base nas entidades de reservas, ofertas, clientes, operadores e práticas sustentáveis, permitindo a análise de receita, comportamento de clientes, avaliações e adoção de práticas sustentáveis.

Principais tabelas do modelo:

- **reservas** — registros das reservas realizadas na plataforma  
- **ofertas** — experiências disponíveis para reserva  
- **clientes** — informações dos clientes  
- **operadores** — empresas responsáveis pelas ofertas  
- **avaliacoes** — avaliações feitas pelos clientes  
- **praticas_sustentaveis** — práticas ambientais adotadas  
- **oferta_pratica** — tabela ponte entre ofertas e práticas sustentáveis  
- **atividades** — informações específicas das ofertas do tipo atividade  
- **hospedagens** — informações específicas das ofertas do tipo hospedagem  
- **calendario** — suporte para análises temporais  

A tabela **reservas** concentra os registros transacionais do processo de reserva, enquanto **ofertas** descreve as experiências disponíveis na plataforma.

![Modelo de Dados](images/modelo_dados.png)

---

## 📊 Dashboards

O projeto contém dois dashboards principais:

### 1️⃣ Desempenho Financeiro e Mercado

Analisa métricas relacionadas à receita e comportamento de clientes.

**Principais indicadores:**

- Receita total  
- Crescimento mensal  
- Ticket médio  
- Taxa de fidelização  
- Receita por tipo de oferta  
- Receita por tipo de cliente  

<p align="center"><br/>
  <img src="images/dashboard_financeiro.png" width="800">
  <br>
  <em>Dashboard 1: Análise de desempenho financeiro, evolução da receita e comportamento de clientes.</em>
</p>

---

### 2️⃣ Qualidade da Experiência e Sustentabilidade

Explora a relação entre experiência dos clientes e práticas sustentáveis.

**Principais indicadores:**

- Avaliação média das ofertas  
- Popularidade por tipo de oferta  
- Adoção de práticas sustentáveis  
- Desempenho por categoria de oferta  

<p align="center"><br/>
  <img src="images/dashboard_experiencia.png" width="800">
  <br>
  <em>Dashboard 2: Análise da experiência dos clientes, popularidade das ofertas e práticas sustentáveis.</em>
</p>

---

## 📂 Estrutura do repositório

Esta estrutura organiza os principais componentes do projeto: o arquivo do dashboard, as consultas SQL utilizadas na análise e as imagens utilizadas na documentação.

```text
projeto-analise-ecoturismo/
│
├── dashboard
│ └── ecoturismo_dashboard.pbix
│
├── sql
│ └── analise_ecoturismo.sql
│
├── images
│ ├── dashboard_financeiro.png
│ ├── dashboard_sustentabilidade.png
│ └── modelo_dados.png
│
└── README.md
 ```
## 🔎 Principais insights da análise

- A plataforma gerou aproximadamente **R$ 663 mil em receita**, com **ticket médio de R$ 276 por reserva**.  
- **Hospedagens concentram a maior parte da receita**, além de apresentar ticket médio superior às atividades.  
- A **taxa de fidelização é de 23,3%**, indicando potencial para estratégias de retenção.  
- **67,5% das ofertas adotam práticas sustentáveis**, reforçando o alinhamento com o conceito de **ecoturismo**.

## 🔗 Acesse o dashboard

[Visualizar no Power BI](https://app.powerbi.com/view?r=eyJrIjoiM2I3YmI4ZWEtMTlmYy00M2NlLWJkOGUtNTZhNDU5NDk4NDBmIiwidCI6ImRhYjgyMzM0LTU2YzctNDIxMy1hZGQyLTRhMjJjMjgyMzYxYyJ9)
