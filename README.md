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
```
Se o comando retornar um número de versão (ex: `v20.11.0`), você está pronto. Caso contrário, baixe e instale o Node.js a partir do [site oficial](https://nodejs.org/).

## 🚀 Como Executar o Projeto

1.  Clone este repositório ou simplesmente salve o arquivo `.js` (ex: `notas-atletas.js`) em uma pasta no seu computador.
2.  Abra um terminal na pasta onde você salvou o arquivo.
3.  Execute o script com o seguinte comando:

    ```bash
    node notas-atletas.js
    ```

## 📝 Saída Esperada

Após a execução do script, você verá a seguinte saída no seu terminal:
Atleta: Cesar Abascal
Notas Obtidas: 10,9.34,8.42,10,7.88
Média Válida: 9.253333333333332

Atleta: Fernando Puntel
Notas Obtidas: 8,10,10,7,9.33
Média Válida: 9.11

Atleta: Daiane Jelinsky
Notas Obtidas: 7,10,9.5,9.5,8
Média Válida: 9

Atleta: Bruno Castro
Notas Obtidas: 10,10,10,9,9.5
Média Válida: 9.833333333333334