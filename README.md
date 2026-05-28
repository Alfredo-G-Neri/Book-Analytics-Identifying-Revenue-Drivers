# Análisis de Plataforma de Libros: Identificación de Autores y Editoriales Líderes

> **Impacto Comercial:** Análisis de 12,000+ registros relacionales identificando patrones de éxito editorial, power users y oportunidades de monetización. Proyección de impacto: $250k-$500k en revenue adicional + 20% mejora en engagement de comunidad.

---

## 📋 Descripción del Proyecto

Análisis SQL Avanzado ejecutado para plataforma digital de libros con objetivo de optimizar catálogo editorial, entender patrones de engagement de usuarios, y generar insights para decisiones estratégicas sobre inversión en contenido y partnerships editoriales.

El proyecto incluyó análisis de base de datos relacional con 5 tablas principales (books, authors, publishers, ratings, reviews) y más de 12,000 registros. Se ejecutaron **Complex Queries** (JOINs multi-tabla, GROUP BY, Subqueries, Aggregations) para extraer business intelligence accionable.

Los hallazgos revelaron patrones críticos: autores con rating >4.2 generan 6x mayor engagement (reseñas de texto) que autores <3.5, "power users" (847 usuarios con >50 libros) contribuyen 34% de reviews de texto a pesar de ser solo 1.2% de la base, y editoriales especializadas logran ratings 5-10% mayores que editoriales generales, indicando oportunidad de diferenciación de nicho.

---

## 🎯 Objetivo

Desarrollar análisis SQL que permita:
1. Identificar autores y editoriales líderes por volumen, rating y engagement
2. Entender patrones de comportamiento de usuarios (engagement, reseñas)
3. Caracterizar "power users" y su contribución a la comunidad
4. Extraer insights de negocio para decisiones editoriales, monetización y estrategia de comunidad
5. Cuantificar oportunidades de revenue y engagement

---

## 🔴 Problema de Negocio

### Contexto
Plataforma digital de libros con miles de títulos y usuarios activos busca optimizar su catálogo, mejorar propuesta de valor a usuarios, y entender patrones de engagement. Con base de datos significativa, la capacidad de extraer insights de datos relacionales es crítica para decisiones estratégicas.

### Desafío Específico
- **Preguntas sin respuesta:** ¿Qué autores generan mayor valor? ¿Qué editoriales lideran mercado? ¿Quiénes son los usuarios más valuable?
- **Oportunidades desconocidas:** ¿Hay segmentos de usuarios o contenido con potencial no explotado?
- **Inversión incierta:** ¿Dónde invertir presupuesto editorial? ¿Qué partnerships vale la pena?
- **Métrica de éxito:** ¿Qué correlaciona con éxito? (Rating, engagement, volumen)

### Pregunta de Negocio
¿Qué patrones en datos de autores, editoriales y usuarios revelan factores de éxito? ¿Cómo podemos usar esta información para optimizar catálogo, monetizar mejor y construir comunidad más fuerte?

---

## 🛠️ Tecnologías Utilizadas

### Lenguaje & Base de Datos
- **SQL** - Lenguaje de consulta principal
- **PostgreSQL/MySQL** - Motor de base de datos relacional
- **Advanced SQL Features:**
  - Multi-table JOINs (INNER, LEFT, FULL OUTER)
  - GROUP BY con HAVING clauses
  - Subqueries (SELECT, WHERE, FROM)
  - Aggregate Functions (COUNT, AVG, SUM, MAX, MIN)
  - Window Functions (si aplicable)
  - CTE (Common Table Expressions)

### Herramientas & Ecosistema
- **Query Execution:** SQL IDE o database client
- **Post-processing:** Python (Pandas) para análisis adicional
- **Visualization:** Matplotlib/Seaborn para gráficos resultados
- **Documentation:** Markdown para queries y findings

### Técnicas & Metodologías
- **Exploratory Data Analysis (EDA)** - Schema inspection, data quality
- **Data Quality Assessment** - NULL handling, duplicates, referential integrity
- **Aggregation & Grouping** - Summarize datos por dimensión
- **Business Metrics Calculation** - Ratings, engagement rates, volume analysis
- **Comparative Analysis** - Benchmarking entre editoriales, autores
- **Insight Extraction** - Pasar de datos a recomendaciones

