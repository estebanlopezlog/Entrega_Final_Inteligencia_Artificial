# 🚀 Proyecto Final – Inteligencia Artificial: Generación de Prompts

## PromptLab: Sistema de Generación y Evaluación de Prompts

---

## 👤 Autor

**Esteban López**  
Curso: **Inteligencia Artificial – Generación de Prompts**  
Comisión: **95825**

---

## 📌 Problema Detectado

> En entornos laborales reales —especialmente en planificación, operaciones y análisis de datos—  
> el uso de modelos de IA suele realizarse sin estructura definida.
>
> Esto genera:
>
> - Prompts ambiguos  
> - Resultados inconsistentes  
> - Reformulaciones constantes  
> - Dependencia del ensayo y error  
> - Pérdida de tiempo operativo  
>
> El problema no es la IA.  
> Es la falta de diseño estratégico del prompt.

---

## 🎯 Objetivo del Proyecto

> Diseñar un sistema estructurado que permita:
>
> - Generar prompts reproducibles  
> - Mejorar la consistencia del output  
> - Reducir iteraciones innecesarias  
> - Evaluar calidad estructural  
> - Crear una base escalable para uso profesional  

---

## 🧠 Enfoque Metodológico

El sistema organiza el diseño de prompts en cinco etapas:

1. Definición del contexto  
2. Asignación de rol  
3. Clarificación del objetivo  
4. Definición del formato de salida  
5. Evaluación estructural  

> Este enfoque reduce ambigüedad y mejora la reutilización del resultado.

---

## 🔎 Implementación – Modelo Texto → Texto

Se comparan dos enfoques:

### 🔹 Prompt Básico
> Respuesta general y conceptual.

### 🔹 Prompt Fast (Optimizado)

Incluye:

- Role Prompting  
- Salida estructurada (JSON)  
- Identificación de problema  
- KPI cuantificable  
- Fórmula matemática  
- Dimensión estratégica  

### ✍ Ejemplo de Prompt

Actúa como analista de datos senior.
Analiza el siguiente objetivo: [objetivo].
Identifica:
- Problema cuantificable
- Indicador propuesto
- Fórmula matemática
- Dimensión estratégica
Devuelve el resultado en formato estructurado.


## 🎨 Implementación – Modelo Texto → Imagen

Se diseñaron prompts orientados a:
Visualizar flujos de análisis
Representar procesos operativos
Generar apoyo visual para documentación estratégica

✍ Ejemplo
Genera una imagen conceptual que represente:
datos → análisis → decisiones.
Estilo profesional, minimalista.

## 📊 Evaluación del Sistema

Se implementaron métricas simuladas para:
- Conteo de tokens
- Evaluación de estructura
- Nivel de accionabilidad
Resultados observados:
- Prompt Básico → Baja estructura
- Prompt Fast → Alta estructura y reutilización
Aunque el Prompt Fast utiliza más tokens, reduce iteraciones y mejora eficiencia operativa.


## ⚙️ Arquitectura del Sistema
Entrada
→ Objetivo estratégico

Motor
→ Prompt Básico
→ Prompt Fast

Evaluación
→ Métrica de estructura
→ Métrica de accionabilidad
→ Simulación de tokens

Salida
→ Indicador definido
→ Fórmula matemática
→ Dimensión estratégica
→ Formato estructurado

##💡 Viabilidad
Técnica
- Implementado en Jupyter Notebook
- Compatible con Gemini / ChatGPT
- No requiere infraestructura compleja
Económica
- Uso de herramientas gratuitas y optimización de consultas.
Temporal
- Desarrollo dentro del cronograma académico.

## 🔮 Proyección Profesional

Este sistema puede evolucionar hacia:
- Automatización de generación de KPIs
- Generadores automáticos de reportes
- Asistentes internos para equipos operativos
- Validadores de calidad de prompts
- No es solo un trabajo académico.
- Es una base aplicable a entornos empresariales reales.

## 🛠 Tecnologías Utilizadas

Python 3.13
Jupyter Notebook
Prompt Engineering
Modelos LLM (Texto → Texto / Texto → Imagen)
