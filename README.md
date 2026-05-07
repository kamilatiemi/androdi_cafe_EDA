# Market Analysis for Robotic Dining: Investment Feasibility in LA

## 📌 Project Overview
This project provides a comprehensive market analysis for a startup coffee shop in Los Angeles that utilizes robotic waiters. While the business currently enjoys success due to the "novelty factor," the goal of this analysis is to provide data-backed insights to potential investors regarding the long-term sustainability of the business when the initial hype fades.

## 🎯 Business Goals
The primary objective is to investigate the Los Angeles restaurant market to determine:
*   The competitive landscape between independent establishments and large chains.
*   The optimal seating capacity based on establishment types.
*   Actionable recommendations for the coffee shop’s expansion and investment strategy.

## 📊 Data Description
The analysis is based on open-source data regarding restaurants in Los Angeles.

| Column | Description |
| :--- | :--- |
| `object_name` | Name of the establishment |
| `chain` | Boolean indicating if the establishment belongs to a chain |
| `object_type` | Category of the establishment (e.g., Cafe, Fast Food, Restaurant) |
| `address` | Full physical address |
| `number` | Number of seats (capacity) |

## 🛠️ Tech Stack
*   **Language:** Python
*   **Libraries:** Pandas (Data Cleaning & Manipulation), Seaborn & Matplotlib (Data Visualization).
*   **Environment:** Jupyter Notebook.

## 📈 Key Research Questions
1.  What is the distribution of establishment types across Los Angeles?
2.  Do chains or independent businesses dominate the market in terms of quantity and seating?
3.  What is the average seating capacity for cafes compared to full-scale restaurants?
4.  Which street locations have the highest concentration of food establishments?

## 🚀 Key Insights (Preview)
*(Dica: Após terminar sua análise, adicione aqui 2 ou 3 pontos principais encontrados e, se possível, uma imagem de um gráfico gerado pelo Seaborn)*
*   Example: "Cafes in LA tend to have a significantly lower seating capacity (avg. 25) compared to restaurant chains."
*   Example: "The 'Chain' model is predominant in fast-food sectors, while independent shops hold a 60% market share in the specialty coffee niche."

## 📂 How to Run This Project
1. Clone the repository: `git clone https://github.com/seu-usuario/nome-do-repositorio.git`
2. Install dependencies: `pip install pandas seaborn matplotlib`
3. Open the `main.ipynb` notebook.