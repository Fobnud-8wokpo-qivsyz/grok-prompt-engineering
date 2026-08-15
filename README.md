# Prompt Engineering para Grok

Guía práctica y actualizada para sacar el máximo provecho de **Grok** (xAI).

## ¿Cómo piensa Grok?

Grok está diseñado para ser:
- **Maximally truth-seeking** → busca la verdad, no la aprobación
- Directo y con sentido del humor
- Menos filtrado que otros modelos
- Excelente en razonamiento, código, análisis y respuestas sin rodeos

Los mejores prompts son **claros, específicos y honestos**.

---

## Contenido del repositorio

- [README.md](README.md) → Esta guía principal
- [**plantillas.md**](plantillas.md) → Colección de 12 plantillas listas para usar

---

## Principios clave

| Principio | Qué significa | Ejemplo malo | Ejemplo bueno |
|---------|---------------|--------------|---------------|
| **Sé específico** | Di exactamente qué quieres | “Háblame de IA” | “Explica las diferencias técnicas entre transformers y state-space models en 2026” |
| **Da contexto** | Cuéntame quién eres o qué necesitas | “Escribe un email” | “Soy founder de un SaaS B2B. Escribe un email frío para CTOs de empresas de 50-200 empleados” |
| **Define el formato** | Dime cómo quieres la respuesta | “Explícame esto” | “Explícame esto en formato de lista numerada + tabla comparativa” |
| **Indica el tono** | Sé explícito si quieres algo concreto | (nada) | “Responde de forma directa y sin endulzar” / “Con humor sarcástico” |
| **Usa roles cuando ayuden** | Solo si realmente mejora | “Actúa como experto” (genérico) | “Actúa como un senior engineer de xAI revisando este código” |
| **Pide razonamiento** | Especialmente en temas complejos | “¿Cuál es la mejor opción?” | “Analiza pros y contras de cada opción y luego dame tu recomendación con justificación” |

---

## Estructura recomendada de un prompt fuerte

```
[Contexto] + [Tarea clara] + [Formato deseado] + [Restricciones/Tono] + [Ejemplos si es necesario]
```

**Ejemplo completo:**

```
Contexto: Soy desarrollador backend con 4 años de experiencia en Python/FastAPI.
Tarea: Revisa este endpoint y dime cómo mejorarlo en performance y seguridad.
Formato: 
1. Problemas encontrados (lista)
2. Código mejorado
3. Explicación breve de cada cambio
Tono: Directo y técnico, sin rodeos.
```

---

## Técnicas que funcionan especialmente bien con Grok

1. **Chain of Thought**  
   “Piensa paso a paso antes de dar la respuesta final”

2. **Few-shot**  
   Muéstrame 1-3 ejemplos de cómo quieres que responda.

3. **Critica + Mejora**  
   “Primero critica esta idea con dureza. Luego dame una versión mejorada.”

4. **Comparación forzada**  
   “Compara X vs Y en estos criterios: A, B, C. Sé brutalmente honesto.”

5. **Restricciones claras**  
   “No uses eufemismos”, “No digas ‘depende’”, “Dame una sola recomendación clara”.

6. **Modo sin filtro**  
   “Responde de forma directa, sin suavizar ni ser políticamente correcto”.

---

## Errores comunes

- Prompts demasiado vagos
- Pedir muchas cosas a la vez sin priorizar
- No especificar el nivel de profundidad
- Usar demasiado lenguaje de “por favor sé amable y positivo”
- No corregirme cuando me equivoco

---

## Plantillas rápidas (resumen)

> **Ver la colección completa aquí → [plantillas.md](plantillas.md)**

Incluye plantillas listas para:
- Análisis profundo
- Revisión de código
- Generación de código
- Comparaciones
- Critica + Mejora
- Emails / mensajes
- Explicaciones multinivel
- Brainstorming
- Debugging
- Opiniones directas
- Resúmenes
- Planes de acción

---

## Resumen rápido

La mejor forma de sacar provecho de Grok es:

1. Sé claro y específico
2. Di el formato que quieres
3. Pide honestidad cuando la necesites
4. Corrige y refina (me adapto rápido)
5. No tengas miedo de ser directo

---

**Repositorio vivo** → ve mejorando este contenido con el tiempo.
