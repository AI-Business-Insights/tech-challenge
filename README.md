# Tech Challenge 6IADT - Fase 1

Pós-Tech FIAP | Datathon | Grupo 59  
**Pós-Tech IA para Devs – São Paulo/SP, 2025**

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/0c4a8d95-caa5-4346-a438-98651fb208f6" />

## Integrantes

- Ana Maria Silva (RM: 366289)
- Débora Dâmaso (RM: 366501)
- Juliana Conde (RM: 366402)
- Marcelo Fernandes (RM: 366035)
- Mariana Santana (RM: 366262)

## Introdução

Este repositório corresponde ao projeto do Tech Challenge da Pós-Tech IA para Devs (FIAP) do Grupo AI&Business Insights, cujo objetivo é desenvolver um sistema inteligente de suporte ao diagnóstico para um hospital universitário. O desafio consiste em aplicar técnicas de Inteligência Artificial (IA), com foco em Machine Learning e Visão Computacional, para auxiliar na análise de exames médicos e processamento de dados clínicos, contribuindo para decisões mais rápidas e eficazes em contextos de alta demanda hospitalar, como a pandemia da COVID-19.

## Descrição dos Datasets

A solução foi construída a partir da integração de dois datasets relacionados ao COVID-19:

- **Dataset de Registros de Pacientes:**  
  Contém dados estruturados, como idade, sexo e variáveis clínicas, para prever a probabilidade de evolução para quadros graves de COVID-19, identificando fatores de risco para priorização de pacientes.

- **Dataset de Imagens de Radiografias de Pulmão:**  
  Inclui imagens classificadas em estados como opacidade, pneumonia, COVID-19 ou saudável. Utiliza redes neurais convolucionais (CNNs) para detectar anormalidades pulmonares associadas à doença, apoiando o diagnóstico visual.

## Exploração dos Dados

- **Registros de Pacientes:**
  - Carregamento e exploração inicial dos dados.
  - Estatísticas descritivas e visualização de distribuições relevantes.
  - Discussão dos resultados preliminares.

- **Imagens de Pulmão:**
  - Carregamento e exploração visual de exemplos.
  - Distribuição das classes.
  - Discussão dos resultados preliminares.

## Pré-processamento dos Dados

#### **Limpeza dos dados:**

- **Registros de Pacientes:**
  Limpeza de dados, tratamento de valores ausentes, normalização e seleção de características.<br>
  Para a base de dados tabulares, veja todos os detalhes do processo de análise e limpeza dos dados:<br>
  https://colab.research.google.com/drive/1HBpS-6cHapA8gm0yS4Gsx5kiAS9TtxCQ<br>

- **Imagens de Radiografias de Pulmão:**
 Para a base de imagens foram adotados os seguintes procedimentos: <br>
 https://colab.research.google.com/drive/1KDI84YUlH4_x5mPulN-zJEzNaWJLmjiF?usp=sharing<br>

## Desenvolvimento do Modelo

## Avaliação dos Modelos

- **Imagens de Radiografia de Pulmão:**
  - Métricas de avaliação: Acurácia, Recall, F1-Score.
  - Interpretação dos resultados da CNN.
  - Discussão crítica dos resultados.

## Aplicabilidade Prática

- Viabilidade de implantação em ambiente clínico.
- Importância do papel dos profissionais médicos no diagnóstico final.
- Limitações e possíveis melhorias futuras.

## Entregáveis

1. **Repositório no Github:**  
   [https://github.com/AI-Business-Insights/tech-challenge](https://github.com/AI-Business-Insights/tech-challenge)

2. **Links dos Datasets:**  
    https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database
    https://www.kaggle.com/datasets/meirnizri/covid19-dataset

4. **Resultados:**  
   - Capturas de tela dos resultados
   - Gráficos e visualizações

5. **Relatório Técnico:**  
   - Estratégias de pré-processamento
   - Justificativa dos modelos escolhidos
   - Resultados e interpretação

6. **Vídeo de Demonstração:**  
   (Incluir link para o vídeo no YouTube)

## Conclusão

## Lições Aprendidas

## Referências

## Apêndices
