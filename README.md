# Formação Cientista de Dados

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/Adrianogvs/002-Projects-Data-Science/blob/master/LICENSE) 

## Índice

* Introdução
* Programação
* Estátiscica
* Mateática
* Machine Learning
* Data Wranglin / Munging
* Visualização De Dados e Comunicação
* Negócios e Gestão


## Introdução

Neste curso Formação Cientista de Dados, irei desenvolver algumas das principais habilidades e ferramentas que um Cientista de Dados deve conhecer.
Não será uma lista definida, mas uma recomendação baseada nas experiencias de alguns Cientistas de Dados e sites em Data Science Big Data.

Este curso não irá me tornar especialista nestas áreas supracitadas, mas irei ter noções e domínio de pelo menos um assunto de cada área. À media em que for avançado na área de Análise de Dados, terá noção que as ferramentas são muito parecidas e compreendendo bem os conceitos, será capaz de usar mais de uma sem dificuldade.

As habilidades e ferramentas são divididas em 7 áreas principais, sendo:
1. Programação de Computadores
2. Estatística
3. Matemática
4. Machine Learning
5. Data Wrangling/Munging
6. Visualização de Dados e Comunicação
7. Negócios e Gestão


## Programação

Programação será uma parte constante do seu trabalho como Cientista de Dados. Esta é uma habilidade fundamental que vai diferenciá-lo de um analista de negócios tradicional. Pode ser necessário escrever código para as mais variadas atividades durante o processo de Data Science e programação de computadores é hoje uma das mais valiosas habilidades, uma vez que os algoritmos estão governando nosso mundo. Trate esta habilidade como um investimento na sua carreira. Ambos R e Python são boas linguagens de programação para começar por causa de sua popularidade e apoio da comunidade. Seguem os principais tópicos que devem ser aprendidos.

### R
Pacote | Função
---|---
ggplot2 | Uma das melhores ferramentas para criação de visualização de dados
dplyr | Conjunto de funções para tratamento de datasets
Database | Diversos drivers para conexão R com bancos de dados Oracle,
Drivers | MongoDB e MySQL
stringr | Manipulação de texto reshape2 Pacote para mudar o formato de datasets
reshape2 | Pacote para mudar o formato de datasets

### Python
Pacote | Função
---|---
Numpy | Biblioteca Python para trabalho com grandes arrays multidimensionais de dados
Pandas | Inspirado em R, pacote para tratamento de datasets
Matplotlib | Visualização de Dados
Scikit-learn | Machine Learning
Seaborn | Visualização de gráficos estatísticos de alto nível

- Saber manipular planilhas Excel e arquivos csv é fundamental.


## Estatística

Um dos conceitos mais importantes de Estatística que você deve compreender é o de Amostragem. Ou seja, quando você coleta os dados, você está normalmente vendo apenas um subconjunto dos dados (você não coleta todos os dados do Facebook para sua análise, mas apenas um subconjunto, uma amostra). O conjunto completo de dados, seria a população. Medidas quantitativas que descrevem propriedades de uma amostra são conhecidos como estatísticas descritivas. Geralmente usamos as estatísticas coletadas na amostra, para inferir as propriedades de toda uma população. Isso é o que chamamos de Estatística Inferencial. Este é um dos principais conceitos por de trás de Machine Learning. 

Conceitos que você deve conhecer:
* Média, Mediana e Moda
* Distribuições de Dados (Normal, Exponencial, Binomial)
* Desvio Padrão e Variância
* Testes de Hipótese
* Testes de Significância
* Análise de Variância Além disso, design de experimentos:
* Testes A/B
* Controle de Variáveis e Grupos de Teste
* Níveis de Confiança


## Matemática

Em um nível básico, você deve estar confortável com álgebra linear do mesmo nível aprendida no ensino médio, como resolver equações e expressões matemáticas.

Conhecimento necessários:
* Álgebra Linear
* Manipulação de Matrizes
* Cálculo Integral


## Machine Learning 

O poder da Machine Learning é realmente significativo, à medida que trabalhamos com grandes conjuntos de dados. Você não vai ter que construir novos algoritmos de aprendizagem de máquina, pois eles já estão prontos, mas você deve compreender como eles funcionam, desde redução de dimensionalidade, até técnicas de aprendizagem supervisionada e não supervisionada.

Você deve saber quando usar algoritmos como redes neurais, support vector machines ou k-means. A teoria por trás destes algoritmos vai dar a você a confiança necessária para escolher a melhor opção de acordo com o conjunto de dados que você tiver em mãos.

