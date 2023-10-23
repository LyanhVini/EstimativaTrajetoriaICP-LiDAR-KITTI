# EstimativaTrajetoriaICP-LiDAR-KITTI

![LiDAR Point Cloud]

Este repositório contém uma implementação personalizada do algoritmo "Iterative Closest-Points (ICP)" para estimar a trajetória de um veículo com base em nuvens de pontos (point clouds) obtidas de varreduras LiDAR do KITTI DATASET.

## Objetivo

O objetivo principal deste projeto é desenvolver uma implementação do algoritmo ICP sem depender de bibliotecas de terceiros. A trajetória final do veículo é estimada com base em 30 scans LiDAR fornecidos no KITTI DATASET, com a trajetória começando no primeiro scan.

## Informações 

1. **Implementação do Algoritmo ICP:** O código-fonte da implementação personalizada do algoritmo ICP está disponível neste repositório. A implementação visa mostrar a corretude do algoritmo.

2. **Dados do KITTI DATASET:** Os 30 scans LiDAR do KITTI DATASET estão incluídos no repositório para fins de demonstração.

3. **Ground-Truth em Formato .npy:** O arquivo .npy contém uma matriz de transformação em coordenadas homogêneas para cada uma das 30 posições do veículo, permitindo a validação da estimativa da trajetória.

## Instruções de Uso

- Clone este repositório em sua máquina local.
- Utilize o código-fonte fornecido para estimar a trajetória do veículo com base nos scans LiDAR e compare os resultados com o ground-truth.

## Requisitos

- Python
- NumPy (para carregar e analisar o ground-truth)

Este projeto é uma oportunidade de aprender e aprimorar as habilidades de processamento de dados LiDAR e algoritmos de registro de nuvens de pontos, além de promover a compreensão da estimativa da trajetória de veículos a partir de dados sensoriais.

