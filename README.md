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

- **Registros de Pacientes:**
  - Carregamento e exploração inicial dos dados.
  - Estatísticas descritivas e visualização de distribuições relevantes.
  - Discussão dos resultados preliminares.

- **Imagens de Pulmão:**
  - Carregamento e exploração visual de exemplos.
  - Distribuição das classes.
  - Discussão dos resultados preliminares.

### Limpeza dos dados

- **Registros de Pacientes:**
  Limpeza de dados, tratamento de valores ausentes, normalização e seleção de características.<br>
  Para a base de dados tabulares, veja todos os detalhes do processo de análise e limpeza dos dados:<br>
  https://colab.research.google.com/drive/1HBpS-6cHapA8gm0yS4Gsx5kiAS9TtxCQ<br>

- **Imagens de Radiografias de Pulmão:**
 Para a base de imagens foram adotados os seguintes procedimentos: <br>
 https://colab.research.google.com/drive/1KDI84YUlH4_x5mPulN-zJEzNaWJLmjiF?usp=sharing<br>

### Desenvolvimento do Modelo

### Avaliação dos Modelos

- Interpretação dos resultados para cada Dataset

### Aplicabilidade Prática

- Viabilidade de implantação em ambiente clínico.
- Importância do papel dos profissionais médicos no diagnóstico final.
- Limitações e possíveis melhorias futuras.

### Lições Aprendidas e Melhorias 

### Conclusão

### Referências

## Entregáveis

1. **Repositório no Github:**  
  No repositório [https://github.com/AI-Business-Insights/tech-challenge](https://github.com/AI-Business-Insights/tech-challenge) constam:
  - Datasets (dados tabulares e imagens)
  - Notebooks Google Colab
  - Relatório da Documentação
  - Link do Vídeo de demonstração no YouTube
  - Referências

3. **Links dos Datasets:**  
    https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database
    https://www.kaggle.com/datasets/meirnizri/covid19-dataset

4. **Notebooks Google Colab:**  
   - Base de Dados I - Dataset de Registros de Pacientes (dados tabulares): incluir link do github
   - Base de dados II - Dataset de Radiografias de Pulmão (imagens): incluir link do GitHub

5. **Relatório Técnico:**  
   - DocumentacaoGeral_AIBI_TechChallenge_Fase1.pdf / incluir link do GitHub

6. **Vídeo de Demonstração:**  
   [Vídeo no YouTube com demonstração do sistema em execução com breve explicação do fluxo.](https://www.youtube.com/playlist?list=PL1zapSlcAQTfqfXpcY-upK14391b0Z5Nw)
