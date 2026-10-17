# Rutas de evacuación en zona inundada

**Actividad:** Cuando el camino más corto no es el mejor
**Materia:** Fundamentos de Inteligencia Artificial

Prototipo que simula una zona inundada como una cuadrícula y busca una ruta desde un punto afectado hasta un refugio. Compara varias estrategias de búsqueda para mostrar la diferencia entre *encontrar una ruta* y *encontrar la ruta conveniente* cuando el terreno tiene riesgo.

## Integrantes y reparto

| Integrante | Celdas | Qué incluye |
|---|---|---|
| Jorge | 1, 2 y 3 | Terreno, funciones base y los algoritmos BFS, Dijkstra y A* |
| Jarett | 4, 5 y 6 | Validador, comparación y visualización, además de las pruebas 1, 2 y 3 |
| Danie | 7 y 8 | Pruebas 4 y 5, y la prueba adicional con error inyectado |
| Erick | 9 y 10 | Prueba del validador, decisiones de diseño y declaración de IA |

## Contenido del repositorio

| Archivo | Qué contiene |
|---|---|
| `rutas_inundacion.ipynb` | Notebook principal: terreno, algoritmos, escenarios, comparación y pruebas |
| `requirements.txt` | Dependencias para ejecutarlo fuera de Colab |

## Cómo reproducirlo

**En Google Colab:** Archivo → Abrir cuaderno → pestaña GitHub → buscar `jorgemx546/rutas-inundacion` → abrir `rutas_inundacion.ipynb` → Entorno de ejecución → Ejecutar todo.

**En local** (Python 3.10 o superior):

```bash
python -m venv .venv
.venv\Scripts\activate        # en Windows
# source .venv/bin/activate   # en Linux/macOS
pip install -r requirements.txt
jupyter nbconvert --to notebook --execute rutas_inundacion.ipynb --output rutas_inundacion.ipynb
```

## Decisiones de diseño

_Pendiente._

## Declaración de uso de IA

_Pendiente._
