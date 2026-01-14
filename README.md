# 🎮 Dashboard de Estratégia de Vendas - Xbox Game Pass

![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

![Status](https://img.shields.io/badge/Status-Concluído-green)

## 📌 Contexto e Objetivo
Este projeto foi desenvolvido para realizar uma **análise exploratória de dados** de assinaturas do ecossistema Xbox Game Pass. O foco principal é entender os vetores de receita, o comportamento do consumidor em relação aos diferentes níveis de assinatura (Core, Standard, Ultimate) e o impacto de estratégias de monetização adicional (Add-ons e Cupons).

O dashboard responde a perguntas estratégicas como:
- Qual plano traz o maior retorno financeiro vs. volume de usuários?
- Como a recorrência (mensal, trimestral, anual) impacta a previsibilidade de caixa?
- Qual o impacto da ativação do "Auto-Renewal" no risco de Churn?


## 📊 Tour pelo Dashboard

### 1. Visão Geral de Receita (Revenue Overview)
Nesta tela, temos os KPIs macro do negócio. É possível notar que o plano **Ultimate** é o maior motor de receita (R$ 5.39 Mil), apesar de não ter a maior base de usuários, validando a estratégia de upsell.

![Visão Geral](/Assets/Revenue_overview.png)

### 2. Análise de Níveis de Assinatura (Subscription Levels)
Aqui aprofundamos na quebra entre os planos. O insight visual claro é que o **GamePass Core** atrai o volume (101 usuários), mas o **Ultimate** retém o valor monetário.

![Níveis de Assinatura](/Assets/Subscription_levels.png)

### 3. Recorrência e Fidelização (Recurrency Plan)
A análise mostra uma forte predominância das assinaturas **Mensais** (139 usuários). Isso sinaliza uma barreira de entrada baixa, mas exige um esforço maior de retenção contínua comparado aos planos anuais.

![Plano de Recorrência](/Assets/Recurrency_plan.png)

### 4. Risco e Auto-Renovação (Auto Renewal & Churn Risk)
Um ponto crítico do negócio: cerca de **50% da base** tem a renovação automática desligada. Cruzando com os dados mensais, identificamos aqui o grupo de maior risco de cancelamento (Churn).

![Auto Renewal](/Assets/Auto_renewal.png)

### 5. Impacto de Add-ons e Cupons
A estratégia de Cross-selling se prova eficaz: usuários que compram Add-ons possuem um **Ticket Médio (AOV)** de R$ 37,06, significativamente superior à média geral de R$ 25,87.

![Add-ons](/Assets/Add_ons.png)

Os cupons representam um valor pequeno se comparados com o benefício do aumento no Ticket Médio dos usuários.

![Cupons](/Assets/Coupons.png)

---

## 💡 Principais Insights de Negócio
Com base na análise dos dados, as seguintes conclusões foram extraídas:

* **Eficiência do Premium:** O plano *Ultimate* gera a maior receita média por usuário (ARPU), sugerindo que campanhas de migração do *Core* para o *Ultimate* são altamente lucrativas.
* **Segurança de Caixa:** As assinaturas anuais, embora tenham menor adoção, garantem previsibilidade de receita e aumentam o LTV (Lifetime Value) do cliente.
* **Oportunidade de Upsell:** A compra de *Add-ons* eleva drasticamente o ticket médio. Clientes engajados com conteúdo extra tendem a ser mais fiéis.
* **Alerta de Risco:** Assinantes mensais com *auto-renew* desativado representam o segmento de maior vulnerabilidade e devem ser alvo de campanhas de retenção proativas.

---

## 🛠️ Tecnologias e Metodologia
- **Power BI:** Ferramenta principal para construção do storytelling e visualização.
- **Power Query:** Utilizado para o tratamento de dados e modelagem (ETL).
- **DAX (Data Analysis Expressions):** Criação de medidas para cálculos de variação, total acumulado e segmentação de clientes.

### ⚠️ Limitações do Projeto
- **Dados de Churn:** O dataset não possui dados explícitos de cancelamento, portanto o risco de churn foi inferido baseando-se no status de renovação automática.
- **Base de Dados:** Os dados utilizados são fictícios/simplificados para fins educacionais.

![Insights](/Assets/Insights.png)

---

### 👨‍💻 Autor
Desenvolvido por **Paulo Leme**.

[LinkedIn](https://www.linkedin.com/in/paulo-henrique-leme-a862ba45/) | [Portfólio](https://github.com/PauloHLeme)