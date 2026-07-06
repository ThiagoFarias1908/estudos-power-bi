# 📊 Power BI & DAX: Projetos e Biblioteca de Medidas

<p align="left">
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/DAX-025E8C?style=for-the-badge&logo=microsoft&logoColor=white" alt="DAX">
</p>

## 📌 Sobre o Repositório
Este repositório é a minha base de conhecimento pessoal e portfólio focado em **Power BI** e modelagem de dados. Ele contém desde a documentação de fórmulas **DAX** aplicadas a cenários reais de negócios até projetos completos de Business Intelligence.

O objetivo é demonstrar proficiência em extração de *insights*, inteligência temporal, análise de performance (KPIs) e resolução de problemas analíticos.

## 📂 Estrutura
- 🧮 **Medidas (DAX):** Biblioteca documentada com fórmulas essenciais e avançadas categorizadas por contexto de negócio.
- 🗄️ **Datasets:** Bases de dados brutas e tratadas utilizadas nas análises.
- 🚀 **Projetos:** Dashboards e cases de negócios de ponta a ponta.

---

## 🚀 Projetos e Casos de Uso
*Casos práticos aplicando modelagem dimensional, DAX avançado e Data Storytelling.*

| Projeto | Descrição | Status |
| :--- | :--- | :--- |
| **Dashboard BikeStores** | *Desenvolvimento ponta a ponta com foco em UX/UI e análise de vendas.* | ✅ Concluído |

---

## 🧮 Biblioteca de Medidas DAX (Base de Conhecimento)

Clique nas categorias abaixo para expandir e explorar as medidas documentadas:

<details>
<summary><b> 📦 Medidas Gerais (Vendas e Pedidos)</b></summary>
<br>

1. [Sales](Medidas/01%20Sales.md): Calcula o total das vendas.
2. [Sales AVG](Medidas/02%20Sales%20AVG.md): Calcula a média das vendas.
3. [Orders Quantity](Medidas/03%20Orders%20Quantity.md): Conta o número total de pedidos.
4. [Distinct Orders Quantity](Medidas/04%20Distinct%20Orders%20Quantity.md): Calcula a quantidade distinta de pedidos.
5. [Sales AVG com Divide](Medidas/05%20Sales%20AVG%20com%20Divide.md): Calcula a média das vendas evitando divisão por zero.
6. [Sales AVGX](Medidas/06%20Sales%20AVGX.md): Média ponderada considerando apenas receitas > 0.
7. [Sales SUMX](Medidas/07%20Sales%20SUMX.md): Total de vendas usando SUMX.
8. [Orders Quantity with revenue < 0](Medidas/08%20Orders%20Quantity%20with%20revenue%20<%200.md): Pedidos com receita negativa.
9. [CALCULATE + ALL](Medidas/09%20CALCULATE%20%2B%20ALL.md): Receita líquida total ignorando filtros.
10. [Porcetagem Categoria](Medidas/10%20Porcetagem%20Categoria.md) / [Porcetagem Ano](Medidas/11%20Porcentagem%20Ano.md): Participação percentual de vendas.
11. [Sales Total Category (Diversos)](Medidas/12%20Sales%20Total%20Category.md): Cálculos de vendas segmentados por categoria (incluindo ALL e ALLSELECTED).
12. [Sales Sorocaba](Medidas/21%20Sales%20Sorocaba.md): Filtragem de vendas por localidade.
13. [Funções de Tabela e Variáveis](Medidas/23%20ADDCOLUMNS.md): Uso de `ADDCOLUMNS`, `CROSSJOIN`, `SUMMARIZE`, `SELECTEDVALUE` e `USERELATIONSHIP`.

</details>

<details>
<summary><b> ⏳ Inteligência Temporal (Time Intelligence)</b></summary>
<br>

1. [Sales Last Month](Medidas%20Inteligência%20Temporal/02%20Sales%20Last%20Month.md): Vendas do mês anterior.
2. [Sales Last Month Delta / %](Medidas%20Inteligência%20Temporal/03%20Sales%20Last%20Month%20Delta.md): Variação nominal e percentual vs Mês Anterior (MoM).
3. [Sales Month over Month (MoM)](Medidas%20Inteligência%20Temporal/05%20Sales%20Month%20over%20Month.md): Vendas do mesmo mês no ano anterior.
4. [Sales Last Year (YoY)](Medidas%20Inteligência%20Temporal/08%20Sales%20Last%20Year.md): Vendas totais do ano anterior.
5. [Year to Date (YTD) e MTD](Medidas%20Inteligência%20Temporal/11%20Sales%20Year%20to%20Date.md): Vendas acumuladas no ano/mês e suas variações vs períodos passados.

</details>

<details>
<summary><b> 🚚 Delivery e Logística</b></summary>
<br>

1. [Deliveries](Medidas%20Delivery/01%20Deliveries.md): Número de entregas.
2. [Deliveries On Time / Late](Medidas%20Delivery/01%20Deliveries.md): Entregas no prazo vs atrasadas.
3. [Deliveries On Time % (OTIF)](Medidas%20Delivery/04%20Deliveries%20On%20Time%20%25.md): Percentual de assertividade nas entregas.
4. [Delivery Lead Time](Medidas%20Delivery/05%20Delivery%20Lead%20Time.md): Tempo médio de entrega dos pedidos.

</details>

<details>
<summary><b> 🧠 Análises Analíticas Avançadas (DAX)</b></summary>
<br>

1. [Rank Produto ALL / ALLSELECTED](Medidas%20Análises%20DAX/03%20Rank%20Produto%20ALL.md): Ranqueamento dinâmico e estático de produtos.
2. [Pareto com Ranking](Medidas%20Análises%20DAX/05%20Pareto%20com%20Ranking.md): Curva ABC (percentual acumulado) para análise de relevância de faturamento e volume.
3. [Ticket Médio (Sales unit)](Medidas%20Análises%20DAX/07%20Sales%20unit.md): Valor médio de venda unitária, variação anual (LY) e impacto financeiro.

</details>

<details>
<summary><b> ⚙️ Medidas Auxiliares</b></summary>
<br>

1. [Actual Year / Last Year](Medidas%20Auxiliares/01%20Actual%20Year.md): Retorno de contexto de datas selecionadas.
2. [Sales Last Date](Medidas%20Auxiliares/03%20Sales%20Last%20Date.md): Identificação do último dia com faturamento registrado.

</details>

<br>

---
*Desenvolvido para documentar a evolução contínua em Business Intelligence e DAX.*
