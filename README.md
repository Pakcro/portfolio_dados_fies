## :open_book: FIES

Meu foco nesse projeto é entender as mudanças que ocorreram dentro do programa governamental, utilizando os dados públicos de 2019, 2020 e 2021. Com base nisso, decidi seguir o processo padrão de ETL.
Os dados foram extraídos do site do MEC, podendo ser acessados pelo link [https://dadosabertos.mec.gov.br/](https://dadosabertos.mec.gov.br/)

**Extração:** Se tratava de arquivos CSV com disponibilização pública.

**Transformação:** Utilizei primeiramente o Python para mesclar todos os arquivos CSV em um só, para faciliar a análise.

**Carregamento:** Visualização dos dados em Python, com relatório descritivo das operações realizadas.

### :wrench: Ferrramentas

-**Python**

-**Pandas**

-**Matplotlib**

-**Anaconda**

-**JupyterLab**

### :memo: Skills utilizadas

-**Limpeza de dados**

-**Tratamento dos dados**

-**Coleta de informações**

-**Transformação das informações em insights**

-**Data visualization**

-**Data Storytelling**

# Etapas

Aqui seguiremos o processo etapa a etapa, para entendermos como chegamos no resultado.

## Extração

Arquivos retirados do site do MEC, onde possuiam arquivos de 2019 a 2021, existem 2 tipos de planilha, uma contendo os dados dos inscritos e outra com as informações das vagas disponibilizadas pelas instituições públicas.

Cada ano possui 2 semestres, os arquivos dos inscritos eram separados da mesma maneira, resultando no total de 6 planilhas mais 3 planilhas de vagas.

## Transformação

Por se tratar de diversas planilhas contendo as mesmas colunas, decidi por mesclar em um unico arquivo, facilitando na hora de realizar as análises futuras. Para isso utilizei Pandas e OS, bibliotecas do Python que facilitam essa operação. 

Os arquivos estavam corretamente classificados, tendo que fazer pequenas correções para facilitar a análise.


