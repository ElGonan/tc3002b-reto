# tc3002b-reto
Reto de la materia TC3002b

# Alan Patricio González Bernal - A01067546
# Alan Rodrigo Castillo Sánchez - A1708668


# Detección de plagio en código fuente
## Descripción
Este proyecto implementa un sistema de detección de plagio en código fuente basado en TF-IDF (Term Frequency-Inverse Document Frequency), combinado con técnicas de procesamiento de lenguajes formales para analizar similitudes estructurales y semánticas en programas Java. El sistema está diseñado para entornos educativos y competencias de programación, donde es crítico identificar tanto copias literales como modificaciones astutas (ej.: renombrado de variables, reordenamiento de bloques).

## Características
- Tokenización de código fuente Java. Se plantea ANTLR4
- Cálculo de TF-IDF para identificar términos significativos.
- Detección de plagio basada en similitudes de tokens y estructuras de código.

## Organizacion del proyecto
```
- datasets
    - ConPlag
        - ...
    - IR-Plag-Dataset
        - ...
- papers
    - ...
- src
    - project.ipynb
    ...
...
```

<b>Es importante denotar que unicamente project.ipynb es ejecutable. Los demás códigos son solo dependencias de ANTLR4</b>

# Mejora para semana 18
## Alan Patricio González Bernal - A01067546

Como parte de mejora para el proyecto, aplicaré un aumento de datos, ya que el dataset actual está limitado y se tuvo que normalizar. Por lo que se propone un aumento de datos sustancial mendiante la combinación y mezcla de otros datasets para tener una base sólida. La cual presentará unos resultados más concisos y confiables por los diferentes estilos y objetivos de los mismos.

Además del aumento de dataset, se implementa detección multiclase de plagio. Ya que se sabe que el plagio es una acusación grave y debe haber verdadera certeza de que existe. Por lo que se implementan multiclases para poder detectar diferentes tipos de plagio lo que asegura que se pueda, a nivel de instructor, tener una mejor idea de qué tipo de plagio se está cometiendo y así poder tomar las acciones correspondientes.

# Referencias

- https://www.antlr.org/index.html

- O. Karnalim, "TF-IDF-inspired detection for cross-language source code plagiarism and collusion," Computer Science, vol. 21, no. 1, pp. 113–136, 2020. doi: 10.7494/csci.2020.21.1.3389
- E. Slobodkin y A. Sadovnikov, "ConPlag: a Dataset of Programming Contest Plagiarism in Java," Zenodo, Nov. 10, 2022. doi: 10.5281/zenodo.7332790
- D. Fu, Y. Xu, H. Yu, y B. Yang, "WASTK: A Weighted Abstract Syntax Tree Kernel Method for Source Code Plagiarism Detection," Scientific Programming, vol. 2017, Art. no. 7809047, 2017. doi: 10.1155/2017/7809047
- Oscar Karnalim, Sulistiani, H. Toba, y M. Joy, "Source Code Plagiarism Detection in Academia with Information Retrieval: Dataset and the Observation," International Journal of Engineering Education, vol. 35, no. 4, pp. 1062–1073, 2019
- Z. C. Lipton, C. Elkan y B. Narayanaswamy, "Optimal Thresholding of Classifiers to Maximize F1 Measure," en Machine Learning and Knowledge Discovery in Databases, T. Calders, F. Esposito, E. Hüllermeier y R. Meo, Eds., ECML PKDD 2014, Lecture Notes in Computer Science, vol. 8725, Springer, Berlín, Heidelberg, 2014, pp. 225–239
- R. S. Mehsen and H. D. Joshi, "Detection of Source Code Plagiarism Utilizing an Approach Based on Machine Learning," International Journal of Computing, vol. 23, no. 1, pp. 78–84, 2024, doi: 10.41859/jc.211.34.98.
- Plagiarism Level & Penalties UGC Guideline for Promotion of Academic Integrity and Prevention of Plagiarism," Library Academy, [En línea]. Disponible en: https://libraryacademy.in/plagiarism-level-penalties-ugc-guideline/. [Accedido: 5-jun-2025].