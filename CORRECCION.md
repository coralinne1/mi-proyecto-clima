# Corrección de mala práctica

## ¿Qué mala práctica identificaste?
No existía un archivo `.gitignore` en el proyecto para excluir archivos sensibles o irrelevantes para el control de versiones.

## ¿Por qué es considerada una mala práctica?
Sin `.gitignore`, se corre el riesgo de subir archivos como claves de API, configuraciones locales o archivos temporales, lo que puede comprometer la seguridad o dificultar el trabajo colaborativo.

## ¿Cómo la solucionaste?
Agregué un archivo `.gitignore` en la raíz del proyecto que incluye reglas comunes para excluir archivos como `.env`, `node_modules/` y archivos temporales.

## ¿Qué beneficios aporta tu solución?
- Protege información sensible (como API keys).
- Evita conflictos al trabajar en equipo.
- Mejora la organización y limpieza del repositorio.
