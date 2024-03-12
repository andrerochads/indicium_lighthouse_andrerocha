# Sobre as entregas, notebooks e próximos passos

Sobre as entregas:

- **Todas as Perguntas e Predição** estão presentes nos notebooks;
- **Relatório das análises estatísticas e EDA** estão presentes nos **notebooks A e B**, na pasta notebooks;
- **Códigos de modelagem** estão presentes no **notebook C**, na pasta notebooks;
- **Arquivo pickle(.pkl)** do modelo de machine learning com o melhor desempenho, na pasta pkl_model;
- **Arquivo de requisitos** com todos os **pacotes utilizados e versões**, está no arquivo de texto com o nome de **requirements.txt**.

Sobre os notebooks:

Dividi-os por tópicos sequenciais para facilitar a organização, cada um deles contém:

- **Notebook A:**


1. Data Description
2. Feature Engineering
3. Salvando dataset

<br>

- **Notebook B:**

4. EDA (Análise Exploratória de Dados)
5. Respostas das Perguntas de Negócio solicitadas no desafio

<br>

- **Notebook C:**

5. Data Preparation
6. Feature Selection
7. Machine Learning
8. Fine Tunning
9. Tradução e Interpretação do Erro
10. Prevendo preço do imóvel solicitado

<br>

Sobre os próximos passos e melhorias:

-  Melhorar o desempenho do modelo, criando mais features;
-  Criar uma feature que calcule as distâncias entre os centros dos distritos e o imóvel, para melhorar a capacidade do modelo de prever os preços imobiliários através da localização;
- Criar uma feature que explore mais a coluna nome do anúncio;
- Deploy do modelo via API + Streamlit. Resumidamente, a API será um web service (no Render) com o modelo treinado (.pkl), e o Streamlit, como um web app que fará as requisições do usuário para a API, que retornará o preço sugerido.
