# 📊 Calculadora de Média Olímpica de Atletas

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

## 📜 Descrição

Este projeto consiste em um script em JavaScript que calcula a "média válida" das notas de uma lista de atletas. Seguindo uma regra comum em competições de ginástica e saltos ornamentais, o cálculo descarta a maior e a menor nota de cada atleta antes de calcular a média das notas restantes.

O script processa uma lista pré-definida de atletas e exibe os resultados formatados diretamente no console.

## ✨ Funcionalidades

-   Processa uma lista de atletas contida em um array de objetos.
-   Para cada atleta, ordena suas notas para identificar a maior e a menor.
-   Descarta a maior e a menor nota do cálculo.
-   Calcula a média aritmética das notas restantes.
-   Exibe um relatório final no console contendo o nome do atleta, suas notas originais e a média válida calculada.

## 🛠️ Tecnologias Utilizadas

-   **JavaScript:** Linguagem principal utilizada para a lógica do script.
-   **Node.js:** Ambiente de execução para rodar o script JavaScript fora do navegador.

## ⚙️ Pré-requisitos

Para executar este projeto, você precisará ter o **Node.js** instalado em sua máquina. Para verificar se você o tem instalado, abra seu terminal e digite:

```bash
node -v