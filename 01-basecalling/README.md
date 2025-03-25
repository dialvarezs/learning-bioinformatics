## Actividad
Realizar el basecalling con la herramienta Dorado utilizando los tres modelos disponibles (`fast`, `hac` y `sup`) y comparar los resultados en términos de calidad y tiempo de ejecución.

Para evaluar la calidad de las lecturas, puedes usar la herramienta `SeqKit`:
```bash
seqkit stats *
```

Si los resultados están en formato `BAM`, utiliza Samtools para convertirlos a `FASTQ`: