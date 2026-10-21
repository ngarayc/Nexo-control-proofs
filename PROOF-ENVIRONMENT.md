# Entorno descartable de pruebas de controles

Este repositorio es una copia sintética de [Nexo `577ecc7ece06829c84f17be8dbe455b85ad0d936`](https://github.com/ngarayc/Nexo/tree/577ecc7ece06829c84f17be8dbe455b85ad0d936) para demostrar rechazo y recuperación de controles. La entrega de aplicación continúa en [ngarayc/Nexo](https://github.com/ngarayc/Nexo). No se promueven allí los cambios defectuosos de esta demostración.

## Equivalencias y diferencias

Se conservan los workflows, agregado, validadores, aplicación y pruebas de la fuente. Los únicos ajustes de CI iniciales sustituyen el nombre del repositorio en el validador de trazabilidad y sus datos de pruebas. La issue #1 de este recurso registra todas las acciones y commits; corresponde a [Nexo #4](https://github.com/ngarayc/Nexo/issues/4). Los cuatro fixtures y sus oráculos permanecen intactos.

Archivos adaptados:

- `scripts/ci/policy.mjs`

Actions permanece deshabilitado durante la primera publicación vacía y la creación de ramas; después se configuran protecciones equivalentes para main/test y entorno de revisión, y se habilita CI. Eso es preparación del recurso descartable, no una promoción de Nexo.

Las pruebas omitidas/fallidas se introducen deliberadamente solo aquí. Se registran resultados de checks, rechazo de integración y restauración. Un token sintético se escanea localmente con redacción y se retira antes de publicar. No hay credenciales reales, datos de producción o evidencia humana fabricada.

Las revisiones humanas de la entrega se acreditan en Nexo sobre su candidato real; este recurso no las sustituye.
