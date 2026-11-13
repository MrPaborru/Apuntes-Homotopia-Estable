# Preferencias editoriales del usuario

- En el texto se escribe «clase n»; los nombres de archivos y etiquetas pueden usar Cn.
- Para colímites ordinarios se usa `\varinjlim`, con `\nolimits` si el subíndice es breve. El telescopio se denota mediante `hocolim`, siguiendo los apuntes existentes.
- Se incluyen todos los diagramas de las pizarras, salvo los que solo representan evaluaciones. Reacomodar los vértices y las flechas para que cada diagrama se lea con claridad en una sola figura, conservando sus objetos, morfismos, relaciones y propósito expresivo. En los diagramas con varias regiones, señalarlas con (i), (ii), etc. cuando sea posible y justificar su conmutatividad en una lista debajo de la figura. Para prismas de transformaciones naturales, mostrar todas las componentes y usar una perspectiva correcta; preferir disposición horizontal.
- Evitar cortes de fórmulas en línea y párrafos cuya última línea tenga solo un par de palabras cortas. Ajustar la redacción conservando íntegramente el contenido y la precisión; comprobar el PDF después de los cambios.
- Incluir y resolver todos los ejercicios del profesor. Si ya están resueltos, citar el resultado previo y explicar cómo se aplica.

- Usar `grisCIMAT` para las etiquetas de región (i), (ii), etc. Usar `rojoCIMAT` para los elementos rojos de las pizarras. Para destacar una flecha o un recorrido cuando ayude a seguir el argumento, se puede usar `rojoCIMATdiagramas`. Preferir `tikzcd` para diagramas conmutativos, centrar las etiquetas de flechas equivalentes y usar `\simeq`.
- Comprobar en el PDF cada diagrama al terminar, con atención a la separación entre objetos, flechas y etiquetas, y a posibles superposiciones.
- Colocar las etiquetas de texto de las flechas de una categoría en cuerpo pequeño y paralelas a la flecha, preferentemente encima. Si una etiqueta queda encerrada entre dos flechas, colocarla del lado exterior y conservar la separación respecto de su flecha. Reacomodar el diagrama para que estas flechas tengan una pendiente suave y el texto quede lo más horizontal posible.
- Favorecer la paginación natural. Mantener cada diagrama cerca del texto que lo introduce y de sus justificaciones, y evitar cortes de página forzados que dejen grandes huecos.
- Para una correspondencia entre morfismos, centrar la flecha respecto de los morfismos que conecta y distinguirla de las flechas de la categoría mediante una flecha de zigzag o `\mapsto`. Usar también cuerpo pequeño en sus etiquetas de texto.
- Las flechas esquemáticas deben distinguirse de los morfismos de la categoría. Preferir un trazo en zigzag para las correspondencias entre clases de objetos o construcciones.

## Redacción de los apuntes

- Usar redacción matemática directa en lugar de atribución narrativa para la exposición habitual. Por ejemplo, escribir «Consideremos…», «Por definición…» o «De aquí se sigue…» en lugar de «El profesor considera…», «El profesor define…» o «En la pizarra se observa…». Exponer directamente las definiciones, los argumentos y las conclusiones.
- Conservar las referencias explícitas a la clase, al profesor o a la pizarra cuando documenten errores cometidos en clase, correcciones orales, cambios introducidos en los apuntes, añadidos u omisiones respecto a la clase, ajustes de notación o diagramas, o el alcance de lo demostrado y de las preguntas que quedaron abiertas en clase. Dejar clara la procedencia: expresiones como «formulación inicial» no deben sustituir a «formulación presentada en clase» si con ello se vuelve ambiguo dónde apareció el error o qué se está corrigiendo.
- La redacción directa debe conservar el contenido, la notación y la estrategia de los argumentos de la clase. No autoriza a inventar explicaciones ni a sustituir las demostraciones del profesor por otras propias.
- Escribir los objetos, espacios de morfismos y funtores con su notación habitual, incluso dentro de los diagramas. Evitar alias locales para notaciones establecidas, como usar `G` para `\Omega^\infty`, para que se pueda consultar un fragmento sin buscar una sustitución previa.
- Usar «codominio» para el objeto de llegada de un morfismo.
