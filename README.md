# 📈 Análise de Viabilidade Financeira - Programa de Fidelidade & Python

Análise de dados focada no impacto financeiro de programas de fidelidade. O script simula e processa dados de resgates, identifica mudanças no comportamento do consumidor (preferência por boletos) e visualiza a correlação direta com a quebra de fluxo de caixa da empresa. Foco em Storytelling com Dados e visualização estratégica.

## 📋 Sobre o Projeto

O objetivo deste projeto foi utilizar **Python** para diagnosticar a saúde financeira de um programa de pontos. Através da análise exploratória, identificamos um problema crítico de **"Canibalização de Margem"**: os usuários deixaram de resgatar produtos (margem alta) para pagar boletos (custo alto para a empresa).

O estudo abrange desde a limpeza dos dados brutos até a criação de visualizações complexas (Eixos Duplos, Áreas de Prejuízo e Gráficos Empilhados) para provar a tese de que o aumento do faturamento não garantiu a sustentabilidade do caixa.

### 🛠 Tecnologias Utilizadas

* ![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
* ![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=for-the-badge&logo=pandas)
* ![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c?style=for-the-badge)
* ![Seaborn](https://img.shields.io/badge/Seaborn-Data_Viz-green?style=for-the-badge)
* **Google Colab** (Ambiente de desenvolvimento)

## 📊 Análises e Visualizações

Abaixo estão as etapas visuais desenvolvidas para contar a história dos dados:

### 1. Fluxo de Pontos (Sazonalidade)
Comparativo entre entrada (Créditos) e saída (Resgates) de pontos. O gráfico destaca visualmente os picos de resgates nos meses de férias (Janeiro e Julho), fundamentais para o planejamento de estoque e caixa.

<img width="1389" height="690" alt="download (5)" src="https://github.com/user-attachments/assets/5a8cb841-2179-4eb8-809b-573ebcabc357" />


### 2. Mudança de Comportamento (Tendência Linear)
Análise de tendência utilizando regressão linear (`regplot`) para demonstrar o crescimento contínuo na preferência dos usuários pelo pagamento de boletos, saindo de 30% para quase 70% do volume total.

<img width="1189" height="590" alt="download (6)" src="https://github.com/user-attachments/assets/6583ac71-3ffc-4852-b594-f57f5964bc02" />


### 3. Impacto no Caixa (Profit & Loss)
Visualização de alto impacto mostrando o momento exato do "Break-even" negativo. A área verde representa saldo positivo, enquanto a área vermelha evidencia o prejuízo acumulado gerado pelo aumento dos custos operacionais dos boletos.

<img width="1190" height="590" alt="download (7)" src="https://github.com/user-attachments/assets/98c26afa-eb2f-47b2-bb2a-7c8cc23adbf6" />


### 4. Canibalização de Resgates (Mix de Produtos)
Gráfico de barras 100% empilhadas que prova a substituição dos resgates. É possível ver claramente a categoria "Boletos" (Laranja) comprimindo e tomando o espaço dos "Outros Prêmios" (Azul) ao longo do ano.

<img width="1189" height="590" alt="download (8)" src="https://github.com/user-attachments/assets/41c7b6a0-8b17-4a32-a663-ef9cf7e92d54" />


---

## 💡 Principais Insights

Com base na análise realizada via script Python, observou-se que:

* **Sazonalidade Crítica:** Os meses de **Janeiro e Julho** apresentam picos de resgate (efeito férias), exigindo maior liquidez de caixa nestes períodos.
* **Transformação do Perfil:** Houve uma mudança estrutural no comportamento do usuário. O programa deixou de ser visto como uma vitrine de prêmios e passou a ser utilizado como uma ferramenta de pagamento de contas (Boletos).
* **Impacto na Margem:** O pagamento de boletos possui um custo financeiro imediato muito maior que a entrega de produtos físicos. O gráfico 3 comprova que, mesmo com o aumento de usuários, o **Caixa tornou-se negativo** devido a essa mudança no mix de resgates.

## 🚀 Acesso ao Projeto

Você pode visualizar e executar o código completo e interagir com os gráficos diretamente no Google Colab através do link abaixo:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1QDJE7KN4a6TIs4CMCqGIcfaftpJA9AcD?usp=sharing)

## ✒️ Autor

**Leonardo Miralles**
* **Área:** Dados / Finanças / Business Intelligence

---
*Projeto desenvolvido para fins de portfólio e análise estratégica de dados - 2025.*
