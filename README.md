# 📊 Impacto dos Indicadores Econômicos no Desempenho do Mercado de Ações Brasileiro (B3)

## 📌 Contexto Simulado

Este projeto simula uma situação real de mercado onde atuo como Analista de Mercado na área de Tesouraria do Bradesco.

O gestor da mesa de Renda Fixa solicitou um estudo para entender como os principais indicadores econômicos (IPCA, Selic, PIB, etc.) e o desempenho dos índices da B3 (Ibovespa, Small Caps, etc.) impactam o mercado de ações brasileiro.

---

## 🎯 Objetivo de Negócio

Fornecer insights que ajudem a **embasar decisões de alocação de recursos** e **definição de produtos de investimento**, considerando a relação entre a **política monetária** e o **desempenho do mercado acionário**.

---

## 👥 Stakeholders Envolvidos

- Gerente da Mesa de Renda Fixa
- Equipe de Riscos
- Área de Produtos de Investimentos

---

## ❓ Pergunta SMART (Exemplo de Análise)

| Critério | Definição |
|---|---|
| **Specific (Específica)** | Qual a relação entre a **variação da taxa Selic após cada reunião do COPOM** e o **retorno acumulado do Ibovespa nos 45 dias seguintes**? |
| **Measurable (Mensurável)** | Resultado será medido pelo **coeficiente de correlação de Pearson** entre as duas variáveis. |
| **Achievable (Atingível)** | Análise viável com os dados históricos disponíveis no Kaggle (últimos 10 anos). |
| **Relevant (Relevante)** | A relação entre Selic e Ibovespa é fundamental para a estratégia da Tesouraria. |
| **Time-bound (Temporal)** | Período da análise: **Janeiro/2013 a Dezembro/2022** |

*(Outras perguntas serão formuladas ao longo do projeto)*

---

## 🗂️ Dados Utilizados

- Dataset: **"brazilian-stock-market"** (Kaggle)
- Conteúdo:
  - Índices de Mercado (Ibovespa, Small Caps, etc)
  - Indicadores Macroeconômicos (Selic, IPCA, PIB, etc)
  - Preços de ações individuais da B3

---

## 🛠️ Metodologia

1. **Entendimento de Negócio e Levantamento de Requisitos**
2. **Definição de Perguntas SMART**
3. **Coleta e Importação dos Dados**
4. **Limpeza e Tratamento dos Dados (Python: Pandas, NumPy)**
5. **Análise Exploratória de Dados (EDA)**
6. **Respostas às Perguntas de Negócio com Estatísticas e Gráficos**
7. **Criação de Dashboard no Power BI**
8. **Conclusões e Recomendações para os Stakeholders**

---

## ✅ Status Atual do Projeto

- ✅ Business Understanding
- ✅ Formulação de perguntas SMART
- 🟡 Início da etapa de Análise Exploratória (EDA)
- ⬜️ Respostas estatísticas
- ⬜️ Visualizações finais
- ⬜️ Power BI Dashboard

*(Este README será atualizado conforme o projeto avança.)*

---

## ▶️ Como Executar o Projeto

1. **Instalar as bibliotecas necessárias:**

```bash
pip install pandas numpy matplotlib seaborn


