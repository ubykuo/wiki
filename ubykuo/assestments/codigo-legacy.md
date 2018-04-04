<!-- TITLE: Assesstment de codigo legacy -->
<!-- SUBTITLE: ¿Cómo se realiza y para qué lo utilizamos? -->

# Código legacy
El objetivo de un assesstment (evaluación) de código es conocer los riesgos de continuar el desarrollo de una plataforma sobre código heredado desconocido. El assesstment debe arrojar evaluaciones objetivas al cliente, obtenidos mediante las métricas [SonarQube](https://www.sonarqube.org/) ([Continuos quality con SonarQube
](https://forum.ubykuo.com/continuos-quality-con-sonarqube/) y evaluaciones más profundas, realizadas por el encargado del assesstment, como por ejemplo, vulnerabilidades de seguridad, problemas de mantenibilidad, etc.

## Puntos principales de análisis
Los puntos a evaluar son los siguientes:
### Mantenibilidad
Es un concepto que abarca la mayor parte de los que siguen (como la reusabilidad, la legibilidad, la cantidad de líneas de código y las buenas prácticas) y define la facilidad con la que el equipo puede modificar el código para corregirlo o mejorarlo.
### Reusabilidad
La reusabilidad indica la posibilidad que tiene una porción de código de ser reutilizado a lo largo de la plataforma, reducir la cantidad de código duplicado hace que el equipo pueda modificar el código con menor riesgo de error y en menor tiempo, teniendo que modificar la lógica en un único lugar, en lugar de en N.
### Legibilidad
El código es escrito una vez y leído infinta cantidad, por esto es que la legibilidad (siempre en cuando sea escrito por humanos...) es importante. La legibilidad es un atributo del código que describe la facilidad con la puede interpretarlo una persona. Siempre tratamos de que el código sea lo más simple y cercano a algo legible incluso para alguien que no es programador.
Signos de mala legibilidad son la mala indentación, el mal uso de espacios, la complejidad para entender la intención del código, entre otros. 
### Documentación
Esta métrica indica si el código está documentado, no solo funciones/métodos/módulos sino también instrucciones de cómo ejecutar la aplicación, casos extraños o _gotchas_ de la plataforma.
Es importante destacar que la documentación es necesaria para describir como utilizar una interfaz (como la descripción de un método, parámetros y retorno), no para describir lo que hace una línea, la intención de esa línea debería ser clara si es legible.
### Cobertura de tests
Un porcentaje que indica la cantidad de líneas de código que son cubiertas por al menos UN test. Esta métrica indica claramente la seguridad (o no) que podemos tener a la hora de modificar el código.
## Plantilla
La plantilla para assesstments se encuentra [aquí](https://docs.google.com/document/d/1-3qZbVgSff5dUBpxa-4ttZDJ7BWordCqZaU6MlFnwsk/edit?usp=sharing)
## Riesgo
El riesgo de la plataforma se termina determinando con un número entre 1 y 10.