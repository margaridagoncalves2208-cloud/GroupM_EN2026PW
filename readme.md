# GroupM_EN2026PW

## Questão de Estudo
Que fatores determinam o tamanho das lapas?

## Descrição
Este repositório contém todo o material do trabalho prático da disciplina de Ecologia Numérica: dados de campo, scripts de análise, resultados e documentação. O objetivo do projeto é identificar e modelar os fatores ambientais e biológicos que influenciam o tamanho das lapas (Patella spp.) em amostras recolhidas.

## Estrutura do repositório
- data/
  - raw/           -> dados brutos recolhidos no campo
  - processed/     -> dados limpos e prontos para análise
- scripts/
  - preprocessing/ -> scripts para limpeza e preparação dos dados
  - analysis/      -> scripts para análise estatística e modelos
  - figures/       -> scripts que geram figuras e tabelas
- results/         -> saídas de análise (figuras, tabelas, modelos treinados)
- docs/            -> documentação adicional e anexos
- readme.md        -> este ficheiro

## Dados
Descreva aqui os ficheiros de dados principais: variáveis medidas (comprimento, largura, massa, local, tipo de substrato, marés, temperatura, etc.), unidades, e qualquer nota sobre o processo de recolha.

## Metodologia (resumo)
1. Inspeção e limpeza dos dados (scripts em scripts/preprocessing).
2. Análise exploratória (scripts em scripts/analysis).
3. Modelagem estatística para identificar variáveis preditoras do tamanho das lapas.
4. Validação e visualização dos resultados (scripts em scripts/figures).

## Requisitos
- R >= 4.0 ou Python >= 3.8 (especifique qual linguagem/ambiente usam)
- Pacotes (ex.: tidyverse, lme4, ggplot2) ou (pandas, numpy, scikit-learn, matplotlib)

## Instalação e execução (exemplo em R)
1. Clone o repositório:
   git clone https://github.com/margaridagoncalves2208-cloud/GroupM_EN2026PW.git
2. Instale as dependências em R:
   install.packages(c("tidyverse","lme4","ggplot2"))
3. Execute os scripts de preprocessing:
   Rscript scripts/preprocessing/01_clean_data.R
4. Execute as análises:
   Rscript scripts/analysis/02_modeling.R

(Adapte as instruções consoante a linguagem e os ficheiros reais do repositório.)

## Como contribuir
- Adicione scripts à pasta scripts e documente mudanças no topo dos ficheiros.
- Abra issues para discutir novas análises ou problemas com os dados.

## Autoras
- Margarida Gonçalves - 64714
- Madalena Rosa - 61959
- Sara Santos - 61552

## Licença
Indique aqui a licença do trabalho (por exemplo: CC BY-SA 4.0, MIT, ou outra).

## Contacto
Para dúvidas ou sugestões: margaridagoncalves@exemplo.com
