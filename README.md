# Red_Arabidopsis
En esta red se puede apreciar información obtenida de bases de datos de un gen de interés de Arabidopsis Thaliana, genes observados en las figuras del archivo disponible en este repositorio.
El gen de interés fue  CCD7 porque, de acuerdo con el documento (pdf) anexo, es una hormona metabolica. 

CCD7 es una dioxigenasa de escisión de carotenoides, su fuente principal es Araport: AT2G44990 y se le conoce por diversos nombres como: ATCCD7; dioxigenasa 7 de escisión de carotenoides; MAX3; T14P1.21.
Para obtener información de ella se revisaron bases de datos biologicas de donde se obtuvo la siguiente información:
- Links para información de NCBI: https://www.ncbi.nlm.nih.gov/gene/819107
- Artículo relacionado a el gen de interés: https://www.cell.com/current-biology/fulltext/S0960-9822(04)00472-5?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS0960982204004725%3Fshowall%3Dtrue
- Links de información de UniProt: https://www.uniprot.org/uniprot/Q7XJM2

Analisis de la información.
El locus MAX3 está en el brazo inferior del cromosoma II entre los marcadores AthB102 y GBF3. La ubicación de MAX3 se delimitó a una región delimitada por los marcadores 442327 y 442610. Esta región tiene aproximadamente 66 kb y contiene 15 genes anotados ( http://www.tigr.org/tdb/e2k1/ath1 ). Uno de estos genes, At2g44990, codifica una supuesta enzima de escisión de carotenoides, AtCCD7, lo que sugiere que MAX3 es CCD7.
El marco de lectura abierto previsto de MAX3 incluye una señal de localización de cloroplasto putativa ( http://www.cbs.dtu.dk/services/TargetP/ ).

Se hizó una busqueda en Genemania de CCD7 para observar la interacción con otros genes en el organismode Arabidopsis Thaliana en base a estudios previos y observar las funciones en las que participa, con otro conjunto de genes, en funciones biolóicas. 
Los datos obtenidos fueron los siguientes: [genemania-report (2).pdf](https://github.com/Miroslava2082/Red_Arabidopsis/files/6722464/genemania-report.2.pdf)

En Genemania es una base de datos orientada a la construcción de redes de asociación de genes que, entre otros muchos datos, almacena interacciones de proteínas. Proporciona  información  sobre  las  asociaciones  de  genes/proteínas obtenidas a  partir  de: (i)  interacciones  físicas, (ii)  co‐expresión  de genes, (iii)  predicciones computacionales, (iv) rutas de señalización, (v) co‐localización, (vi) interacciones genéticas y (vi) dominios de proteínas comunes.!
En CCD7 se pueden observar las siguientes interacciones en donde se muestran el conjunto de interacciones físicas (en color rojo), las predicciones (naranja), las co-expresiones (morado), los dominios que comparte con otras proteínas (amarillo) y la interacción geneteica (verde).
![genemania-network (3)](https://user-images.githubusercontent.com/85301570/123563655-88bd7900-d77b-11eb-9f7a-db6fdf50aebb.jpg)
[genemania-networks (2).txt](https://github.com/Miroslava2082/Red_Arabidopsis/files/6722503/genemania-networks.2.txt)
 
En el analisis de los datos obtenido en Genemania se obtiene que no se han reportado interacciones físicas con otros genes, no presenta interacción genetica y la única co-localización se encuentra en los genes NCDE5 Y NCDE9.
![genemania-network (9)](https://user-images.githubusercontent.com/85301570/123564575-8fe68600-d77f-11eb-886f-1a29f14f807f.jpg)
Pero computacionalmente predice que tiene interacción con 8 genes, en donde se puede predecir que teiene mayor interacción con los genes AT5G25050 y AT1G04570 de manera directa, estas se interconectan con el gen CCD8.
![genemania-network (8)](https://user-images.githubusercontent.com/85301570/123564480-3da56500-d77f-11eb-8ab3-6634f9d9657f.jpg)
Se co-expresa con varios genes y también se puede co-expresar de forma inderacta con otros como: CCD1, NCDE5, AT1G52100, etc. Como se muestra en la siguiente imagen. Los genes más cercanos a CCD7 son los que presentan interacción directa, mientras que los genes más alejados y visualmente grandes presentan una interacción indirecta.
![genemania-network (6)](https://user-images.githubusercontent.com/85301570/123564221-22862580-d77e-11eb-89a3-13e7151cd9ad.jpg)
Por último se puede observar que los principales genes con lo que comparte dominios de proteínas con otros genes son genes pertenecientes a las familias CCD y NCED.
![genemania-network (7)](https://user-images.githubusercontent.com/85301570/123564368-d4255680-d77e-11eb-9d58-ae1f53997fee.jpg)
