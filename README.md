Proyecto: seguimiento_1

El formato GFF3 (General Feature Format version 3) consta de 9 columnas separadas por tabulaciones. A continuación, se describe el contenido de cada columna:


| **Columna**   | **Descripción**                                                                                                                                                   |
|---------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Seqid**     | Identificación de la secuencia (por ejemplo: `ctg123`).                                                                                                            |
| **Source**    | Origen del *feature*, como el nombre del software o base de datos que lo generó (ej.: Genbank, Genescan, etc.).                                                   |
| **Type**      | Tipo de elemento genético. Utiliza términos de la Ontología de Secuencia (ej.: `SO:0000110`).                                                                     |
| **Start / End** | Posición inicial y final del elemento en la secuencia. Deben ser enteros positivos. Por convención, se cumple que `start ≤ end`.                                |
| **Score**     | Valor numérico en punto flotante que representa la confianza de la predicción (como valores *p* o *e*).                                                            |
| **Strand**    | Indica en qué hebra del ADN se encuentra el *feature* (`+` o `-`).                                                                                                 |
| **Phase**     | Solo para características tipo **CDS**. Especifica si se deben omitir 0, 1 o 2 bases antes del primer codón. Se usa para mantener el marco de lectura.             |
| **Attributes**| Metadatos en formato `tag=value`, como el ID del gen o su nombre. 

### 3) Información del organismo

#### *Rhinolophus ferrumequinum*  
![Murciélago de herradura mayor](https://github.com/user-attachments/assets/3270925a-3802-44de-a837-78f7b63cf801)

- **Nombre común:** Murciélago de herradura mayor.
- **Origen del nombre:** Proviene de una estructura en forma de herradura en la nariz, utilizada para emitir ultrasonidos mediante ecolocalización.
- **Distribución geográfica:** Europa, norte de África y Asia.
- **Hábitats comunes:** Bosques, cuevas, minas, túneles y edificios antiguos.
- **Comportamiento:** Es un animal nocturno y altamente dependiente de la ecolocalización para orientarse y cazar.

**Dato curioso:** Puede modular la frecuencia de su ecolocalización con gran precisión, permitiéndole detectar insectos en ambientes con muchos obstáculos.

Resultados:

i. ¿Cuántos features contiene el archivo?

22

ii. ¿Cuántas regiones de la secuencia (cromosomas) contiene el archivo?

134

iii. ¿Cuántos genes están listados en el organismo?

22172

iv. Top 10 tipos de features más anotados (columna 3):

| #  | Feature               | Frecuencia |
|----|------------------------|------------|
| 1  | exon                  | 387,739    |
| 2  | CDS                   | 369,518    |
| 3  | biological_region     | 110,127    |
| 4  | mRNA                  | 33,636     |
| 5  | five_prime_UTR        | 31,810     |
| 6  | three_prime_UTR       | 22,287     |
| 7  | gene                  | 19,533     |
| 8  | ncRNA_gene            | 2,011      |
| 9  | snRNA                 | 907        |
| 10 | pseudogene            | 628        |