Aprendizagem Supervisionada Aprendizagem supervisionada é útil, quando uma propriedade (chamada label) está disponível para os datasets de treino, mas não está presente em outros datasets (os datasets de teste), que então precisam ser previstos (a aplicação dos algoritmos nos datasets de teste, permitem medir a efetividade do aprendizado realizado com os datasets de treino). Note que o label pode ser um valor numérico e a diferença entre o valor previsto e o valor real, constitui uma medida de erro. 

Principais algoritmos de aprendizagem supervisionada:
* Regressão
* Regressão Logística
* Classificação com Naive Bayes
* Árvores de Decisão
* Redes Neurais
* Support Vector Machines

Aprendizagem Não-Supervisionada Em algumas situações, o objetivo não é prever um valor para uma propriedade específica e neste caso, aprendizagem supervisionada não seria a melhor opção.

Ao invés disso, o desafio é descobrir relacionamentos implícitos em um determinado dataset. O exemplo mais comum é o agrupamento de itens baseados em suas similaridades e diferenças (o que é chamado de clusterização).

Principais algoritmos de aprendizagem não-supervisionada:
* Algoritmos de clustering
* Principal Componente Analysis
* Singular Value Decomposition
* Independent Componente Analysis

Reinforcement Learning Algumas situações estarão no meio das duas opções anteriores. Estes tipos de
problemas de aprendizagem, são resolvidos com o Reinforcement Learning.


## Data Wrangling / Munging

A coleta, limpeza, organização e transformação os dados é uma parte menos nobre do processo de Data Science, porém é uma das mais importantes. Este
processo é conhecido como Data Wrangling ou Data Munging na comunidade
Data Science. Mesmo não sendo a parte mais nobre, ela vai ocupar cerca de 60% do trabalho de um Cientista de Dados.

Seus dados raramente estarão limpos e organizados e será preciso criar regras para garantir que a integridade dos dados seja mantida. Por exemplo: você pode obter dados de diferentes fontes, que contenham o nome do estado de São Paulo. Em cada cadastro, você pode encontrar: SP, São Paulo, Sao Paulo, SÃO PAULO, SãoPaulo. Como você vai padronizar os dados? Que regras vai adotar?
Como vai documentar? Como isso afeta o tempo de processamento e o resultado da sua análise? Não subestime esta fase. A qualidade dos seus inputs, vai determinar a qualidade dos seus outputs.

Você precisar conhecer:
* Como coletar dados de bancos de dados relacionais usando a linguagem SQL e como coletar dados de bancos de dados NoSQL 
* Como coletar dados do Hadoop, Spark
* Transformações matemáticas nos dados
* Manipulação de texto (usando expressões regulares)


## Visualização de Dados e Comunicação

Seu trabalho de análise está quase concluído, mas ainda não terminou. Você precisa agora ser capaz de converter dias ou semana de análise de dados, em apenas um ou dois gráficos e comunicar de forma efetiva seus resultados. Em alguns casos, será necessário contar a história por trás dos dados (storytelling). Se você for apresentar seus dados para outros Cientistas de Dados, um tipo de linguagem será usado, se a sua audiência for diretores e gerentes, sua linguagem
deverá ser outra, sempre adequada ao seu público.

Você deve conhecer:
* Visualização de Dados com Matplotlib e Seaborn (Python) e ggplot2 (Linguagem R)
* D3.js
* Tableau
* Precisa ter habilidades de Comunicação
* Técnicas de Apresentação


## Negócios e Gestão

O Cientista de Dados não vai dominar todas as áreas de negócios. Mas o conhecimento de business, vai permitir uma compreensão mais fácil dos problemas com os dados, o processo de limpeza e o que esperar como resultado.
Se você conhece bem a área de Marketing, vai saber que indicadores utilizar, que
dados precisam ser cruzados, que informações os gestores precisam e assim por
diante. Se a sua especialização for apenas técnica, seu trabalho como Cientista de
Dados pode ser comprometido. Nossa recomendação é que você dedique parte
do seu aprendizado a leitura de livros não técnicos, como livros sobre Marketing
ou Finanças. Esse conhecimento poderá ser usado muito além da análise de dados.

Recomendação:
* Conheça bem as boas práticas de Gestão de Projetos
* Leia livros sobre negócios
* Procure compreender os principais indicadores usados em áreas chaves como RH, Finanças, Marketing e Vendas
* Acesse frequentemente sites especializados em negócios, como o site do Valor Econômico, por exemplo (www.valor.com.br).

