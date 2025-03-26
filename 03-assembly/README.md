## Datos para ensamblar
- Nicolás: PSAE-806
- Thomas: PSAE-956

Tamaño de genoma (ambos): 7Mb aprox.

### Actividad 1
Realizar el filtrado y control de calidad de los datos de secuenciación. Posteriormente, llevar a cabo un ensamblaje de `novo` con [`Flye`](https://github.com/mikolmogorov/Flye) y un pulido con [`Medaka`](https://github.com/nanoporetech/medaka).

### Actividad 2
Luego del control de calidad, aplicar un muestreo de las lecturas utilizando [`Filtlong`](https://github.com/rrwick/Filtlong) y [`Rasusa`](https://github.com/mbhall88/rasusa) para obtener conjuntos de datos con las siguientes profundidades :
- 10x
- 20x
- 30x 
- 40x

Para cada conjunto de datos,  realizar el ensamblaje de `novo` con [`Flye`](https://github.com/mikolmogorov/Flye) y un pulido con [`Medaka`](https://github.com/nanoporetech/medaka).
