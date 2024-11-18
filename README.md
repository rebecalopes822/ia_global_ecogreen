# DISRUPTIVE ARCHITECTURES: IoT, IoB & GENERATIVE AI

## GLOBAL SOLUTION

**Equipe EnerGreen**  
- Giovanna Lima (RM: 553369)  
- Paulo Sergio (RM: 84059)  
- Rebeca Lopes (RM: 553764)  

---

## Sistema de Monitoramento e Economia de Consumo de Energia

### Descrição do Problema

Nosso projeto busca criar uma ferramenta prática para ajudar as pessoas a monitorarem o consumo de energia elétrica e promover o uso consciente de energia. Com o aumento das tarifas e a importância crescente de práticas sustentáveis, percebemos a necessidade de uma forma clara de visualizar o consumo ao longo do tempo. Nossa solução permite que os usuários registrem e analisem seu consumo mensal, com alertas e incentivos para quem busca economizar.

---

### Metodologia Utilizada

Para construir o sistema, utilizamos métodos simples de análise de dados e algumas técnicas de machine learning para gerar insights fáceis de entender. Nossas principais abordagens foram:

#### 1. Gráficos de Consumo
- **Histórico Mensal**: Criamos um gráfico de linha para mostrar o consumo de energia mês a mês, ajudando a visualizar as flutuações de uso.
- **Comparação com a Média Anual**: Com um gráfico de barras, comparamos o consumo de cada mês com a média anual, facilitando identificar se o consumo foi acima ou abaixo da média.

#### 2. Modelos de Machine Learning
- **Regressão Linear**: Usamos regressão linear para prever o consumo do próximo mês com base nos dados históricos, ajudando o usuário a se antecipar a mudanças de consumo.
- **Classificação por K-Nearest Neighbors (KNN)**: Esse modelo classifica o perfil de consumo (baixo, médio ou alto) para facilitar a visualização do comportamento de uso ao longo do tempo.
- **Árvore de Decisão**: Implementamos uma árvore de decisão para prever se o consumo tende a aumentar ou diminuir, com base nas mudanças dos últimos meses.
- **Random Forest Regressor**: Esse modelo usa múltiplas árvores para melhorar a precisão na previsão do consumo do próximo mês.

#### 3. Estatísticas de Consumo
- **Média e Mediana**: Calculamos a média e a mediana anual do consumo, dando ao usuário uma ideia clara de seu consumo típico.
- **Consumo Total Anual**: Exibimos o consumo total ao longo do ano para uma visão geral do gasto.
- **Meses de Maior e Menor Consumo**: Identificamos os meses de pico e de menor consumo para facilitar a análise de padrões.

#### 4. Comparação Mensal com a Média Anual
- Para cada mês, comparamos o consumo com a média anual.  
  - **Abaixo da média**: Parabenizamos o usuário.  
  - **Acima da média**: Emitimos um alerta para incentivar a economia.

---

### Resultados Obtidos

Nossa ferramenta se mostrou eficiente para fornecer informações práticas e fáceis de interpretar sobre o consumo de energia ao longo do ano. Os gráficos ajudam a visualizar o histórico e identificar padrões, enquanto os modelos de previsão trazem uma estimativa para o mês seguinte. Com a comparação mensal em relação à média, oferecemos um feedback direto ao usuário, incentivando o uso consciente.

---

### Conclusões

Nosso projeto alcança o objetivo de promover a conscientização sobre o consumo de energia com uma interface simples e informativa. Com análises diretas e feedbacks personalizados, ajudamos os usuários a monitorarem e ajustarem seu consumo de forma prática.

---

### Link do Vídeo da Apresentação

[https://youtu.be/xXL4_ZPhl6o](https://youtu.be/xXL4_ZPhl6o)