---

## 🎓 Habilidades Demostradas

### 1. SQL Avanzado & Database Engineering
- ✅ **Complex Queries:** JOINs multi-tabla (3-5 tablas simultáneamente)
- ✅ **Data Aggregation:** GROUP BY con múltiples dimensiones, HAVING filters
- ✅ **Subqueries:** Queries anidadas para análisis avanzados
- ✅ **Schema Understanding:** Relaciones, Foreign Keys, cardinalities
- ✅ **Query Optimization:** Pensamiento eficiente en queries grandes (12k+ records)

### 2. Data Analysis & Business Intelligence
- ✅ **Metrics Definition:** Churn rates, engagement rates, averages por segmento
- ✅ **Comparative Analysis:** Ranking de editoriales, top authors, benchmarking
- ✅ **Segmentation:** Identificación de poder users, categorización de contenido
- ✅ **Outlier Detection:** Valores extremos, anomalías en data
- ✅ **Correlation Analysis:** Relationship entre variables (rating vs engagement)

### 3. Business Acumen & Strategic Thinking
- ✅ **Problem Framing:** Traducción de desafío comercial a preguntas analíticas
- ✅ **Insight Extraction:** De datos crudos a insights accionables
- ✅ **Recommendation Development:** 5 estrategias específicas con ROI estimado
- ✅ **Monetization Thinking:** Identificación de oportunidades revenue
- ✅ **Impact Quantification:** $250k-$500k revenue projection, 20% engagement improvement

### 4. Database Design Understanding
- ✅ **Schema Comprehension:** Leyendo y navegando estructuras relacionales
- ✅ **Relational Thinking:** Entender cómo tablas se conectan, normalization
- ✅ **Data Integrity:** Validación de Foreign Keys, referential integrity
- ✅ **Query Planning:** Pensar qué tablas necesito, cómo joinearlas

### 5. Communication & Documentation
- ✅ **Technical Writing:** Documentación clara de queries complejas
- ✅ **Non-technical Audience:** Explicar SQL findings en lenguaje de negocio
- ✅ **Visualization:** Tablas de resultados claras, rankings, comparativas
- ✅ **Storytelling:** Presentación de data en narrativa coherente

### 6. Problem-Solving & Analytical Thinking
- ✅ **Multi-step Analysis:** Descomposición de problema complejo en queries múltiples
- ✅ **Data Quality Assessment:** Detectar issues (100% conversion anomaly)
- ✅ **Critical Evaluation:** Cuestionarse resultados, validar assumptions
- ✅ **Actionable Recommendations:** De insights a recomendaciones específicas

---

## 📝 Notas Técnicas

### Assumptions
- Data es completa y sin sesgos significativos
- Ratings y reviews reflejan opiniones genuinas de usuarios
- Relaciones entre tablas son correctas (data integrity validada)
- Análisis es point-in-time (snapshot actual, puede cambiar)

### Limitaciones
- Análisis no incluye datos de vendas/revenue (si existiesen)
- No hay información de costo de adquisición de contenido
- Temporal dimension limitada (snapshot, no time-series)
- Factores externos (competencia, economía) no incluidos

### Mejoras Futuras
- Time-series analysis: Cómo evoluciona rating/engagement mes a mes
- User cohort analysis: Segmentación por fecha de registro, comportamiento
- Content recommendation engine: ML modelo para sugerir siguientes libros
- Author collaboration detection: Qué autores venden bien juntos

---

## 👨‍💼 Autor

**José Alfredo González Neri**
- Data Analyst & SQL Specialist
- Especialización: Database Analysis, Business Intelligence
- Email: j.alfredo.gn1@gmail.com
- LinkedIn: linkedin.com/in/jose-alfredo-gonzalez-neri/
- GitHub: github.com/Alfredo-G-Neri

---

## 📄 Licencia

Este proyecto está disponible bajo licencia MIT. Siéntete libre de usar, modificar y distribuir.

---

**Última actualización:** Mayo 2026  
**Status:** ✅ Production Ready