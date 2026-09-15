# Capitulo-3-Programación
Carga de ejemplos y ejercicios asociados al Capitulo 3 de Deitel

## De qué trata
 
Continúa la presentación de HTML5 enfocándose en las **características nuevas** del estándar. Mientras el capítulo 2 cubre el marcado fundamental

El capítulo advierte desde el inicio que el soporte de estas características **varía entre navegadores**, por lo que los ejemplos del libro se muestran con capturas de distintos navegadores (Chrome, Firefox, Internet Explorer, Safari y Opera) para evidenciar las diferencias. Para este caso se consideró el uso de Chrome y Firefox.

## Objetivos del capítulo
 
- Construir un formulario utilizando los nuevos tipos `input` de HTML5.
- Especificar el elemento `input` que debe recibir el enfoque de manera predeterminada.
- Usar elementos `input` con validación automática.
- Especificar texto `placeholder` temporal en varios elementos `input`.
- Usar el atributo `autocomplete` para ayudar a reintroducir texto escrito antes en un formulario.
- Usar el elemento `datalist` para especificar una lista de valores y completar entradas automáticamente.
- Usar los nuevos elementos de estructura de página para delinear partes de una página: encabezados, secciones, figuras, artículos, pies de página y más.

## Ideas centrales
 
**Validación automática del lado del cliente.** Es el aporte más importante del capítulo. Tradicionalmente ha sido difícil asegurar que el usuario introduzca una dirección de correo, un URL, una fecha o una hora en el formato adecuado. Los nuevos tipos `input` validan por sí mismos, lo que elimina la necesidad de escribir código de JavaScript para ello, reduce los datos inválidos enviados y disminuye el tráfico entre el cliente y el servidor. Cuando el usuario envía el formulario, el navegador verifica de inmediato los elementos y despliega una anotación señalando el campo incorrecto. Sin embargo, **de todas formas el servidor debe validar toda la entrada del usuario.** La validación del cliente es una conveniencia, no una garantía de seguridad.

**Validación no es verificación.** HTML5 comprueba el **formato**, no la existencia. No verifica si una dirección de correo electrónico realmente existe ni si un URL introducido apunta a un recurso real.

**Degradación en navegadores sin soporte.** Los navegadores que no soportan un tipo `input` nuevo simplemente lo despliegan como un campo de texto estándar. Por eso el libro recomienda agregar texto descriptivo junto a cada campo indicando el formato esperado, ya que el `placeholder` tampoco está garantizado.
