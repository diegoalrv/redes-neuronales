# 💻 00_Notebooks_Practica

Carpeta con los **notebooks interactivos de Jupyter** del curso *Redes Neuronales con Python*. Cada notebook combina teoría, código ejecutable y ejercicios prácticos para reforzar lo visto en clase.

---

## 📂 Contenido

| Notebook | Tema | Clase |
|----------|------|-------|
| `Ej_NumPy.ipynb` | Operaciones numéricas, arrays, producto punto | Clase 5 |
| `Ej_Pandas.ipynb` | DataFrames, limpieza y preparación de datos | Clase 6 |
| `Ej_Matplotlib.ipynb` | Visualización de datos para redes neuronales | Clase 7 |
| `Clase_8.2_TensorFlow_PyTorch.ipynb` | Construcción de redes neuronales con TF/Keras y PyTorch | Clase 8.2 |

---

## 📒 Detalle de cada notebook

### 🔢 `Ej_NumPy.ipynb` — Clase 5
Fundamentos de NumPy aplicados a redes neuronales.

- Creación y manipulación de arrays
- Operaciones vectorizadas
- Producto punto (`dot product`) — operación clave en redes neuronales
- Operaciones estadísticas y procesamiento por lotes
- Ejercicios prácticos con soluciones

### 📊 `Ej_Pandas.ipynb` — Clase 6
Manipulación y preparación de datos tabulares.

- Creación y exploración de `DataFrames`
- Limpieza de datos y manejo de valores faltantes
- Detección de outliers
- Normalización y estandarización para entrenar modelos
- Ejercicios prácticos

### 📈 `Ej_Matplotlib.ipynb` — Clase 7
Visualización de datos y resultados de modelos.

- Gráficos de líneas, dispersión e histogramas
- Box plots y heatmaps
- Curvas de aprendizaje (`loss` y `accuracy`)
- Buenas prácticas de visualización
- Ejercicios prácticos

### 🧠 `Clase_8.2_TensorFlow_PyTorch.ipynb` — Clase 8.2
Implementación de redes neuronales con dos frameworks.

- Conceptos fundamentales: forward/backward pass, activaciones
- Construcción de modelos con **TensorFlow/Keras** (API de alto nivel)
- Construcción de modelos con **PyTorch** (más flexible)
- Comparación entre ambos frameworks
- Ejemplos completos de entrenamiento y evaluación

---

## 🚀 Cómo usar los notebooks

1. **Activa tu entorno de Python** (consulta `02_Guias_Instalacion/`).
2. **Lanza Jupyter** desde la terminal:
   ```bash
   jupyter notebook
   ```
   o bien:
   ```bash
   jupyter lab
   ```
3. **Abre el notebook** que corresponda a la clase que estás cursando.
4. **Ejecuta las celdas en orden** con `Shift + Enter`.
5. **Modifica el código** y experimenta — la mejor forma de aprender es probar.
6. **Resuelve los ejercicios** al final de cada notebook antes de revisar las soluciones.

---

## 📦 Requisitos

Asegúrate de tener instaladas las siguientes librerías:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
pip install tensorflow
pip install torch torchvision
```

> 💡 Si usas Google Colab, todas estas librerías ya vienen preinstaladas.

---

## 🧭 Orden recomendado de estudio

```
Ej_NumPy.ipynb  →  Ej_Pandas.ipynb  →  Ej_Matplotlib.ipynb  →  Clase_8.2_TensorFlow_PyTorch.ipynb
```

Cada notebook se construye sobre los conceptos del anterior. No te saltes pasos.

---

## 💡 Tips

- Ejecuta **todas las celdas** aunque parezcan triviales — el estado de Jupyter es secuencial.
- Si una celda falla, revisa que hayas ejecutado las celdas anteriores (especialmente los `import`).
- Usa `Kernel → Restart & Run All` cuando algo se comporte raro.
- Guarda tu progreso a menudo (`Ctrl + S` / `Cmd + S`).

---

## 🔗 Material relacionado

- 📚 Teoría: `../01_Materiales_Teoricos_Completos/`
- 📖 Referencias rápidas: `../03_Referencias_Rapidas/`
- 📅 Cronograma: `../04_Cronograma/`
- 📝 Evaluaciones: `../05_Evaluaciones_y_Examenes/`

---

**Última actualización:** Abril 2026
