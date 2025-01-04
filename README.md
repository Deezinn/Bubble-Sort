# Bubble Sort

O **Bubble Sort** é notavelmente lento, mas é o mais simples dos algoritmos de ordenação.

---

## Funcionamento

1. **Comparação de dois números:**
   - Se o número à esquerda for maior, os elementos devem ser trocados.

2. **Deslocamento:**
   - O algoritmo desloca-se uma posição à direita após cada comparação.

3. **Bolhas no vetor:**
   - À medida que o algoritmo avança, os itens maiores "surgem como uma bolha" na extremidade superior do vetor.

---

## Análise de Comparações

- Para um vetor com 10 elementos:
  - Na **primeira passagem**, realiza **9 comparações**.
  - Na **segunda passagem**, realiza **8 comparações**.
  - Na **terceira passagem**, realiza **7 comparações**.
  - E assim por diante, seguindo o padrão: \( n-1, n-2, n-3 \).

### Exemplo com 10 itens:

Número de comparações:
\[ 9 + 8 + 7 + 6 + 5 + 4 + 3 + 2 + 1 = 45 \]

---

## Trocas

- Há **menos trocas do que comparações**, pois dois elementos só serão trocados se necessário.

