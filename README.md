# Apuntes de Homotopía Estable

Apuntes personales en español para el curso **Temas Selectos de Topología II: Homotopía Estable**, impartido por el Dr. José María Cantarero López en el Centro de Investigación en Matemáticas (CIMAT). El material organiza y complementa las clases con definiciones, demostraciones, ejemplos, diagramas y referencias bibliográficas. No es una publicación oficial del CIMAT.

## PDF

La versión compilada más reciente está disponible en [`build/main.pdf`](build/main.pdf) y se conserva en el repositorio junto con los archivos fuente.

## Contenido y estado actual

El documento reúne las **clases 1–25**. La última incorporada es la **clase 25, del 5 de noviembre de 2026**, y el PDF completo tiene **373 páginas**. La clase 25 ocupa las páginas 358–371 del visor, incluida su portadilla; la bibliografía se encuentra en las páginas 372–373.

La [clase 25](Apuntes/C25.tex) desarrolla los siguientes temas:

- Espectros anillo en homotopía y un criterio de anulación de mapas fantasmas.
- Construcción de la multiplicación de Eilenberg–MacLane por niveles y sus compatibilidades estructurales.
- Unidad y axiomas multiplicativos de `HR`, mediante homología y detección de mapas en grado cero.
- Anillos graduados de coeficientes, comparación con la cohomología y cálculo de los coeficientes de `KU` mediante la clase de Bott.

Incluye los ejercicios 53–54 con sus soluciones. Las correcciones respecto a la exposición y los resultados utilizados sin demostración se identifican en el texto. El teorema de imposibilidad de Lewis se anunció al comienzo, pero su desarrollo quedó pospuesto.

La clase 21 mantiene una versión elaborada únicamente a partir de las pizarras, pendiente de ampliación cuando se disponga de su transcripción. Las pizarras y transcripciones originales se conservan por separado del repositorio de apuntes; la transcripción de la clase 24 se fusionó a partir de tres partes, preservando los originales y documentando los empalmes y los tiempos estimados.

## Criterios editoriales

La exposición utiliza redacción matemática directa y conserva la notación y la estrategia de los argumentos de clase. Se incluyen los diagramas de las pizarras, reacomodándolos cuando es necesario para que encajen sin desbordarse; las flechas que solo representan evaluaciones pueden escribirse aparte. Se resuelven los ejercicios propuestos. Las correcciones, los complementos editoriales y las cuestiones abiertas se distinguen del contenido demostrado en clase.

Cada introducción incorpora una orientación bibliográfica breve con localizadores comprobados en las fuentes consultadas. Se distingue entre referencias a enunciados, ejercicios y demostraciones disponibles.

## Compilación

Se requiere una instalación de TeX Live con `latexmk`, pdfLaTeX, Biber y los paquetes LaTeX utilizados por el documento. Desde la raíz del repositorio, ejecuta:

```sh
latexmk -pdf
```

El PDF se genera en `build/main.pdf`. La configuración de `latexmkrc` dirige allí también los archivos auxiliares. Para borrar los auxiliares y conservar el PDF, ejecuta `latexmk -c`; `latexmk -C` elimina todos los archivos generados, incluido el PDF.

## Organización

- `Apuntes/`: apuntes de las clases y archivo que los reúne.
- `Apuntes/Cuerpo.tex`: fechas y orden de las clases, cargadas mediante `\include{Apuntes/Cn}`.
- `Figuras/`: diagramas reutilizados por los apuntes.
- `Personalizacion/`: estilos, encabezados, títulos y entornos LaTeX.
- `Portada/`: portada y recursos gráficos.
- `Referencias.bib`: bibliografía del documento.
- `build/main.pdf`: PDF compilado para lectura.

## Sincronización con GitHub

Se versionan los archivos LaTeX, la bibliografía, las figuras y recursos de la plantilla, la documentación y el PDF final. Dentro de `build/` se sincroniza únicamente `main.pdf`; los auxiliares de compilación, las memorias locales de trabajo y los archivos temporales quedan excluidos mediante `.gitignore`.

## Licencia

Este repositorio no especifica una licencia abierta de reutilización. Para reutilizar o redistribuir su contenido, consulta al autor.
