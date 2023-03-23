# Projeto: Cálculo da probabilidade de germinação de sementes infectadas

## Objetivo

Este projeto tem como objetivo calcular a probabilidade de uma semente infectada germinar com base nas informações disponíveis em um experimento. O experimento envolve a disseminação de 320 sementes de aveia após serem contaminadas com um fungo. A pesquisa deseja saber qual a probabilidade &Theta; de uma semente infectada germinar. Infelizmente o número exato de sementes germinadas não pode ser avaliado, mas sabemos que menos de 25 sementes germinaram.

## Linguagem e bibliotecas

O projeto foi desenvolvido usando a linguagem Python e as seguintes bibliotecas:

- `numpy`: usada para manipulação de arrays e cálculos numéricos.
- `scipy`: usada para cálculos estatísticos e científicos.
- `matplotlib`: usada para criação de gráficos e visualização dos resultados.

## Solução

A solução encontrada envolve o uso do método da máxima verossimilhança para estimar a probabilidade &Theta; de uma semente infectada germinar. O código calcula os valores da função de verossimilhança para cada valor possível de &Theta; e encontra a estimativa que maximiza essa função. Essa estimativa representa o valor mais provável para &Theta; com base nas informações disponíveis no experimento.

Os resultados do programa podem ser visualizados em um gráfico que mostra os valores da função de verossimilhança em função de &Theta;. Você pode usar essa visualização para avaliar a incerteza associada à estimativa e tomar decisões com base nas informações disponíveis.
