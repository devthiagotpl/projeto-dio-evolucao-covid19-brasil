# Projeto de Análise exploratória de dados do COVID-19 com Python
Projeto feito através do ***Bootcamp Geração Tech Unimed-BH - Ciência de Dados*** da <link src='https://web.dio.me/home'>Digital Innovation One</link> no *Desafio de Projeto do Modulo 2 - Criando modelos com Python e Machine Learning para prever a evolução do **COVID-19 no Brasil***. Ministrado pelo **Mestre** *Neylson Crepalde.*



## Etapas envolvidas na Análise de Dados:

#### 1. **Importação de pacotes necessários**

*Importar nossos pacotes necessários é o ponto de partida de toda a programação de análise de dados em python. Os pacotes mais populares para ciência de dados:*

- pandas

- numpy
- datetime

#### 1.2 **Alguns pacotes mais avançados para visualização dos dados**

- Plotly.express
- plotly.graph_objects
- re
- statsmodels.tsa.seasonal
- matplotlib.pyplot
- pmdarima.arima
- Prophet

#### 2. **Coleta de dados**

*Para uma análise de dados limpa e perfeita, o elemento mais importante é a coleta de dados de qualidade. Para esta análise, os dados coletados foi fornecido pelo Mestre Neyson Crepalde*

- https://github.com/neylsoncrepalde/projeto_eda_covid/blob/master/covid_19_data.csv?raw=true

#### 3. **Transformando dados às nossas necessidades (Data Wrangling)**

*A **Data Wrangling** é um processo onde transformaremos e limparemos nossos dados às nossas necessidades. Não se pode analisar com os dados extraídos crus. temos q transformar os dados para prosseguir com nossa análise.*

#### 4. **Análise exploratória de dados (EDA) e Visualização**

*Esse processo é a parte onde vc mais precisa ter atenção para não extrair e acabar mostrando dados irrelevantes, pois é o coração e a alma da análise de dados. Então, eu dividi este processo em algumas etapas:*

- Explorando dados dos casos confirmados de **COVID-19** apenas no Brasil
- Serie temporal em casos confirmados e novos casos por dia **COVID-19**
- Visualização gráfica da Media dos casos Confirmados, Morte por **COVID-19** no Brasil
- Taxa de crescimento Médio do COVID no Brasil em todo o período e Taxa por dia
- Visualização da Taxa de crescimento de casos confirmados no Brasil

- Predições baseadas nas bibliotecas ***seasonal***, ***pmdarima***, ***prophet***
  - Previsão de casos confirmados no Brasil para os próximos 30 dias
- Modelo de crescimento com Prophet
  - Preprocessamento
  - Definindo modelo de crescimento
  - treinando o modelo
  - construindo previsões para o futuro
  - Visualização gráfica das predições de casos confirmados no Brasil



### Por fora do Conteúdo ministrado no bootcamp Acrescentei mais algumas análises exploratória e visualização dos dados utilizando o próprio conteúdo aprendidos em aula e buscando informações nas documentações.

***Trouxe o Ranking do 11 Primeiros Países com maiores casos confirmados, casos de mortes e os casos Recuperados:***

* Visualização gráfica do Rank 11 de Países com casos confirmados.
* Visualização gráfica do Rank 11 de Países com casos de mortes.
* Visualização gráfica do Rank 11 de Países com casos Recuperados.

________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

## *English*

# COVID-19 Exploratory Data Analysis Project with Python

Project made through the ***Bootcamp Geração Tech Unimed-BH - Data Science*** of <link src='https://web.dio.me/home'>Digital Innovation One</link> in the *Challenge of Module 2 project - Creating models with Python and Machine Learning to predict the evolution of **COVID-19 in Brazil***. Taught by **Master** *Neylson Crepalde.*



## Steps involved in Data Analysis:

#### 1. **Import required packages**

*Importing our required packages is the starting point of all data analysis programming in python. The most popular packages for data science:*

- pandas

- numpy
- datetime

#### 1.2 **Some more advanced packages for data visualization**

- Plotly.express
- plotly.graph_objects
- re
- statsmodels.tsa.seasonal
- matplotlib.pyplot
- pmdarima.arima
- Prophet

#### 2. **Data Collection**

*For clean and perfect data analysis, the most important element is collecting quality data. For this analysis, the data collected was provided by Mestre Neyson Crepalde*

- https://github.com/neylsoncrepalde/projeto_eda_covid/blob/master/covid_19_data.csv?raw=true

#### 3. **Transforming data to our needs (Data Wrangling)**

*The **Data Wrangling** is a process where we will transform and clean our data to our needs. It cannot be analyzed with the raw extracted data. we have to transform the data to proceed with our analysis.*

#### 4. **Exploratory Data Analysis (EDA) and Visualization**

*This process is the part where you most need to be careful not to extract and end up showing irrelevant data, as it is the heart and soul of data analysis. So I've broken this process down into a few steps:*

- Exploring data from confirmed cases of **COVID-19** in Brazil only
- Time series in confirmed cases and new cases per day **COVID-19**
- Graphic visualization of the Media of Confirmed cases, Death by **COVID-19** in Brazil
- Average growth rate of COVID in Brazil throughout the period and Rate per day
- View the growth rate of confirmed cases in Brazil

- Predictions based on ***seasonal***, ***pmdarima***, ***prophet*** libraries
  - Forecast of confirmed cases in Brazil for the next 30 days
- Growth model with Prophet
  - preprocessing
  - Defining growth model
  - training the model
  - building predictions for the future
  - Graphic visualization of predictions of confirmed cases in Brazil



### Outside the content taught in the bootcamp I added some more exploratory analysis and data visualization using the content learned in class and looking for information in the documentation.

***Brought the Ranking of the Top 11 Countries with the highest confirmed cases, cases of deaths and cases Recovered:***

* Graphical view of Rank 11 of Countries with confirmed cases.
* Graphical visualization of Rank 11 of Countries with cases of deaths.
* Graphical view of Rank 11 of Countries with Recovered cases.

