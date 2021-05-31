![Drug Discovery Image](https://www.viomundo.com.br/wp-content/uploads/2019/04/sus-pixabay.png)

# Projeto Módulo 1 - Bootcamp Data Science Aplicada - Alura
---

Opa!

Seja bem vindo ao meu repositório, nele, será abordado as informações que envolvem o desenvolvimento do projeto referente ao Módulo 1 do Bootcamp de Data Science Aplicada, ministrado pela **Alura**

## 🤿 Escopo do Projeto
---

Este projeto utiliza dados de dois portais diferente do governo brasileiro. 

O primeiro é o [DataSUS](http://www2.datasus.gov.br/DATASUS/index.php?area=0202&id=11633&VObj=http://tabnet.datasus.gov.br/cgi/deftohtm.exe?sih/cnv/qi), que fornece diversos dados referentes à saúde no SUS (Sistema Público de Saúde).
O segundo, vêm diretamente do [SIDRA](https://sidra.ibge.gov.br/tabela/1737), ele é um portal que disponibiliza dados do IBGE (Instituto Brasileiro de Geografia e Estatística).

Ahh, e só uma obsservação, os dados utilizados foram filtrados para períodos de antes da pandemia do COVID-19, portanto são dados que estão em uma situação mais normalizada.

### 🩺 Dados do DataSUS
---

No portal do DataSUS foram utilizado os dados referentes ao **valor médio de AIH** (autorização de internação hospitalar) das unidades do SUS em todo o Brasil, durante o período de 2008 a 2020.

### 📈 Índice IPCA
---

Já no portal do IBGE, foram utilizados os dados do índice IPCA acumulado dos últimos 12 meses, durante o período de 2008 a 2020.

## 📍 Objetivo
---

O objetivo deste projeto é realizar uma análise exploratória dos dados citados anteriormente, a fim de corrigir o **valor médio de AIH** pela **inflação** ocorrida no período citado, podendo distinguir o **preço médio da AIH** e **valor médio AIH** corrigido pela inflação.

## 🎲 Resultados
---

Durante o processo de análise dos dados de **valor médio** foi identificado que o estado do **Paraná** tinha os maiores valores nos últimos tempos, portanto, utilizamos os dados desse estado para corrigir os valores com a inflação.
Aplicando o índice IPCA sobre o período de 2008 a 2020 referente ao estado, plotando um gráfico foi possível notar o **preço** (valor médio) que havia sido declarado, e agora, também o **real valor** (valor médio corrigido) do que foi cobrado da AIH.

O gráfico a seguir representa o resultado deste projeto, na qual podemos perceber que, quanto maior a distância entre as linhas, mais "caro" foi a média do valor das AIH sobre o bolso do cliente (seja ele governo ou cidadão).

![image info](/ipca.bmp)
