# Análise das Temperaturas Máximas Médias do Brasil — INMET (1991–2020)

Análise exploratória das Normais Climatológicas do INMET para o período de 1991–2020, 
explorando a temperatura máxima média entre meses, estados, regiões e estações 
meteorológicas do Brasil.

## 📚 Fonte dos dados

Instituto Nacional de Meteorologia (INMET) — Normais Climatológicas do Brasil 1991–2020.
[portal.inmet.gov.br/normais](https://portal.inmet.gov.br/normais)

Os dados correspondem à temperatura máxima média compensada, mensal e anual, de 146 
estações meteorológicas espalhadas pelo país.

## 🛠️ Tecnologias

- Python
- pandas
- matplotlib
- geobr (para o mapa por estado)
- Google Colab

## 🔍 O que foi feito

- Limpeza dos dados: tratamento de valores ausentes (marcados como "-"), conversão de 
  colunas para formato numérico e verificação de duplicidades
- Temperatura máxima média por mês, por estado e por região
- Mapa do Brasil colorido por temperatura máxima média estadual
- Ranking das 10 estações mais quentes e das 10 mais frias
- Distribuição das temperaturas máximas médias anuais entre as estações

## 📊 Principais insights

- Dezembro tem a maior temperatura máxima média mensal; julho, a menor
- Roraima é o estado com maior temperatura máxima média; Santa Catarina, o menor
- Na comparação entre regiões: Norte > Nordeste > Centro-Oeste > Sudeste > Sul
- Floriano (PI) tem a maior temperatura máxima média anual entre as estações (28,3 °C)
- São Joaquim (SC) tem a menor (13,5 °C)
- Amplitude de 14,8 °C entre o maior e o menor valor observado

## ▶️ Como executar

O notebook foi feito para rodar no Google Colab. Basta abrir o arquivo `.ipynb`, 
rodar as células em ordem e fazer upload do arquivo `Normal-Climatologica-TMAX.xlsx` 
quando solicitado — o arquivo original está disponível em `data/Normal-Climatologica-TMAX.xlsx` 
neste repositório.
