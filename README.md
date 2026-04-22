# Tarea 3: SBOMs + Análisis de vulnerabilidades

## Integrantes:
- David Báez.
- Martín Carrasco.
- Sabrina López.

## Caso de estudio: [FastAPI](https://github.com/fastapi)

### ¿Qué es FastAPI?

FastAPI es un framework web para creación rápida de APIs en Python de forma sencilla y en pocas líneas de códigos. En los últimos años ha ganado una gran popularidad en base a su simpleza, siendo adoptado por diferentes empresas como Netflix, Microsoft, Uber, entre otras.

### Análisis

Para el análisis se utilizaron los _notebooks_ ya implementados, se añadieron consultas para SBOMs, y fueron modificadas las de CodeQL y Grype permitiendo mostrar más repositorios e información. 

Igualmente para el análisis, se tuvieron que modificar los repositorios y sus respectivos links en el archivo _repos.json_. Por otro lado, se realizaron cambios a los _scripts_ de CodeQL (memoria) y Grype para soportar y permitir el análisis de repositorios Python de gran tamaño, con el formato de dependencia de _pyproject.toml_, transformandolo a un archivo _requirements.txt_ soportado.