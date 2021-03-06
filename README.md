## English description

This is the repo of my solution to the *Demographic Data Analyzer* project from the **Data Analysis with Python** course from freeCodeCamp. The portuguese description is down below.

### Assignment

# Demographic Data Analyzer

In this challenge you must analyze demographic data using Pandas. You are given a dataset of demographic data that was extracted from the 1994 Census database. Here is a sample of what the data looks like:

|    |   age | workclass        |   fnlwgt | education   |   education-num | marital-status     | occupation        | relationship   | race   | sex    |   capital-gain |   capital-loss |   hours-per-week | native-country   | salary   |
|---:|------:|:-----------------|---------:|:------------|----------------:|:-------------------|:------------------|:---------------|:-------|:-------|---------------:|---------------:|-----------------:|:-----------------|:---------|
|  0 |    39 | State-gov        |    77516 | Bachelors   |              13 | Never-married      | Adm-clerical      | Not-in-family  | White  | Male   |           2174 |              0 |               40 | United-States    | <=50K    |
|  1 |    50 | Self-emp-not-inc |    83311 | Bachelors   |              13 | Married-civ-spouse | Exec-managerial   | Husband        | White  | Male   |              0 |              0 |               13 | United-States    | <=50K    |
|  2 |    38 | Private          |   215646 | HS-grad     |               9 | Divorced           | Handlers-cleaners | Not-in-family  | White  | Male   |              0 |              0 |               40 | United-States    | <=50K    |
|  3 |    53 | Private          |   234721 | 11th        |               7 | Married-civ-spouse | Handlers-cleaners | Husband        | Black  | Male   |              0 |              0 |               40 | United-States    | <=50K    |
|  4 |    28 | Private          |   338409 | Bachelors   |              13 | Married-civ-spouse | Prof-specialty    | Wife           | Black  | Female |              0 |              0 |               40 | Cuba             | <=50K    |


You must use Pandas to answer the following questions:

* How many people of each race are represented in this dataset? This should be a Pandas series with race names as the index labels. (`race` column)
* What is the average age of men?
* What is the percentage of people who have a Bachelor's degree?
* What percentage of people with advanced education (`Bachelors`, `Masters`, or `Doctorate`) make more than 50K?
* What percentage of people without advanced education make more than 50K?
* What is the minimum number of hours a person works per week?
* What percentage of the people who work the minimum number of hours per week have a salary of more than 50K?
* What country has the highest percentage of people that earn >50K and what is that percentage?
* Identify the most popular occupation for those who earn >50K in India. 

Use the starter code in the file `demographic_data_anaylizer`. Update the code so all variables set to "None" are set to the appropriate calculation or code. Round all decimals to the nearest tenth.

Unit tests are written for you under `test_module.py`.

### Development

For development, you can use `main.py` to test your functions. Click the "run" button and `main.py` will run.

### Testing 

We imported the tests from `test_module.py` to `main.py` for your convenience. The tests will run automatically whenever you hit the "run" button.

### Submitting

Copy your project's URL and submit it to freeCodeCamp.

### Dataset Source

Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.

-------------------------------------------------------------------------------------

## Descri????o em portugu??s

Esse ?? o reposit??rio com a minha solu????o para o projeto *Demographic Data Analyzer* do curso **Data Analysis with Python** do freeCodeCamp. 
A tradu????o ?? livre e feita por mim.

### Tarefa

# Demographic Data Analyzer

Neste desafio voc?? deve analisar dados demogr??ficos usando Pandas. Voc?? disp??e de um dataset que foi extra??do de um censo de 1994. Aqui est?? uma amostra de como os dados s??o:

|    |   age | workclass        |   fnlwgt | education   |   education-num | marital-status     | occupation        | relationship   | race   | sex    |   capital-gain |   capital-loss |   hours-per-week | native-country   | salary   |
|---:|------:|:-----------------|---------:|:------------|----------------:|:-------------------|:------------------|:---------------|:-------|:-------|---------------:|---------------:|-----------------:|:-----------------|:---------|
|  0 |    39 | State-gov        |    77516 | Bachelors   |              13 | Never-married      | Adm-clerical      | Not-in-family  | White  | Male   |           2174 |              0 |               40 | United-States    | <=50K    |
|  1 |    50 | Self-emp-not-inc |    83311 | Bachelors   |              13 | Married-civ-spouse | Exec-managerial   | Husband        | White  | Male   |              0 |              0 |               13 | United-States    | <=50K    |
|  2 |    38 | Private          |   215646 | HS-grad     |               9 | Divorced           | Handlers-cleaners | Not-in-family  | White  | Male   |              0 |              0 |               40 | United-States    | <=50K    |
|  3 |    53 | Private          |   234721 | 11th        |               7 | Married-civ-spouse | Handlers-cleaners | Husband        | Black  | Male   |              0 |              0 |               40 | United-States    | <=50K    |
|  4 |    28 | Private          |   338409 | Bachelors   |              13 | Married-civ-spouse | Prof-specialty    | Wife           | Black  | Female |              0 |              0 |               40 | Cuba             | <=50K    |


Voc?? deve usar Pandas para responder as seguintes quest??es:

* Quantas pessoas de cada ra??a est??o representadas nesse dataset? Isso deve ser uma Series com os nomes das ra??as de labels do ??ndice (coluna `race`).
* Qual a idade m??dia dos homens?
* Qual a porcentagem de pessoas que t??m um Bachelor's Degree?
* Qual a porcentagem de pessoas com educa????o avan??ada (`Bachelors`, `Masters`, ou `Doctorate`) que ganha mais de 50K?
* Qual a porcentagem de pessoas sem educa????o avan??ada que ganha mais de 50K?
* Qual o m??nimo de horas que uma pessoa trabalha por semana?
* Qual a porcentagem de pessoas que trabalham o m??nimo de horas por semana e ganham mais de 50K?
* Qual pa??s tem a maior porcentagem de pessoas que ganham >50K e qual ?? essa porcentagem?
* Identifique o ocupa????o mais popular para aqueles que ganham >50K na India. 

Use o c??digo inicial em `demographic_data_anaylizer`. Atualize o c??digo de modo que todas as vari??veis "None" tenham seu c??lculo/c??digo apropriado. Arrendode os decimais para o d??cimo mais pr??ximo.

Testes unit??rios est??o escritos para voc?? em `test_module.py`.

### Desenvolvimento

Para desenvolvimento, voc?? pode usar `main.py` para testar sua fun????o clicando em "run" para rodar `main.py`.

### Testando 

Os testes unit??rios para este projeto est??o em `test_module.py`. Importamos os testes de `test_module.py` para `main.py` por conveni??ncia. Os teste v??o rodar automaticamente quando clicar em "run".

### Submiss??o

Copie a URL do projeto e submeta-a ao freeCodeCamp.

### Fonte do dataset

Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.
