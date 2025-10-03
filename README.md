📌 Projeto

Este projeto é uma análise exploratória de dados (EDA) e teste de hipóteses aplicado a dados de corridas de táxi em Chicago. O objetivo é entender padrões de viagens, identificar bairros mais movimentados e testar se fatores externos (como clima) afetam a duração das corridas.

---

## 📂 Dados

Foram utilizados três conjuntos de dados CSV:

1. **project_sql_result_01.csv** – número de corridas por empresa de táxi (15 a 16 de novembro de 2017).  
2. **project_sql_result_04.csv** – bairros de destino e média de viagens em novembro de 2017.  
3. **project_sql_result_07.csv** – viagens do Loop para o Aeroporto Internacional O'Hare, incluindo data/hora, condições meteorológicas e duração da corrida.

---

## 🛠 Metodologia

O projeto seguiu os seguintes passos:

### Passo 4 – Análise Exploratória de Dados (EDA)

1. Importação e inspeção dos dados (`pandas`)  
2. Verificação e correção de tipos de dados  
3. Identificação dos **10 principais bairros por número de corridas**  
4. Criação de gráficos:
   - Número de corridas por empresa de táxi
   - Top 10 bairros por número de corridas  
5. Interpretação e conclusões baseadas nos gráficos  

### Passo 5 – Teste de Hipóteses

- **Hipótese testada:**  
  "A duração média dos passeios do Loop para o Aeroporto Internacional O'Hare muda nos sábados chuvosos."
  
- **Etapas:**
  1. Formulação da hipótese nula (H₀) e alternativa (H₁)  
  2. Definição do nível de significância (α = 0.05)  
  3. Seleção do teste estatístico adequado (teste t ou Mann-Whitney, dependendo da distribuição)  
  4. Análise do p-valor e decisão sobre H₀  
  5. Interpretação dos resultados  

---

## 📊 Principais Resultados

- Empresas de táxi mais ativas tiveram maior volume de corridas no período analisado.  
- Os 10 bairros mais populares mostraram concentração geográfica de destinos.  
- O teste de hipóteses indicou que **as condições meteorológicas afetam a duração média das corridas nos sábados**, fornecendo insights valiosos para planejamento logístico e previsão de demanda.

---

## 🛠 Tecnologias utilizadas

- Python 3  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- SciPy / Statsmodels  

---

## 💡 Conclusão

O projeto demonstra habilidades em:

- Manipulação e análise de dados em Python  
- Visualização e interpretação de informações  
- Teste de hipóteses e estatística aplicada  
- Comunicação clara de resultados  


