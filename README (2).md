# 📊 Certamen 2 – Computación Aplicada – USM

Este repositorio contiene el desarrollo del **Certamen 2** para la asignatura **Computación Aplicada**, impartida en la Universidad Técnica Federico Santa María (USM). El objetivo principal del trabajo es aplicar herramientas de procesamiento y análisis de datos en dos contextos industriales relevantes: el monitoreo de **chancadores** en minería y el análisis de **motores de avión** utilizando datos de sensores.

---

## 🎯 Objetivo General

Aplicar técnicas de análisis exploratorio, limpieza de datos, visualización y aprendizaje automático para diagnosticar y predecir comportamientos en sistemas industriales, promoviendo el desarrollo de habilidades prácticas con Python y librerías de ciencia de datos.

---

## 📁 Estructura del Proyecto

```
Certamen-2-CA-USM/
│
├── Chancador.ipynb/                   # Notebooks con modelos aplicados a chancadores
├── Chancadores Data SEt/             # Datos originales en formato Excel
├── DATA LIMPIA Chancadores/          # Datos procesados y limpios (formato CSV)
│
├── Motores Aviones ipynb/            # Notebooks con análisis de fallas de motores (NASA)
├── Motores Aviones csv/              # Datos preprocesados de los motores
└── README.md                         # Este archivo
```

---

## 🧪 Tecnologías y Librerías

- **Python 3.x**
- **Jupyter Notebooks** – Entorno interactivo para prototipado
- **Pandas** – Manejo y limpieza de datos
- **NumPy** – Cálculo numérico
- 

---

## 📌 Contenido Destacado

### 🔧 Chancadores

Se analiza el rendimiento de chancadores (máquinas que reducen el tamaño del mineral) mediante datos temporales de detenciones. Se aplican ventanas móviles de análisis para observar patrones y posibles eventos críticos en la operación.

**Ejemplo de notebook:**
- `chancadorVentana60T-checkpoint.ipynb`: Aplicación de ventanas móviles de 60 minutos para caracterización temporal.

### ✈️ Motores de Avión

Basado en el conjunto de datos de NASA sobre motores a reacción, se analiza la **vida útil remanente** y se simulan modelos de fallo progresivo.

**Ejemplo de notebook:**
- `FD001.ipynb`: Análisis del comportamiento del motor en distintos ciclos de uso, identificación de patrones de desgaste.

---

## ⚙️ ¿Cómo ejecutar el proyecto?

1. Clona el repositorio:
   ```bash
   git clone https://github.com/ingeDiego23/Certamen-2-CA-USM.git
   ```
2. Instala los requerimientos (opcional):
   ```bash
   pip install -r requirements.txt
   ```
3. Abre Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Explora los notebooks disponibles en las carpetas:
   - `Chancador.ipynb`
   - `Motores Aviones ipynb`

---

## 👨‍🎓 Autor

 
  Estudiante – Universidad Técnica Federico Santa María  
  GitHub: [@ingeDiego23](https://github.com/ingeDiego23)

---

## 📄 Licencia

Distribuido bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

---

## 📚 Agradecimientos

Este trabajo se inspira en datasets reales como los provistos por la NASA y en desafíos comunes del análisis de datos en la industria minera. Agradezco al cuerpo docente de la asignatura por su guía y apoyo en este proceso de aprendizaje.

