<!-- TITLE: Codigo Legacy -->
<!-- SUBTITLE: A quick summary of Codigo Legacy -->

# Assessment de código legacy

## Introducción

Este documento se base en los resultados obtenidos a través de una herramienta conocida de análisis de calidad [SonarQube](https://www.sonarqube.org/) y en el análisis por parte del equipo.

Los reportes se basan en métricas ampliamente aceptadas, como deuda técnica, cobertura, complejidad ciclomática, cantidad de líneas de código y cantidad de código duplicado.

## Puntos principales de análisis

- Reusabilidad y mantenibilidad:
  - La reusabilidad indica la posibilidad que tiene una porción de código de ser reutilizado a lo largo de la plataforma, reducir la cantidad de código duplicado hace que el equipo pueda modificar el código con menor riesgo de error y en menor tiempo, teniendo que modificar la lógica en un único lugar, en lugar de en N.
  - La mantenibilidad es un concepto más abarcativo  que es afectado por la reusabilidad del código, la legibilidad, la documentación, la cantidad de tests, el tamaño del proyecto y las buenas prácticas.
- Documentación: esta métrica indica si el código está documentado, no solo funciones/métodos/módulos sino también instrucciones de cómo ejecutar la aplicación, casos extraños o _gotchas_ de la plataforma.
- Cobertura de tests: un porcentaje que indica la cantidad de líneas de código que son cubiertas por al menos UN test.

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