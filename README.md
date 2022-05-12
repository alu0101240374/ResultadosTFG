## Resultados TFG provisionales 12/05/2022

En el directorio 'Fotos/' se encuentran las fotos de los patrones reconocidos como doble techo, desde el 12/05/2022 hasta el 01/01/2021

Todas las fotos siguen el siguiente formato de nombre: NombreDeLaCompañia_TamañoDeVentana_SaltoDeVentana

SaldoDeVentana significa el tamaño del incremento que es aplicado al movimiento de la ventana dentro del bucle que recorre el histórico de datos.

### Resultados de Accuracy

Se creó una base de datos Test, formada por 6 patrones definidos como doble techo, y 4 como resto.

Los resultados según el tamaño de la ventana fueron los siguientes:

- Tamaño 32:  90% accuracy (Etiqueta como doble techo un resto)
- Tamaño 37: 100% accuracy
- Tamaño 48: 100% accuracy
- Tamaño 52: 100% accuracy
- Tamaño 60: 80% accuracy (Etiqueta como doble techo un resto y un resto como doble techo)