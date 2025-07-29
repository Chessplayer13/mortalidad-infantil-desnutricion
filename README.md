# 🗺️ Mortalidad Infantil por Desnutrición en Colombia

Este repositorio contiene un análisis geoespacial de la mortalidad infantil por desnutrición en Colombia, con visualizaciones a nivel municipal y departamental. El objetivo es identificar los territorios con mayores tasas de mortalidad en niños menores de 5 años y visibilizar las desigualdades territoriales en salud infantil.

---

## 📂 Estructura del repositorio

<img width="587" height="276" alt="image" src="https://github.com/user-attachments/assets/80fd388e-a073-4cb1-aa00-0151ba7d0759" />


---
## 📸 Vista previa de la animación

A continuación se muestra una imagen de referencia del resultado final generado por el notebook `02_animacion_mortalidad_infantil_desnutricion.ipynb`
<img width="812" height="675" alt="image" src="https://github.com/user-attachments/assets/127d7d3d-4eac-4ec3-a3dd-b1d82be913af" />


---

## 🚀 ¿Cómo usar este repositorio?

Para generar o visualizar la animación, puedes seguir dos caminos:

### ▶️ Opción rápida: solo ejecutar la animación

El archivo final (`tasa_mortalidad_menores_5.csv`) ya está incluido en la carpeta `Data/`, por lo que puedes ejecutar directamente:

- `02_animacion_mortalidad_infantil_desnutricion.ipynb`

Este notebook genera la animación del mapa con las tasas de mortalidad infantil por desnutrición a nivel municipal.

> ⚠️ **Importante:** Para ejecutar este notebook es obligatorio descargar el shapefile de municipios de Colombia y colocarlo en la carpeta `Municipios/`.  
> Esta instrucción también está explicada dentro del notebook.

---

### 🛠️ Opción avanzada: agregar nuevos años o causas de mortalidad

Si deseas modificar el análisis (por ejemplo, incluir más años o estudiar otra causa de muerte), puedes seguir el proceso descrito en:

- `01_construccion_dataset_mortalidad_desnutricion.ipynb`

Este notebook explica cómo construir el archivo base a partir de:
- Las estadísticas vitales de defunciones (`EEVV`)
- Las proyecciones de población municipal


---

## 📌 Notas importantes

- El shapefile de municipios **no está incluido** en el repositorio por superar el límite de tamaño de GitHub.
- Puedes descargarlo desde el Geoportal del DANE
  
Una vez descargado, colócalo dentro de la carpeta `Municipios/`.

---

## 📊 Objetivo

Este proyecto busca apoyar la toma de decisiones y fomentar la conciencia pública sobre la desigualdad territorial en el acceso a condiciones básicas para la infancia en Colombia, usando datos oficiales y herramientas de análisis espacial.

---

## 📚 Fuentes de datos

- Estadísticas Vitales de Defunciones (EEVV) – DANE  
- Proyecciones de población por municipio – DANE  
- División político-administrativa (DIVIPOLA) – DANE

---

## 📃 Licencia

Este repositorio se publica bajo la licencia MIT. Puedes usar, modificar y compartir este trabajo libremente, citando la fuente original.

---

## ✍️ Autor

Carlos Durán  
🔗 [LinkedIn – carlosduran-data](https://www.linkedin.com/in/carlosduran-data/)


