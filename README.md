# Construir commits más elegantes

Los commits deben representar un objetivo específico, no se debe mezclar más de una
funcionalidad en el mismo commit, si tributan a objetivos diferentes, son commits
diferentes.
Para crear un nuevo commit se debe analizar la funcionalidad semánticamente, evitando
hacer mención a elementos redundantes como los archivos modificados o las fechas en
que se modificaron, ya que el control de versiones se encarga de identificar esos
elementos. A continuación, se define la estructura que deben llevar los commits.

### 1. Título 

El título debe ser breve (no más de 50 caracteres) y comenzar con un verbo en
infinitivo que describa la acción realizada. Además, el título debe comenzar en mayúscula
y no debe terminar con un punto.
El título debe estar prefijado con un código de representación en minúsculas envuelto en
corchetes cuadrados “[ ]”, los prefijos se describen en la tabla a continuación de la
estructura.

### 2. Descripción

Esta sección es opcional, pero se recomienda que esté siempre disponible.
Proporciona una descripción más detallada de los cambios realizados, desde una
perspectiva más conceptual de la funcionalidad. En esta sección, se pueden incluir
detalles sobre la implementación, las decisiones de diseño tomadas, los problemas
resueltos, entre otros. El cuerpo debe estar separado del título por una línea en blanco y
no debe exceder 72 caracteres de ancho. El texto debe comenzar por mayúscula y
terminar en punto.

### 3. Observaciones

Esta sección es opcional y se utiliza para agregar información adicional
al commit, como el número de tarea asociado, los problemas cerrados, los cambios en la
documentación, entre otros. Al igual que el cuerpo, el pie de página debe estar separado
del cuerpo por una línea en blanco, el texto debe comenzar por mayúscula y terminar en
punto.

# Ejemplo de un commit

> ##### [feat] Añadir autenticación en dos pasos

El código de verificación se puede enviar mediante diferentes canales, estos son: SMS,
llamada telefónica, whatsapp o email. También se habilitan web services que permiten
agregar, editar y eliminar canales de autenticación.
