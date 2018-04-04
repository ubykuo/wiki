<!-- TITLE: Assesstment de codigo legacy -->
<!-- SUBTITLE: ¿Cómo se realiza y para qué lo utilizamos? -->

# Assessment de código legacy
El objetivo de un assesstment (evaluación) de código es conocer los riesgos de continuar el desarrollo de una plataforma sobre código heredado desconocido. El assesstment debe arrojar evaluaciones objetivas al cliente, obtenidos mediante las métricas [SonarQube](https://www.sonarqube.org/) ([Continuos quality con SonarQube
](https://forum.ubykuo.com/continuos-quality-con-sonarqube/) y evaluaciones más profundas, realizadas por el encargado del assesstment, como por ejemplo, vulnerabilidades de seguridad, problemas de mantenibilidad, etc.

## Puntos principales de análisis
* Reusabilidad y mantenibilidad:
	* La reusabilidad indica la posibilidad que tiene una porción de código de ser reutilizado a lo largo de la plataforma, reducir la cantidad de código duplicado hace que el equipo pueda modificar el código con menor riesgo de error y en menor tiempo, teniendo que modificar la lógica en un único lugar, en lugar de en N.
  * La mantenibilidad es un concepto más abarcativo  que es afectado por la reusabilidad del código, la legibilidad, la documentación, la cantidad de tests, el tamaño del proyecto y las buenas prácticas.
* Documentación: esta métrica indica si el código está documentado, no solo funciones/métodos/módulos sino también instrucciones de cómo ejecutar la aplicación, casos extraños o _gotchas_ de la plataforma.
* Cobertura de tests: un porcentaje que indica la cantidad de líneas de código que son cubiertas por al menos UN test.

## Análisis &lt;módulo&gt;

Imagen SonarQube

## Reusabilidad y mantenibilidad (Baja|Media|Alta)

Observación 1

Observación 2

Observación N

## Documentación (Nula|Baja|Media|Alta)

## Cobertura de tests (Nula|Baja|Media|Alta)

## Conclusión

Dificultad

(1..10)