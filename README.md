Claro! Vou reformular o README.md fornecido pela DIO.ME para incluir concisamente o nosso trabalho desenvolvido, seguindo as instruções fornecidas. Vou garantir que a linguagem seja simples e clara, refletindo o nível de um aluno iniciante.

---

# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao desafio de projeto "Previsão de Estoque Inteligente na AWS com SageMaker Canvas". Neste Lab DIO, você aprenderá a usar o SageMaker Canvas para criar previsões de estoque baseadas em Machine Learning (ML). Siga os passos abaixo para completar o desafio!

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter uma conta na AWS. Se precisar de ajuda para criar sua conta, confira nosso repositório [AWS Cloud Quickstart](https://github.com/digitalinnovationone/aws-cloud-quickstart).

## 🎯 Objetivos Deste Desafio de Projeto (Lab)

![image](https://github.com/digitalinnovationone/lab-aws-sagemaker-canvas-estoque/assets/730492/72f5c21f-5562-491e-aa42-2885a3184650)

- Dê um fork neste projeto e reescreva este `README.md`. Sinta-se à vontade para detalhar todo o processo de criação do seu Modelo de ML para uma "Previsão de Estoque Inteligente".
- Para isso, siga o [passo a passo] descrito a seguir e evolua as suas habilidades em ML no-code com o Amazon SageMaker Canvas.
- Ao concluir, envie a URL do seu repositório com a solução na plataforma da DIO.

## 🚀 Passo a Passo

### 1. Selecionar Dataset

- Navegue até a pasta `datasets` deste repositório. Esta pasta contém os datasets que você poderá escolher para treinar e testar seu modelo de ML. Sinta-se à vontade para gerar/enriquecer seus próprios datasets, quanto mais você se engajar, mais relevante esse projeto será em seu portfólio.
- Escolha o dataset que você usará para treinar seu modelo de previsão de estoque.
- Faça o upload do dataset no SageMaker Canvas.

#### *Resposta/ Meu trabalho:*

Usei o dataset fornecido pela DIO.ME, que contém informações de estoque, vendas e devoluções de produtos. O dataset utilizado está no arquivo `dataset-500-curso-sagemaker-canvas-dio.csv`.

### 2. Construir/Treinar

- No SageMaker Canvas, importe o dataset que você selecionou.
- Configure as variáveis de entrada e saída de acordo com os dados.
- Inicie o treinamento do modelo. Isso pode levar algum tempo, dependendo do tamanho do dataset.

#### *Resposta/ Meu trabalho:*

No SageMaker Canvas, configurei as variáveis de entrada e saída com base nas colunas do dataset. Depois, iniciei o treinamento do modelo.

### 3. Analisar

- Após o treinamento, examine as métricas de performance do modelo.
- Verifique as principais características que influenciam as previsões.
- Faça ajustes no modelo se necessário e re-treine até obter um desempenho satisfatório.

#### *Resposta/ Meu trabalho:*

Depois do treinamento, examinei as métricas para ver como o modelo se saiu. Aqui estão as principais métricas obtidas:

- **Avg. wQL (Average Weighted Quantile Loss):** 0.068
- **MAPE (Mean Absolute Percentage Error):** 0.027
- **WAPE (Weighted Absolute Percentage Error):** 0.115
- **RMSE (Root Mean Squared Error):** 1.246
- **MASE (Mean Absolute Scaled Error):** 0.000

Essas métricas ajudam a entender a precisão do modelo. Valores mais baixos indicam previsões melhores.

### 4. Prever

- Use o modelo treinado para fazer previsões de estoque.
- Exporte os resultados e analise as previsões geradas.
- Documente suas conclusões e qualquer insight obtido a partir das previsões.

#### *Resposta/ Meu trabalho:*

Usei o modelo treinado para fazer previsões de estoque. Os resultados das previsões estão no arquivo `single_prediction_results.csv`. A análise completa do modelo está no `report.pdf`.

## Conclusão

Esse projeto foi uma boa prática para aprender conceitos básicos de Machine Learning sem precisar codificar. O SageMaker Canvas facilitou a criação e análise do modelo.

### Arquivos do Projeto

- `dataset-500-curso-sagemaker-canvas-dio.csv`: Dataset fornecido pela DIO.ME e usado para o treinamento
- `single_prediction_results.csv`: Resultados das previsões
- `report.pdf`: Relatório de análise do modelo

## 🤔 Dúvidas?

Esperamos que esta experiência tenha sido enriquecedora e que você tenha aprendido mais sobre Machine Learning aplicado a problemas reais. Se tiver alguma dúvida, não hesite em abrir uma issue neste repositório ou entrar em contato com a equipe da DIO.
