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

Para cada conjunto de datos,  realizar el ensamblaje _de novo_ con [`Flye`](https://github.com/mikolmogorov/Flye) y un pulido con [`Medaka`](https://github.com/nanoporetech/medaka).

### Actividad 3
Realiza el control de calidad de los ensamblajes obtenidos con  [`CheckM2`](https://github.com/chklovski/CheckM2) y [`BUSCO`](https://busco.ezlab.org). Compara los valores de completitud y contaminación antes y después del pulido con Medaka. 


### Actividad 4
Calcula la profundidad por posición reclutando las lecturas utilizadas para ensamblar y las lecturas utilizadas para pulir con los siguientes ensamblajes:
- Rasusa 10x
- Rasusa 40x
- Filtlong 10x 
- Filtlong 40x

Para obtener la profundidad realiza un mapeo de las lecturas con [`Minimap2`](https://github.com/lh3/minimap2) y luego calcula la profundidad por posición con el comando [`samtools depth`](https://github.com/samtools/samtools). Posteriormente grafica la distribución de profundidad con algún lenguaje de programación como Python o R (1 gráfico por ensamblaje).


### Actividad 5
Selecciona cualquiera de los genomas ensamblados usando [`Bakta`](https://github.com/oschwengers/bakta). Utiliza el `bakta_plot` para la generación de un gráfico circular del genoma.