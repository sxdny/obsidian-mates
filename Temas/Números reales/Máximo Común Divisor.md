# Máximo común divisor.
---
El máximo común divisor es el mayor de los divisores en común de 2 o más números.

Para sacar el MCD de dos números, tendremos que:

1. Dividir entre el número entre el número más pequeño posible hasta que no se puede dividir más.
2. Después, sacaremos los *comúnes* con *menor* exponente y haremos el cálculo.

## Ejemplo:
---
Saber el máximo común divisor de $18$ y $24$:

Hacemos las divisiones:

| Nuúmero 18  | 18              | 2   | Número 24   | 24              | 2   |
| ----------- | --------------- | --- | ----------- | --------------- | --- |
|             | 9               | 3   |             | 12              | 2   |
|             | 3               | 3   |             | 6               | 2   |
|             | 1               |     |             | 3               | 3   |
|             |                 |     |             | 1               |     |
| Equivale a: | $3^{2}\times 2$ |     | Equivale a: | $2^{3}\times 3$ |     |

Ahora, sacamos los *comúnes* con *menor exponente*: $2 \times 3 = 6$

El MCD de 18 y 24, es 6.

## ¿Qué pasa si no coinciden?
---
En caso de que no coincida ningún número, el MCD será 1.

