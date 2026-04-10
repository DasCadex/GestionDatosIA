# Predicción de Agotamiento de Stock en Productos

Este proyecto tiene como objetivo anticipar, mediante un modelo de IA, si un producto en bodega se agotará en los próximos días, utilizando variables como historial de ventas, frecuencia de reposición y estacionalidad.

El sistema permite optimizar la gestión de inventario en retail, pasando de una estrategia reactiva a una estrategia proactiva basada en datos.

---

## Componentes del sistema

- **Scripts de procesamiento**: ingesta, limpieza, transformación y validación de datos.
- **Base de datos PostgreSQL**: para la carga y consulta estructurada de los datasets.
- **Modelo de IA (scikit-learn / XGBoost)**: clasificación binaria para predecir agotamiento de stock.
- **Metabase (opcional)**: dashboard de visualización de resultados y alertas.
- **Documentación**: diseño técnico completo (DDT) y planificación del proyecto (PMBOK).

---

## Tecnologías utilizadas

- Python 3.10+
- Pandas / Scikit-learn / XGBoost
- PostgreSQL
- Docker (implementación futura)
- Git / GitHub
- Trello (planificación y seguimiento)

---

## Pipeline implementado

| Etapa | Descripción |
|-------|------------|
| 1. Diseño e instalación | Definición de arquitectura, estructura de carpetas y configuración del entorno |
| 2. Ingesta | Lectura desde archivos CSV (ventas, stock, promociones) |
| 3. Limpieza | Eliminación de duplicados, tratamiento de nulos y corrección de inconsistencias |
| 4. Transformación | Creación de variables como días sin reposición, promedio de ventas y estacionalidad |
| 5. Validación | Revisión de tipos, rangos y coherencia de los datos |
| 6. Carga en PostgreSQL | Subida del dataset limpio y validado a la base de datos |
| 7. Entrenamiento IA | Clasificación binaria con scikit-learn para la variable `SeAgotara` |
| 8. Evaluación | Métricas como Precision, Recall y F1-Score |
| 9. Visualización | Panel con predicciones, stock proyectado y alertas |

---

# INTEGRANTES:
- Fernando Villalobos
- Nicolas Sotomayor
- Felipe Arriagada
- Joan Rojas
