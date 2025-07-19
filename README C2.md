
# 🧠 Certamen 2 - Computación Aplicada - Universidad Técnica Federico Santa María

Este repositorio contiene el desarrollo del **Certamen 2** para la asignatura **Computación Aplicada** de la Universidad Técnica Federico Santa María (USM). El trabajo se centra en el análisis de datos industriales utilizando herramientas de Python y ciencia de datos para evaluar la condición de distintos sistemas: aceites lubricantes, chancadores y motores aeronáuticos.

---

## 🎯 Objetivos Generales

- Aplicar técnicas de análisis exploratorio y preprocesamiento de datos.
- Detectar fallas, anomalías y degradaciones en activos industriales.
- Utilizar ventanas de tiempo y escalado de variables para modelar condiciones de operación.
- Presentar resultados con sustento técnico en notebooks y reportes.

---

## 📁 Estructura del Proyecto

```
📂 Aceite.ypnb/                 → Análisis de contaminantes en aceites lubricantes
📂 Aceite data set/             → Datos originales y preprocesados de laboratorio
📂 Aceite Informe/              → Informe académico en PDF

📂 Chancador.ipynb/             → Análisis de sensores de chancadores por ventana de tiempo
📂 Chancadores Informe/         → Informe técnico de análisis en minería

📂 Motores Aviones ipynb/       → Notebooks de simulaciones de fallas (NASA CMAPSS)
📂 Motores de Aviones Data Set/ → Archivos crudos de simulación FD001–FD004
📂 Motores Informe/             → Informe completo de predicción de fallas
📂 Reboiler ipynb_checkpoints/   → Notebooks de análisis térmico de reboiler
📂 Reboilers Data SEt/           → Archivos con datos crudos y depurados
📂 Reboiler Informe/             → Informe de presentación en formato PowerPoint
```

---

## 🔍 Áreas de Análisis

### ♨️ Reboilers
- Análisis de datos industriales de un sistema de recirculación térmica (reboiler).
- Limpieza y renombramiento de variables de sensores (temperatura, presión, conductividad, carga de motor).
- Conversión de series temporales y agrupación en ventanas de 120 minutos.
- Aplicación de filtros para identificar comportamientos anómalos en base a umbrales de operación.
- Presentación de resultados en formato notebook y diapositivas técnicas.



### 🛢️ Aceites Lubricantes
- Evaluación de desgaste de maquinaria mediante elementos metálicos en muestras de aceite.
- Procesamiento, limpieza y normalización de variables.
- Visualización comparativa de niveles de impurezas.

### 🪨 Chancadores
- Análisis de comportamiento de variables de sensores en distintos períodos.
- Agrupamiento de datos en ventanas de 60, 120 y 180 minutos.
- Estudio de paradas, cargas y condiciones anómalas en planta minera.

### ✈️ Motores de Avión (NASA CMAPSS)
- Simulación de condiciones de desgaste progresivo en motores.
- Estimación de RUL (Remaining Useful Life).
- Visualización del ciclo de vida de múltiples motores bajo distintas condiciones.

---

## 🛠️ Herramientas y Tecnologías

- Python 3.x
- Jupyter Notebook
- Bibliotecas: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

---

## 🚀 Instrucciones de Uso

1. Clonar este repositorio:
   ```bash
   git clone https://github.com/ingeDiego23/Certamen-2-CA-USM.git
   ```

2. Abrir el entorno Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Explorar notebooks por carpeta según el área de análisis:
   - `aceite_archivolimpio.ipynb`
   - `chancadorVentana*.ipynb`
   - `FD001.ipynb`, `FD002.ipynb`, etc.

---

## 📄 Informes Académicos

- 📘 Aceites: `Aceite Informe/aceites.pdf`
- 📘 Chancadores: `Chancadores Informe/Informe_Chancador.pdf`
- 📘 Motores: `Motores Informe/Motores Informe.pdf`

---

## 👥 Autores

- Diego Ingelmo – [@ingeDiego23](https://github.com/ingeDiego23)
- Milovan Bustamante – [@milovanbustamante](https://github.com/milovanbustamante)

---

## 📜 Licencia

Este proyecto se publica bajo la licencia **MIT**.
