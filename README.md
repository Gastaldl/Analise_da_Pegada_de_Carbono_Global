# 🌍 Análise da Pegada de Carbono Global e Indicadores de Sustentabilidade  

## 📌 Introdução  
Este projeto tem como objetivo analisar e comparar a pegada de carbono e os indicadores de sustentabilidade de diversos países, com ênfase especial no Brasil. Para isso, utilizamos dois conjuntos de dados principais:  

1. **Emissões de CO₂ fósseis por setor** (carvão, petróleo, gás, cimento, entre outros).  
2. **Indicadores de sustentabilidade** (acesso à eletricidade, capacidade de geração de energia renovável, intensidade energética e dados socioeconômicos).  

A análise busca compreender os fatores que influenciam as emissões de carbono, identificar padrões de sustentabilidade energética e explorar políticas ambientais adotadas globalmente.  

## 🔍 Perguntas de Pesquisa  
Algumas questões que direcionaram a análise incluem:  
✅ Qual a pegada de carbono do Brasil e sua comparação com a média global?  
✅ Como a dependência de energias renováveis impacta as emissões?  
✅ Quais setores são os principais responsáveis pelas emissões no Brasil e na OCDE?  
✅ Existe uma relação entre PIB per capita e pegada de carbono?  
✅ Como o acesso à eletricidade e o uso de combustíveis limpos afetam as emissões de carbono?  
✅ Podemos classificar os países em categorias de pegada de carbono com base em aprendizado de máquina?  

## 🛠 Tecnologias e Ferramentas Utilizadas  
O projeto foi desenvolvido em **Python**, utilizando bibliotecas essenciais para análise e modelagem de dados:  
- `pandas` → Manipulação e análise de dados  
- `numpy` → Cálculos matemáticos e otimização  
- `matplotlib` & `seaborn` → Visualização de dados  
- `scikit-learn` → Modelagem de aprendizado de máquina (regressão e classificação)  

## 📊 Etapas do Projeto  
🔹 **Coleta e limpeza de dados:** Tratamento de valores nulos e padronização de colunas.  
🔹 **Exploração e visualização:** Gráficos e estatísticas descritivas para análise de padrões.  
🔹 **Modelagem preditiva:** Utilização de regressão linear e RandomForest para prever e classificar países com base em emissões de CO₂ e consumo de energia renovável.  
🔹 **Comparação Brasil vs Mundo:** Análise específica da pegada de carbono do Brasil em relação a grandes emissores e países da OCDE.  

## 📌 Como Executar o Projeto  
1. Instale as bibliotecas necessárias com:  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
2. Execute o Jupyter Notebook e rode as células do código passo a passo.  
3. Os gráficos gerados mostrarão as tendências globais de emissões e sustentabilidade.  
