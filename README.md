# seguimiento_1

**1)** a. 
    El formato GFF3 consta de 9 columnas espaciadas por Tab, las columnas y su información contenida:
   - **Seqid**: Identificación de la secuencia.
   - **Source**: Origen del Feature, nombre del software o database donde se generó el feature.
   - **Type**: Tipo de elemento genético presente, usando términos de la Ontología de Secuencia.
   - **Start/End**: Posición inicial y final de un elemento biológico dentro de la secuencia, los valores deben ser enteros positivos y por convención --> start <=                        end.
   - **Score**: Representa un valor numérico, en punto flotante, que evalúa la confianza en la predicción usando valores p ó e.
   - **Strand**: Indica en qué hebra del ADN se encuentra el Feature.
   - **Phase**: Solo para características CDS, especifica si debe saltarse 0, 1 o 2 bases antes de comenzar el primer codón. Se usa para mantener el marco de lectura                  correcto.
   - **Attributes**: Incluye metadatos en formato tag=value, como el ID del gen o su nombre.

**3)**  
a. **Rhinolophus ferrumequinum:** 
- Comunmente llamado Murciélago de herradura mayor, su nombre proviene de una estructura característica en la nariz con forma de herradura, la cual usa para emitir ultrasonidos y orientarse por ecolocalización.
- Este animal se encuentra en Europa, el norte de África y Asia.
- Sus habitats comunes son zonas boscosas, cuevas, minas, edificios antiguos o túneles.
- Es un animal nocturno y es muy dependiente de la ecolocalización de alta precisión para cazar en vuelo.
- Como dato curioso, este murciélago es uno de los pocos que puede modular la frecuencia de su ecolocalización con mucha precisión, lo que le permite detectar incluso insectos en ambientes con muchos obstáculos.

- i. **# ¿Cuantos features contiene el archivo?**
    22
- ii. **# ¿Cuántas regiones de la secuencia (cromosomas) contiene el archivo?**
    134
- iii.****
- iv. **# ¿Cuál es el top 10 de tipo de features (columna 3) más anotados en el genoma?**
    - 387739  exon
    - 369518  CDS
    - 110127  biological_region
    - 33636   mRNA
    - 31810   five_prime_UTR
    - 22287   three_prime_UTR
    - 19533   gene
    - 2011    ncRNA_gene
    - 907     snRNA
    - 628     pseudogene


