# Product-Recommendations-For-IA-Project

[![Google Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sir20PiR/Product-Recommendation-For-IA-Project/blob/main/Sistema_de_Recomenda%C3%A7%C3%A3o.ipynb)

Este projeto aborda os conceitos básicos da implementação da biblioteca Surprise do Python e da média ponderada do IMDB para a predição de produtos, no qual utilizamos mais de 3 heurísticas de **Inteligência Artificial** para solucionar vários problemas relacionados a diferentes tipos de sistemas de recomendação. Disciplina de 64 horas, Inteligência Artificial ministrada pelo [Prof. Msc. Frederico Santos de Oliveira](https://github.com/freds0), no qual atua na área de IA.
## Descrição do projeto

Nosso projeto é um sistema de recomendação baseado em popularidade e em filtragem colaborativa. Vamos dividir em duas partes para que fique mais fácil a compreensão.

###  Algoritmo Baseado em Popularidade

Vamos utilizar para a primeira heurística o _Popular Based       Recommender System, então_ criamos um algoritmo que desse aos       usuários uma estimativa geral dos produtos a serem mostrados a eles, podemos chamar de trending, ou seja, o que está mais popular no      momento, para isso utilizaremos um método simples de classificação   que é por meio de média ponderada, utilizada no sistema de       recomendação do website IMDB. A sacada aqui foi utilizar métodos de  filtragem, na mesma abordagem assumida pelo algoritmo do IMDB de     forma que pudesse ser aplicada na Amazon.

### Algoritmos de Filtragem Colaborativa
Filtragem colaborativa é o processo de filtrar informação ou padrões usando técnicas que envolvem colaboração de múltiplos agentes, pontos de vista, fontes de dados, etc.
Aqui utilizamos diferentes métodos de forma que o utilizado fosse o que apresentasse o menor erro. Sendo cada método, um algoritmo diferente. 
O primeiro deles foi o KNN(K-Nearest-Kneighbors), este método é um dos mais clássicos e mais implementados algoritmos de filtragem colaborativa, depois SlopeOne e por último coclustering. De forma geral, a maioria deles advém do teorema de Bayes.

## Como rodar?
Apenas abra aba do Google Colab [![Google Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sir20PiR/Product-Recommendation-For-IA-Project/blob/main/Sistema_de_Recomenda%C3%A7%C3%A3o.ipynb) e clique em Executar Tudo na aba de Ambientes de Execução.

Se preferir baixe o arquivos, crie um ambiente virtual, instale os requirementos e rode no Jupyter Notebook.

## Créditos e Referências
SANTOS, Gustavo Rezende. **Building a Recommendation System**. [_S. l._], 27 out. 2020. Disponível em: https://github.com/gurezende/Studying/blob/master/MIT/Module4/Recommendation_Project.ipynb. Acesso em: 20 jun. 2022.

SANTOS, Gustavo Rezende. **Criando Sistemas de Recomendação em Python**. [_S. l._], 1 nov. 2020. Disponível em: https://medium.com/data-hackers/criando-sistemas-de-recomenda%C3%A7%C3%A3o-em-python-ef350f601e3d. Acesso em: 20 jun. 2022.

SIDHU, Kuldeep Singh. **Recommendation System**. [_S. l._], 6 maio 2020. Disponível em: https://github.com/singhsidhukuldeep/Recommendation-System/blob/master/Building_Recommender_System_with_Surprise.ipynb. Acesso em: 30 jun. 2022.

LI, Susan. **Building and Testing Recommender Systems With Surprise, Step-By-Step**. [_S. l._], 26 dez. 2018. Disponível em: https://towardsdatascience.com/building-and-testing-recommender-systems-with-surprise-step-by-step-d4ba702ef80b. Acesso em: 10 jul. 2022.

DIAS, Tiago. **Sistemas de Recomendações com Surprise**. [_S. l._], 16 dez. 2020. Disponível em: https://dadosaocubo.com/sistemas-de-recomendacoes-com-surprise/. Acesso em: 21 jun. 2022.

SEEDA, Pathairush. **A Complete Guide To Recommender Systems — Tutorial with Sklearn, Surprise, Keras, Recommenders**. [_S. l._], 13 out. 2021. Disponível em: https://towardsdatascience.com/a-complete-guide-to-recommender-system-tutorial-with-sklearn-surprise-keras-recommender-5e52e8ceace1. Acesso em: 14 jun. 2022.

Ni, Jianmo. **Amazon Review Data**. [_S. l._], out. 2018. Disponível em: [https://nijianmo.github.io/amazon/index.html](https://nijianmo.github.io/amazon/index.html). Acesso em: 9 jul. 2022.

LOPES, Rafael Barbolo. **Sistemas de Recomendação com Inteligência Artificial**.

SCHIAVINI, Rodrigo. **O que é um sistema de recomendação para e-commerce? Tudo sobre o tema!**. [_S. l._], 28 fev. 2019. Disponível em: https://www.smarthint.co/o-que-e-um-sistema-de-recomendacao/#:~:text=O%20principal%20objetivo%20de%20um,bons%20resultados%20para%20o%20neg%C3%B3cio. Acesso em: 10 jul. 2022.
