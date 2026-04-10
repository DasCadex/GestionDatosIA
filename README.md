#alcanse del proyecto :

El alcance principal de nuestro proyecto es poder implementar un sistema de automatización y implementación de IA para poder medir el stock, en profundidad es poder que la IA estudie el stock de los productos y avisar a supervisores o encargados de la tienda cuando el stock esté bajo para poder abastecer, también que sea capaz la IA de identificar que productos de compra más en ciertas épocas para que puedan mantener un stock controlado para no tener demasiado ni tampoco poco, sin mencionar de mantener un precio justo para las épocas. 

##componnentes del sitema

Scripts de procesamiento: ingesta, limpieza, transformación y validación de datos.
Base de datos PostgreSQL: para la carga y consulta estructurada de los datasets.
Modelo de IA (scikit-learn): clasificación binaria para predecir agotamiento.
Documentación: en este punto dejaremos un manul de usuaio , la planificacion y por ultimo el documento completo indicando la arquitectura



Tecnologías utilizadas
Python 3
PostgreSQL
Docker
Git / GitHub
Trello (para planificacion)
excel y word para documentacion

|-------|-------------|
| 1. Diseño e instalación | Estructura de carpetas, setup del entorno, definición de herramientas |
| 2. Ingesta | Lectura desde CSV (Kaggle o Mockaroo), carga a memoria |
| 3. Limpieza | Eliminación de duplicados, tratamiento de nulos, revisión de tipos |
| 4. Transformación | Creación de variables como días sin reposición, tasa de ventas, etc. |
| 5. Validación | Revisión de rangos, tipos, coherencia; validación básica |
| 6. Carga en PostgreSQL | Subida del dataset limpio y validado a la base de datos local |
| 7. Entrenamiento IA | Clasificación binaria con scikit-learn para variable `SeAgotara` |
| 8. Evaluación | Métricas como accuracy, recall; revisión de logs de ejecución |
| 9. Visualización | Panel con predicciones, stock proyectado y alertas (si aplica) |

---

## :open_file_folder: Estructura del repositorio

```
Documentacion_tecnica/
├── planificacion_PMBOK
├── dWBS_planificacion/
├── README.md


---

## Cómo ejecutar el sistema (entorno ya instalado)

1. Clonar el repositorio  
   `git clone https://github.com/usuario/agotamiento-stock.git`

2. Entrar a la carpeta del proyecto  
   `cd `

3. Ejecutar el pipeline manualmente por etapas  
   Ejemplo:  
   `python scripts/ingesta.py`  
   `python scripts/limpieza.py`  
   `python scripts/entrenamiento.py`

4. Visualizar los resultados y métricas desde consola o dashboard

---

## Documentación técnica



El documento de diseño técnico está disponible en:  
[`docs/diseño_tecnico.pdf`](docs/diseño_tecnico.pdf)



# INTEGRANTES:
- Fernando Villalobos
- Nicolas Sotomayor
- Felipe Arriagada
- Joan Rojas
