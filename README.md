# Tarea 4: Análisis de Vulnerabilidades

## Integrantes:
- David Báez.
- Martín Carrasco.
- Sabrina López.

## Caso de estudio: [GitHub Actions](https://github.com/orgs/actions/repositories?q=sort%3Astars)

### ¿Qué es GitHub Actions?

GitHub Actions facilita la automatización de los flujos de trabajos de software integrada directamente en GitHub, permitiendo compilar, probar, y desplegar el código. Gestiona las revisiones de código, la administración de ramas, y la clasificación de incidentes.

### Análisis

Para el análisis se utilizaron los _notebooks_ ya implementados de la tarea anterior.

Se tuvieron que modificar los repositorios y sus respectivos links en el archivo _repos.json_. Se limitó el análisis a los cinco repositorios con más estrellas y cuyo lenguaje de programación fuera TypeScript, esto último debido a la falta de los componentes de CodeQL para los otros idiomas de los principales reposiorios: go y C#.

Durante la clase se llegó hasta el análisis de dependencias y vulnerabilidades con CodeQL y Grype. De las vulnerabilidades encontradas, la mayoría fueron de baja severidad (low). Como GitHub Action es utilizado para los flujos de trabajo, es utilizado en muchos repositorios de todo tipo, por lo que es importante que sea lo más seguro posible.