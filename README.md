# MVP de Análise de Dados e Boas Práticas da Pós-Graduação na PUC-Rio de Ciência de Dados e Analitycs
Autor: Thomas Alves de Souza Abrantes

**Este repositório foi destinado a entrega do MVP da Sprint de Análise de Dados e Boas Práticas da Pós-Graduação na PUC-RIO.**  
<br>

O MVP foi desenvolvido com um notebook do Google Collab disponivei neste repositório e acessado pelo arquivo:
*  Notebook Google Collab: **Sprint_2_MVP_Análise_de_Dados_e_Boas_Práticas.ipynb**
<br>

**Arquivos com dataset utilizados neste MVP:**
<hr>

**netflix_titles.csv**  
  *  Arquivo csv extraído no Kaggle ( https://www.kaggle.com/datasets/rahulvyasm/netflix-movies-and-tv-shows ))
  *  Dataset com mais de 8 mil registros com informações sobre filmes e as séries disponíveis na plataforma Netflix até 2021.
  
**amazon_prime_titles.csv**  
  *  Arquivo csv extraído no Kaggle ( https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows/data )
  *  Dataset com mais de 9 mil registros de filmes e séries disponíveis na plataforma Amazon Prime, até meados de 2021, com informações de títulos, elenco, diretores, classificações, ano de lançamento e duração.

**paises.csv**  
  *  Arquivo contendo a lista de todos os paises em inglês para garantir que os paises informados na coluna 'country' de cada dateset estejam corretos.
<br>

## **Objetivo**  
<hr>
Neste MVP vamos realizar a análise dos catálogos de títulos disponíveis nas duas plataformas (Netflix e Amazon Prime).  
Com um dataframe consolidado (com os dois datasets) podemos analisar e classificar os títulos de acordo com a sua origem (Netflix ou Amazon Prime) e responder as seguintes perguntas:

*  Quais países produziram mais títulos em cada catálogo (Netflix e Amazon Prime)?
*  Quais períodos (iremos agrupar o ano de lançamento por décadas) houve mais produção de títulos na Netflix e Amazon Prime?
*  Quais gêneros são mais populares no catálogo da Netflix e Amazon Prime?
*  Com as respostas acima podemos ter um direcionamento ao aplicar em uma nova empresa?
