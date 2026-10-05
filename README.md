# Hábitos alimentares na pandemia de COVID-19

**Projeto I · Análise de Dados · Especialização em Estatística e Ciência de Dados**

👉 **Apresentação:** https://camisaj.github.io/projeto1-analise-de-dados/

Apresentação em slides feita em [Quarto](https://quarto.org) (formato `revealjs`) com uma análise exploratória e visual de como os hábitos alimentares mudaram durante a pandemia de COVID-19.

## Dados

Questionário online aplicado em 2022 por alunas da pós-graduação em Nutrição da UFF, respondido por **2.359 pessoas** e com **29 variáveis**: perfil sociodemográfico, condições vividas na pandemia, peso e altura e mudanças no consumo de 14 itens alimentares.

## O que fiz

- **Representatividade:** comparei a amostra com a população brasileira (IBGE: Censo 2022 e PNAD Contínua Educação 2025).
- **Agrupamento dos alimentos:** usei a correlação de Spearman entre os 14 itens alimentares e reuni os que andam juntos em 7 grupos (in natura, proteína animal, carboidratos, ultraprocessados, álcool, água e delivery).
- **Mudanças no consumo:** descrevi as mudanças por grupo de alimento e cruzei com idade, gênero, isolamento social, dificuldade financeira, acompanhamento nutricional, IMC e renda.

A análise é descritiva: tabelas automáticas, gráficos estáticos e cruzamentos entre variáveis.

## Principais achados

- **3 em cada 4** pessoas (73,5%) relataram alteração na alimentação, principalmente jovens, mulheres e quem fez isolamento social.
- **A idade define a direção da mudança:** os mais jovens aumentaram carboidratos e ultraprocessados; quem tem 60 anos ou mais reduziu ultraprocessados e aumentou o consumo de alimentos in natura.
- **A dificuldade financeira piorou a dieta:** 50% de quem passou por dificuldade financeira reduziu o consumo de proteína animal, contra 17% de quem não passou.
- **Acompanhamento nutricional:** quem já consultou nutricionista foi mais para alimentos in natura e menos para carboidratos e ultraprocessados.

## Limitações

Amostra de conveniência: mais mulheres, pessoas brancas e com pós-graduação do que a população brasileira. As mudanças são autorrelatadas e não informam quantidade. Os resultados mostram associações, não causas.

## Ferramentas

R e Quarto, com os pacotes `openxlsx`, `dplyr`, `tidyr`, `forcats`, `ggplot2`, `ggstats`, `ggrepel`, `scales`, `RColorBrewer`, `corrplot`, `fmsb`, `gtsummary` e `gt`.

## Sobre este repositório

Este repositório contém apenas a versão publicada dos slides (HTML gerado pelo Quarto), servida pelo GitHub Pages.

## Autoria

Camila Sajnin
