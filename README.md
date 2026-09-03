
# Cyclistic - Estudo de caso

Análise de como membros anuais e passageiros casuais usam as bicicletas da Cyclistic de forma diferente, com o objetivo de embasar uma estratégia de marketing para converter passageiros casuais em membros anuais.

## Dados

Últimos 12 meses de viagens (agosto/2025 a julho/2026) do sistema de bicicletas compartilhadas Divvy (Chicago), disponibilizados publicamente pela Motivate International Inc: https://divvy-tripdata.s3.amazonaws.com/index.html

Os arquivos `.csv` não estão incluídos neste repositório. Para reproduzir a análise, baixe os arquivos do período desejado no link acima e coloque-os na pasta `data/tcc/`.

## Como rodar

```bash
pip install -r requirements.txt
jupyter notebook main.ipynb
```

## Estrutura do notebook

- Introdução e tarefa de negócio
- Limpeza e preparação dos dados
- Processamento (loop mensal com cálculo de duração, distância, dia da semana e estações)
- Visualizações
- Resumo da análise
- Recomendações

## Principais achados

- Membros concentram uso em dias úteis, partindo majoritariamente de estações no distrito comercial (Loop); casuais concentram uso em fins de semana, partindo de pontos turísticos/recreativos (Navy Pier, orla do lago).
- Parte dos membros adota comportamento tipo-casual nos fins de semana, migrando para estações turísticas.
- Ambos os grupos preferem bicicleta elétrica à clássica, mesmo com distância percorrida semelhante entre os dois tipos — a diferença está na velocidade, não na distância.
- Forte sazonalidade: queda no volume no inverno (dez-fev), pico no verão (jun-jul).
