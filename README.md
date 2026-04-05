# Análisis de conflictividad laboral en plataformas de reparto (2006–2023)

## Descripción del proyecto

Este proyecto analiza la evolución de la conflictividad laboral en el sector de mensajería, cadetería y reparto urbano de alimentos en Argentina entre 2006 y 2023.

El objetivo es comparar los patrones de conflicto entre:

- Trabajadores del sector tradicional  
- Trabajadores de plataformas digitales  

y evaluar cómo la expansión de las plataformas transformó:

- la intensidad del conflicto  
- los tipos de demandas  
- las formas de protesta  
- las formas de organización  

---

## Problema de negocio / analítico

Las plataformas digitales introducen nuevas formas de organización del trabajo, caracterizadas por:

- dispersión geográfica  
- ausencia de relación laboral formal  
- gestión algorítmica  

Esto plantea una pregunta clave:

¿Las plataformas debilitan o transforman la conflictividad laboral?

---

## Dataset

- Fuente: Secretaría de Trabajo de la Nación  
- Periodo: 2006–2023  
- Dataset original: 155 filas, 120 variables  
- Dataset final: 1000 filas (expansión con datos sintéticos)  
- Variables: tipo de demanda, acción, organización, ubicación, sector  

Se aplicaron procesos de:

- limpieza de datos  
- análisis exploratorio (EDA)  
- reducción de variables (feature selection)  

---

## Principales insights

### 1. Crecimiento exponencial de la conflictividad

La cantidad de conflictos crece fuertemente a partir de 2018, superando los 300 eventos en 2023 :contentReference[oaicite:1]{index=1}  

Insight: la expansión de plataformas coincide con un aumento del conflicto  

---

### 2. Alta concentración geográfica

Los conflictos se concentran principalmente en:

- AMBA  
- Santa Fe  

Insight: el conflicto está vinculado a zonas de alta densidad urbana  

---

### 3. Las plataformas concentran la conflictividad

- 60% de los conflictos corresponden a trabajadores de plataformas :contentReference[oaicite:2]{index=2}  

Insight clave: lejos de desmovilizar, las plataformas intensifican el conflicto  

---

### 4. Predominan demandas no salariales

- ~70% de los conflictos no son salariales  
- Principales temas:
  - seguridad (robos, accidentes)  
  - condiciones laborales  

Insight: el problema central no es solo el ingreso, sino el riesgo laboral  

---

### 5. Nuevas formas de protesta

- Menos del 30% de las protestas son huelgas :contentReference[oaicite:3]{index=3}  
- Predominan:
  - movilizaciones  
  - cortes  
  - acciones sin paro  

Insight: el conflicto se adapta a la estructura flexible del trabajo  
---

### 6. Cambio en las demandas según el sector

- Sector tradicional → reclamos salariales  
- Plataformas → reclamos de seguridad  

Insight estructural: cambia la naturaleza del conflicto  

---

### 7. Persistencia del rol sindical

- El sindicato sigue siendo el principal organizador :contentReference[oaicite:4]{index=4}  
- Pero crecen:
  - organizaciones informales  
  - redes de trabajadores  

Insight: transición hacia formas híbridas de organización  

---

## Visualizaciones desarrolladas

- Evolución temporal de conflictos  
- Mapa de intensidad por provincia  
- Comparación plataformas vs tradicional  
- Distribución de demandas  
- Tipos de protesta  
- Formas de organización  

---

## Tecnologías utilizadas

- Python (pandas, matplotlib, seaborn)  
- Generación de datos sintéticos (SDV)   
- GeoJSON para mapas  

---

## Valor del proyecto

Este análisis demuestra que:

1. Las plataformas no eliminan el conflicto  
2. Transforman su forma  
3. Generan nuevas demandas y estrategias  
Aporta evidencia cuantitativa a un debate teórico actual  

---

## Próximos pasos

- Modelos predictivos de conflictividad  
- Clustering de tipos de conflicto según sector tradicional o de aplicación

---

## 👤 Autor

Iván Montes de Oca  
🔗 https://github.com/ivanmontesdeoca
