# Dashboard – Netflix e Prime Video

﻿Dashboard desenvolvido com base em dois datasets a fim de visualizar e analisar o comportamento das plataformas de streaming Netflix e Prime Video ao longo do tempo. Para esse projeto, foi necessário utilizar Python para fazer a união, a limpeza e o preparo inicial dos conjuntos de dados. Já no Power BI, ferramentas nativas foram utilizadas para complementar o tratamento das informações antes da construção da visualização.
 
As bases de dados estão disponíveis no Kaggle ([Netflix](https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies?select=titles.csv) e [Prime Video](https://www.kaggle.com/datasets/victorsoeiro/amazon-prime-tv-shows-and-movies?select=titles.csv)) e o procedimento de limpeza realizado pelo Python estão disponíveis [aqui](https://github.com/JhenyfferOliveira/Projeto-PowerBI-Ada/blob/main/dataset.ipynb).

O projeto visou cumprir os requisitos de **Visualização com Power BI**, do bootcamp de Ciência de Dados da **Ada Tech**, patrocinado pelo **Potência Tech**, do **iFood**. 

O projeto foi realizado em março de 2024 e contou com a colaboração de 4 integrantes:
* Carlos André
* Jhenyffer Oliveira
* Rodrigo Udenal
* Wallace Souza

---

# Análise Geral
![Gráfico 1](Graficos/1.png)

---

Antes de tudo, optou-se por visualizar os gêneros que tem maior quantidade de títulos em cada plataforma:
![Gráfico 2](Graficos/2.png)![Gráfico 3](Graficos/3.png)

Top 5:
+ Amazon: Drama, Thriller, Comédia, Sci-fi, Romance.
+ Netflix: Drama, Thriller, Comédia, Ação, Crime.
  
---

# Perguntas Iniciais e Tendências Gerais
Observar esses gêneros instigou uma busca pela relação entre os votos dos gêneros mais assistidos e os gêneros mais votados. Assim, a análise de tendências gerais com base nos gráficos ficou evidente e chegou-se a alguns questionamentos. Seguem abaixo

## **1. Qual é a distribuição de filmes e séries por tipo (filme ou série de TV) nas plataformas?**

## **2. Como a quantidade de conteúdo lançado tem variado ao longo dos anos?**

## **3. Quais são os gêneros mais populares em cada plataforma?**

## **4. Qual é a distribuição geográfica das produções (países de origem) em cada plataforma?**

## **5. Como a popularidade (avaliações do IMDb e pontuações do TMDb) varia entre os diferentes tipos de conteúdo (filmes versus séries de TV)?**

## **6. Existe alguma correlação entre a popularidade do conteúdo (avaliações do IMDb, pontuações do TMDb e popularidade do TMDb) e o número de temporadas para séries de TV?**

## **7. Existe alguma relação entre a popularidade do conteúdo e o número de votos no IMDb?**

## **8. Quais são os títulos mais populares em cada plataforma, com base em uma combinação de pontuações, popularidade e número de votos?**

## **9. Como a popularidade do conteúdo varia entre diferentes países?**



---

# Considerações Finais


---

# Observações:
+ Os conjuntos de dados foram criados para listar todos os programas disponíveis nas plataformas, em junho de 2022, com informações disponíveis nos Estados Unidos.

---

# Ferramentas utilizadas

| Python | Pandas | Power BI | Git | 
| ------ | ------ | -------- | --- | 
| <img src="https://s3.dualstack.us-east-2.amazonaws.com/pythondotorg-assets/media/files/python-logo-only.svg" width="100"> | <img src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg" width="180"> | <img src="https://upload.wikimedia.org/wikipedia/commons/c/cf/New_Power_BI_Logo.svg" width="110"> | <img src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.svg" width="100"> |
