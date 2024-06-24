# Ordenador de Array e Remoção de Duplicatas em JavaScript

Este é um script em JavaScript que ordena um array de números e remove duplicatas, garantindo que apenas os valores únicos sejam mantidos.

## Funcionalidades

O script realiza as seguintes operações:

- **Ordenação do Array:** Utiliza um algoritmo de ordenação simples para ordenar os números em ordem crescente.
- **Remoção de Duplicatas:** Após a ordenação, percorre o array para remover elementos duplicados mantendo apenas a primeira ocorrência de cada valor.

## Como usar

Para utilizar o script, siga os passos abaixo:

1. **Defina o array de números:** Edite a variável `numeros` no código para incluir os números desejados. Por exemplo:
   ```javascript
   let numeros = [4, 3, 1, 5, 5, 7, 2, -47, 2001];
   ```

2. **Execute o script:** Abra o console do seu navegador ou execute o arquivo JavaScript em um ambiente Node.js para ver os resultados.

## Exemplo

Suponha que você tenha o seguinte array:
```javascript
let numeros = [4, 3, 1, 5, 5, 7, 2, -47, 2001];
```

Ao executar o script, você verá o seguinte resultado no console:
```
[-47, 1, 2, 3, 4, 5, 7, 2001]
```

Neste exemplo, o array foi ordenado em ordem crescente e as duplicatas foram removidas, resultando em um array com valores únicos.

## Notas

- O script assume que todos os elementos no array são números.
- Este script é útil para ordenar um conjunto de números e garantir que não haja duplicatas presentes no resultado final.
