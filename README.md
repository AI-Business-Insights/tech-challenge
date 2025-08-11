# Tech Challenge 6IADT - Fase 1

**Pós-Tech IA para Devs – São Paulo/SP, 2025**

<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/0c4a8d95-caa5-4346-a438-98651fb208f6" />

## Integrantes

- Ana Maria Silva (RM: 366289)
- Débora Dâmaso (RM: 366501)
- Juliana Conde (RM: 366402)
- Marcelo Fernandes (RM: 366035)
- Mariana Santana (RM: 366262)

## Introdução

Este repositório corresponde ao projeto do Tech Challenge da Pós-Tech IA para Devs (FIAP) do Grupo Artificial Intelligence & Business Insights, cujo objetivo é desenvolver um sistema inteligente de suporte ao diagnóstico para um hospital universitário. O desafio consiste em aplicar técnicas de Inteligência Artificial (IA), com foco em Machine Learning e Visão Computacional, para auxiliar na análise de exames médicos e processamento de dados clínicos, contribuindo para decisões mais rápidas e eficazes em contextos de alta demanda hospitalar, como a pandemia da COVID-19.

O trabalho do grupo para a fase I do Tech Challenge concentrou-se no desenvolvimento de modelos preditivos de aprendizado de máquina para cálculo da propensão de um paciente avançar para fases graves da Covid19 ou vir a falecer (baseando-se em dados estruturados, dispostos em forma tabular), bem como cálculo da propensão de um paciente estar com um pulmão não saudável (baseado em dados não estruturados, referentes a imagens de radiografias realizadas no momento do diagnóstico), usando o resultado dessas análises para priorizar o atendimento aos pacientes com risco mais elevado de complicações, maximizando a capacidade de salvar vidas e reduzindo os custos de atendimento e internação.

## Descrição dos Datasets

O grupo decidiu trabalhar com fontes de dados distintas (dados tabulares e imagens) para ter a possibilidade de testar o uso de diferentes algoritmos de detecção de padrões, assim como aproximar-se da realidade de um hospital ou centro de diagnóstico, que certamente tem à disposição dados de diferentes naturezas e formatos, que podem ou não ser combinados para uma avaliação mais abrangente do estado de saúde de um paciente, permitindo ações que possam personalizar seu atendimento, de acordo com a tendência de evolução da doença, identificada a partir dos dados e modelos estatísticos e matemáticos empregados na análise dos dados.

A solução foi construída a partir da integração de dois datasets relacionados ao COVID-19:

- **Dataset de Registros de Pacientes (dados tabulares):**  
  Contém dados estruturados, como idade, sexo e variáveis clínicas, para prever a probabilidade de evolução para quadros graves de COVID-19, identificando fatores de risco para priorização de pacientes.

- **Dataset de Radiografias de Pulmão (imagens):**  
  Inclui imagens classificadas em estados como opacidade, pneumonia, COVID-19 ou saudável. Utiliza redes neurais convolucionais (CNNs) para detectar anormalidades pulmonares associadas à doença, apoiando o diagnóstico visual.

## Relatório Técnico

Na estrutura da documentação consta:

### Descrição

### Exploração dos Dados

### Pré-processamento dos Dados

### Limpeza dos dados

### Desenvolvimento do Modelo

### Avaliação dos Modelos

### Aplicabilidade Prática

### Lições Aprendidas e Melhorias 

### Conclusão Geral

### Referências

## Entregáveis

1. **Repositório no Github e Google Drive:**  
  - [Pasta no Google Drive com Entregáveis](https://drive.google.com/drive/folders/1pEZHwCrVuLVRahdMEr89pPuFEcwg8mQI?usp=drive_link)

2. **Links dos Datasets:**  
  - Base de dados I: https://www.kaggle.com/datasets/meirnizri/covid19-dataset (dados tabulares, referentes a 1.048.576 pacientes únicos, provenientes do sistema de saúde do México).
  - Base de dados II: https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database (dados de 21.165 radiografias do pulmão, trabalhadas por pesquisadores das universidades de Doha, no Catar, e de Daca, em Bangladesh).


3. **Notebooks Google Colab:**  
   - [Base de Dados I - Dataset de Registros de Pacientes (dados tabulares)](https://github.com/AI-Business-Insights/tech-challenge/blob/5c3f6a3bed09d5c30e181cb124775c31389a7888/notebooks/Covid_19_Dataset_Analise_completa_dos_dados_tabulares.ipynb)
   - [Base de dados II - Dataset de Radiografias de Pulmão (imagens)](https://github.com/AI-Business-Insights/tech-challenge/blob/5c3f6a3bed09d5c30e181cb124775c31389a7888/notebooks/Covid_19_Imagens_dataset.ipynb)

4. **Relatório Técnico:**  
   - [Relatório da Documentação (em PDF)](https://drive.google.com/file/d/1RWTwwmhm8u9K-q5MBZzj4uWWKSrI4Sw0/view?usp=drive_link)

5. **Vídeo de Demonstração:**  
   [Vídeo no YouTube com demonstração do sistema em execução com breve explicação do fluxo.](https://www.youtube.com/playlist?list=PL1zapSlcAQTfqfXpcY-upK14391b0Z5Nw)
