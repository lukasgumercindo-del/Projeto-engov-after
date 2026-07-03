# Projeto-engov-after

# 📊 Inteligência de Mercado: Análise Exploratória de Vendas — Engov After (2020-2026)

Como identificar quais produtos realmente carregam o faturamento de uma marca e quais dominam em volume de distribuição, ao longo de um histórico de mais de 5 anos? 

Este projeto foi desenvolvido para analisar o comportamento comercial e a performance de vendas da linha **Engov After** entre os anos de 2020 e 2026. Utilizando técnicas avançadas de **Análise Exploratória de Dados (EDA)**, transformei um histórico bruto de transações em um diagnóstico visual estratégico, revelando os verdadeiros produtos campeões da marca em receita e em volume.

---

## 🛠️ O Arsenal Técnico
Para garantir uma análise escalável, performática e altamente visual, construí o projeto utilizando:

* **Linguagem Principal:** Python 3 (executado em ambiente interativo no VS Code).
* **Manipulação de Dados & Regras de Negócio:** `pandas` (essencial para agrupamentos complexos, agrupamentos por períodos e cálculos de participação de mercado).
* **Data Visualization & Storytelling:** `plotly.express` (escolhido especificamente para gerar gráficos dinâmicos e interativos, permitindo inspecionar cada barra e ponto de dado detalhadamente).

---

## 📉 O Cenário de Negócio
No mercado de bens de consumo de giro rápido, entender o mix de produtos é vital. Nem sempre o produto que mais vende em quantidade é o que traz mais margem ou faturamento para a empresa. 

O objetivo principal desta análise foi cruzar o volume de vendas com o faturamento gerado por SKU (unidade de estoque), entregando para a gerência de produto uma visão clara de:
1. Quais SKUs são as "âncoras" financeiras da marca.
2. Como as vendas se comportaram sazonalmente ao longo da janela histórica de 2020 a 2026.
3. Quais produtos têm maior apelo de volume físico versus apelo de receita.

---

## 🔬 O que a Análise Exploratória me revelou?

### 1. Desempenho do Mix (SKUs Campeãs)
Ao agrupar e ordenar as métricas utilizando o Pandas (`df.groupby().agg()`), foi possível isolar os produtos por relevância:
* **Líderes de Faturamento:** Identificação dos sabores/embalagens que representam a maior fatia da receita da marca (crucial para estratégias de trade marketing e alocação de verba).
* **Líderes de Volume:** Mapeamento de quais SKUs têm maior giro logístico, ajudando a prever demandas de estoque e abastecimento de canais de distribuição.

### 2. Storytelling Visual com Plotly
Em vez de gráficos estáticos comuns, a escolha pelo **Plotly Express** permitiu criar uma experiência onde o usuário final pode interagir com os dados:
* Gráficos de barras interativos comparando Faturamento vs. Volume por SKU.
* Análise de tendência temporal, mostrando o crescimento ou estabilização da linha Engov After ao longo dos anos mapeados (2020-2026).

---

## 🤫 Nota de Confidencialidade (LGPD & Compliance)
*Os dados brutos utilizados nesta análise contêm informações estratégicas simuladas e mascaradas. Valores exatos e nomes específicos de clientes/distribuidores foram preservados e modificados de acordo com as diretrizes de compliance e segurança da informação, mantendo, contudo, a perfeita lógica estatística e o comportamento real de mercado para fins corporativos e de portfólio.*

---

## 🚀 Próximos Passos Sugeridos para a Marca
Com base nos padrões encontrados no notebook:
1. **Foco no Mix Rentável:** Direcionar campanhas de marketing digital especificamente para as SKUs que mostraram maior elasticidade de preço e faturamento.
2. **Otimização de Estoque:** Ajustar o calendário de produção fabril baseando-se nos picos sazonais de volume detectados entre os anos analisados.
