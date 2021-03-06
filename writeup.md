# Projeto: Contando histórias com o Tableau

Projeto final do Nanodegree Data Science II da Udacity, utilizando dados de passageiros do Titanic.

* [Versão inicial](https://public.tableau.com/profile/cleber.yamamoto#!/vizhome/Titanic_story_v1_1/Titanic_story_v1)

* [Versão final](https://public.tableau.com/profile/cleber.yamamoto#!/vizhome/Titanic_story_final/Titanic_story_final)



## Resumo

Análise do perfil de sobreviventes do naufrágio do Titanic. Uma trágica história que ocorreu em 15 de Abril de 1912, quando o Titanic colidiu com um iceberg. Dos 2.224, contando passageiros e tripulação, 1.502 pessoas morreram.
Os dados utilizados para esta análise de sobreviventes, são os dados de treinamento do dataset do desafio do Kaggle, com apenas 891 registros.
Os passageiros com idade entre 21 a 30 anos foram os que mais sobreviveram. Os passageiros que adquiriram tickets de classe 1 também foram os que mais sobreviveram. Mas, o perfil com maior índice de sobrevivência foram os passageiros de 0 a 10 anos de idade com ticket de classe 2, onde todos sobreviveram.




## Design

Identifiquei que os dados do dataset fornecido pela Udacity eram dados parciais, pois apresentava somente 891 registros dos 2.224 passageiros do Titanic. Notei que a quantidade de dados era a mesma do dataset de treinamento do desafio do Kaggle.

Importei os dados no aplicativo Tableau versão Public. Identifiquei que dos 891 registros, 177 não continham dados de idade. Faltavam também dados da cabine.

Não havia um relação da entrada dos passageiros que entravam por uma porta (Cherbourg, Queenstown ou Southampton) e a classe do ticket (classe 1, 2 ou 3).

Comecei a criar um gráfico de barras no Tableau utilizando a dimensão "Survived" (booleano: 0 = não sobreviveu, 1 = sobreviveu) e a medida "SOMA(número de registros)" para identificar quantos passageiros daquela amostra sobreviveu ao naufrágio.

Depois criei um gráfico de barras para identificar quantos sobreviventes haviam em cada classe de ticket. Notei que haviam muito mais sobreviventes dos passageiros da classe de ticket 1, da classe 2 estava bem equilibrado e a classe 3 sobreviveram menos de 1/3.

Dividi a idade em grupos de faixa etária a cada 10 anos: [0 a 10], [11 a 20], [21 a 30], [31 a 40], [41 a 50], [51 a 60], [61 a 70] e [71 a 80].

Criei um gráfico de barras para identificar qual a faixa etária que mais tinha sobreviventes e a proporção de homens e mulheres em cada faixa etária.

Por fim, criei um gráfico de barras para comparar os sobreviventes de cada faixa e classe de ticket. 

Criei uma história no Tableau baseado na sequência de criação dos gráficos para um grupo de WhatsApp de amigos. Dos 12 amigos, somente 2 responderam.

A partir da respostas dos dois amigos e revisão dos videos do "curso da Udemy - Data Science II - Semana 8 - Princípios de design", deixei os gráficos bem mais limpos para serem visualizados e com destaques para melhor entendimento da história.

Após 2 revisões do Time da Udacity, notei que havia uma diminuição na taxa de sobrevivência com o aumento da idade.



## Feedback

* O primeiro gráfico tá na mesma cor e o segundo está estreito (parece muito longo, tipo aquele gráfico do documentário "Uma verdade inconveniente", onde o cara que perdeu a eleição teve de subir num elevador para mostrar onde terminava o gráfico...Rsrsrs)

* O gráfico "Sobreviventes por classe e idade" está confuso, muito colorido




## Recursos

* [Dados do Titanic](https://www.google.com/url?q=https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59d54e6d_titanic-data/titanic-data.csv&sa=D&ust=1519745320238000&usg=AFQjCNFrqi3VCegLLwhKWn2iTnYTH3c6tg)

* [Kaggle - Titanic](https://www.kaggle.com/c/titanic)

* [Tableau Public Version](https://public.tableau.com)