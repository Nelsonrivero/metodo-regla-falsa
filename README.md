# Método de la Regla Falsa

Este repositorio contiene una implementación en Python del método de la regla falsa para encontrar la raíz de una función en un intervalo dado. Además, incluye la funcionalidad de exportar las iteraciones del método a un archivo Excel.

## Uso

Para utilizar este código, sigue los siguientes pasos:

1. Clona este repositorio en tu máquina local.
2. Ejecuta el script `regla_falsa.py`.
3. Ingresa los extremos del intervalo cuando se te solicite.
4. El programa encontrará la aproximación de la raíz y creará un archivo Excel llamado `iteraciones_regla_falsa.xlsx` que contiene las iteraciones del método.

## Requisitos

- Python 3.x
- Biblioteca `openpyxl`

## Ejemplo

Supongamos que queremos encontrar la raíz de la función `f(x) = x^2 - 2`. Podemos ejecutar el script proporcionando los extremos del intervalo.

```python
def ejemplo_funcion(x):
    return x**2-2
