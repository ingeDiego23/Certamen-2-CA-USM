
# 🧠 Certamen 2 - Computación Aplicada - Universidad Técnica Federico Santa María

Este repositorio contiene el desarrollo del **Certamen 2** del curso **Computación Aplicada**, impartido en la Universidad Técnica Federico Santa María (USM). A través del análisis de diferentes conjuntos de datos reales e industriales, se aplican técnicas de ciencia de datos, limpieza, visualización y procesamiento para evaluar el estado de salud de componentes industriales.

---

## 🎯 Objetivos Generales

- Aplicar herramientas de análisis exploratorio de datos (EDA).
- Detectar anomalías y patrones operacionales mediante sensores.
- Simular condiciones de desgaste y fallas con datos reales.
- Presentar análisis interpretables desde una perspectiva ingenieril.

---

## 📁 Estructura del Proyecto

```
📂 Aceite.ypnb/                 → Análisis de aceites lubricantes
📂 Aceite data set/             → Datos originales y procesados de aceites
📂 Chancador.ipynb/             → Notebooks con ventanas de tiempo aplicadas a sensores de chancadores
📂 Motores Aviones ipynb/       → Notebooks con simulaciones de fallas (NASA CMAPSS)
📂 Motores de Aviones Data Set/ → Datos crudos (train_FD001–FD004)
📂 Motores Informe/             → Informe de motores en PDF
📂 Aceite Informe/              → Informe de aceites en PDF
```

---

## 🔬 Áreas de Análisis

### 🛢️ Aceites Lubricantes

- Procesamiento de datos históricos de análisis de laboratorio.
- Detección de patrones y posibles contaminaciones o desgaste prematuro.
- Limpieza, escalado y normalización de variables químicas.
- Análisis por tipo de metal presente en el aceite.

### 🪨 Chancadores

- Segmentación en ventanas de 60, 120 y 180 minutos para evaluar desempeño.
- Visualización de detenciones, carga de motor y temperatura.
- Preprocesamiento y detección de condiciones anómalas.

### ✈️ Motores de Avión (NASA CMAPSS)

- Simulación de vida útil restante (RUL) por motor FD001–FD004.
- Cálculo de estadísticas por motor y visualización de ciclos.
- Análisis supervisado de condiciones de operación y degradación.

---

## 🛠️ Tecnologías Utilizadas

- Python 3.x
- Jupyter Notebook
- Bibliotecas: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

---

## 🚀 Instrucciones de Uso

1. Clonar este repositorio:
   ```bash
   git clone https://github.com/ingeDiego23/Certamen-2-CA-USM.git
   ```

2. Ejecutar los notebooks:
   ```bash
   jupyter notebook
   ```

3. Navegar por los directorios y abrir:
   - `aceite_archivolimpio.ipynb` para el análisis de aceites
   - `chancadorVentana120T.ipynb` y similares para chancadores
   - `FD001.ipynb` a `FD004.ipynb` para motores de avión

---

## 📄 Informes

- 📘 `Aceite Informe/aceites.pdf` — Informe técnico de lubricantes.
- 📘 `Motores Informe/Motores Informe.pdf` — Análisis completo de simulaciones de motores.

---

## 👨‍💻 Autor

- Diego Ingelmo – [@ingeDiego23](https://github.com/ingeDiego23)

---

## 🧾 Licencia

Este proyecto está licenciado bajo los términos de la **MIT License**.
