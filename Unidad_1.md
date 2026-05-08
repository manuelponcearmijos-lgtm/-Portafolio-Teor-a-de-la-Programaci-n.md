# 🧩 Contenido del Portafolio – Matemáticas Discretas

---
 <h2>📘 1. Resumen Teórico</h2>

<p>✍️ <i>Elaborado por el estudiante</i></p>

<details>
<summary><b>🔹 Definición de proposición</b></summary>
<blockquote>
 Una proposición lógica es una afirmación o frase que expresa una idea con un valor de verdad definido: puede ser verdadera o falsa, pero nunca ambas al mismo tiempo. Son fundamentales en la lógica matemática porque permiten analizar argumentos, construir tablas de verdad y aplicar reglas de inferencia. En la vida cotidiana también aparecen constantemente, aunque muchas veces no se reconozcan como tales; por ejemplo, cuando alguien dice “Hoy llueve” está formulando una proposición, ya que esa frase puede evaluarse como verdadera o falsa según la realidad.

 **Definición**:Una proposición lógica se define como un enunciado o oración que tiene la propiedad de ser falsa (0) o verdadera (1), pero que no puede poseer ambos valores de verdad de manera simultánea. Se considera el elemento fundamental y básico de la lógica matemática 

Ejemplo: “El número 5 es impar” → Verdadero.
</blockquote>
</details>

<details>
<summary><b>🔹 Tipos de proposiciones</b></summary>
<blockquote>

 Las proposiciones lógicas se clasifican principalmente en dos grandes tipos: simples y compuestas. Las simples expresan una sola idea sin conectores, mientras que las compuestas se forman al unir proposiciones simples mediante operadores lógicos como la conjunción (∧), disyunción (∨), negación (¬), condicional (→) y bicondicional (↔), parece complicada verdad, pero lo bueno es que existen juegos donde se pueden identificar y poner en practica esas proposiciones, lo cual uno puede aprender mucho, solo que hay que buscar las maneras.
 
-Proposiciones Simples (Atómicas)
Definición: Enunciados que expresan una única idea y no contienen conectores lógicos.
Ejemplo:

“La Tierra gira alrededor del Sol” → Verdadero.

“2 + 2 = 5” → Falso.

Proposiciones Compuestas (Moleculares)
Definición: Se forman a partir de proposiciones simples unidas por conectores lógicos.

Ejemplos:

Conjunción (∧): “Hoy es lunes ∧ hace frío”.

Disyunción (∨): “Voy al cine ∨ me quedo en casa”.

Negación (¬): “¬(Está lloviendo)”.

Condicional (→): “Si estudias → apruebas”.

Bicondicional (↔): “Un número es par ↔ divisible entre 2”.
</blockquote>
</details>

<details>
<summary><b>🔹 Conectores lógicos (∧, ∨, ¬, →, ↔)</b></summary>
<blockquote>
 Los conectores lógicos son símbolos que permiten unir proposiciones simples para formar proposiciones compuestas y analizar su valor de verdad. Cada conector tiene una función específica en la lógica proposicional:

- Conjunción (∧): Une dos proposiciones y solo es verdadera si ambas lo son. Ejemplo: “Hoy es viernes ∧ hace sol”.

- Disyunción (∨): Es verdadera si al menos una de las proposiciones lo es. Ejemplo: “Estudio ∨ descanso”.

- Negación (¬): Invierte el valor de verdad de una proposición. Ejemplo: “¬(Está lloviendo)”.

- Condicional (→): Representa una relación de causa o implicación: si la primera proposición es verdadera, la segunda debe serlo. Ejemplo: “Si estudio → apruebo”.

- Bicondicional (↔): Es verdadera cuando ambas proposiciones tienen el mismo valor de verdad. Ejemplo: “Un número es par ↔ divisible entre 2”.
## 🔗 Conectores Lógicos

Los conectores permiten unir proposiciones simples para formar expresiones más complejas y analizar su valor de verdad.

| Conector | Símbolo | Definición | Ejemplo |
|----------|---------|------------|---------|
| **Conjunción** | ∧ | Es verdadera solo si ambas proposiciones lo son. | “Hoy es viernes ∧ hace sol” |
| **Disyunción** | ∨ | Es verdadera si al menos una proposición lo es. | “Estudio ∨ descanso” |
| **Negación** | ¬ | Invierte el valor de verdad de una proposición. | “¬(Está lloviendo)” |
| **Condicional** | → | Si la primera proposición es verdadera, la segunda debe serlo. | “Si estudio → apruebo” |
| **Bicondicional** | ↔ | Es verdadera cuando ambas proposiciones tienen el mismo valor de verdad. | “Un número es par ↔ divisible entre 2” |

---

📘 Estos conectores son la base para construir **tablas de verdad**, aplicar **reglas de inferencia** y diseñar **circuitos lógicos** en Matemáticas Discretas.

  
</blockquote>
</details>

<details>
<summary><b>🔹 Explicación de tablas de verdad</b></summary>
<blockquote> 
 Una tabla de verdad es una descripción organizada de todos los posibles valores de verdad que puede adoptar una proposición compuesta, considerando todas las combinaciones posibles de sus variables proposicionales. Según el resultado final, las proposiciones se clasifican en:

•	Tautología: Cuando la proposición es verdadera para todas las asignaciones posibles de valores.

•	Contradicción: Cuando la proposición es siempre falsa en todos los casos de su tabla de verdad.

•	Contingencia: Cuando la proposición puede ser tanto verdadera como falsa (una mezcla de ambos), dependiendo de los valores de las proposiciones que la integran.
 
**Nota**: Quiero a dar a conocer que la primera vez que vi este tema mi cabeza voló por los cielos ya que no entendía nada, y me esforzaba mucho para no quedarme atrás, pero después de esa clase observe un tutorial y la verdad se me hizo muy sencillo a tal punto que me sabia las reglas al derecho y al revés, el principal problema no fue el maestro si no fui yo, debido a que tenia que pedir ayuda peo no lo hice.

## 📊 Tablas de Verdad de Conectores Lógicos

### 1. Negación (¬p)
| p | ¬p |
|:-:|:-:|
| V | F |
| F | V |

---

### 2. Conjunción (p ∧ q)
| p | q | p ∧ q |
|:-:|:-:|:-----:|
| V | V | V |
| V | F | F |
| F | V | F |
| F | F | F |

---

### 3. Disyunción (p ∨ q)
| p | q | p ∨ q |
|:-:|:-:|:-----:|
| V | V | V |
| V | F | V |
| F | V | V |
| F | F | F |

---

### 4. Condicional (p → q)
| p | q | p → q |
|:-:|:-:|:-----:|
| V | V | V |
| V | F | F |
| F | V | V |
| F | F | V |

---

### 5. Bicondicional (p ↔ q)
| p | q | p ↔ q |
|:-:|:-:|:-----:|
| V | V | V |
| V | F | F |
| F | V | F |
| F | F | V |

 
</blockquote>
</details>

<details>
<summary><b>🔹 Principales leyes lógicas</b></summary>
<blockquote>
 También llamadas "Leyes de las proposiciones" o "Teoremas", se utilizan para simplificar expresiones complejas. Las más destacadas son:

 ## 📑 Principales Leyes Lógicas

| Ley | Expresión | Ejemplo |
|-----|-----------|---------|
| **Identidad** | p ∧ V = p ; p ∨ F = p | “Estudio ∧ verdadero = estudio” |
| **Dominio (Anulación)** | p ∨ V = V ; p ∧ F = F | “Estudio ∨ verdadero = verdadero” |
| **Idempotencia** | p ∨ p = p ; p ∧ p = p | “Estudio ∨ estudio = estudio” |
| **Doble Negación** | ¬(¬p) = p | “No es falso que estudio = estudio” |
| **Conmutativa** | p ∨ q = q ∨ p ; p ∧ q = q ∧ p | “Estudio ∨ descanso = descanso ∨ estudio” |
| **Asociativa** | (p ∨ q) ∨ r = p ∨ (q ∨ r) | “(Estudio ∨ descanso) ∨ juego = Estudio ∨ (descanso ∨ juego)” |
| **Distributiva** | p ∨ (q ∧ r) = (p ∨ q) ∧ (p ∨ r) | “Estudio ∨ (descanso ∧ juego)” |
| **De Morgan** | ¬(p ∧ q) = ¬p ∨ ¬q ; ¬(p ∨ q) = ¬p ∧ ¬q | “No (estudio ∧ descanso) = No estudio ∨ no descanso” |
| **Absorción** | p ∨ (p ∧ q) = p ; p ∧ (p ∨ q) = p | “Estudio ∨ (estudio ∧ descanso) = estudio” |
| **Complemento** | p ∨ ¬p = V ; p ∧ ¬p = F | “Estudio ∨ no estudio = verdadero” |


</blockquote>
</details>

<details>
<summary><b>🔹 Reglas de inferencia</b></summary>
<blockquote>
Son principios que permiten deducir conclusiones válidas a partir de premisas.  
Ejemplo:  
1️⃣ P → Q  
2️⃣ P  
∴ Q (Modus Ponens)
</blockquote>
</details>


## 2. 📊 Ejercicios Resueltos (mínimo 5)
Incluye:

- ✒️ Traducción de lenguaje natural a simbólico  
- 📐 Construcción de tablas de verdad  
- 🧮 Identificación de tautologías, contradicciones y contingencias  
- 🔧 Aplicación de leyes proposicionales  
- ✅ Validación de argumentos  

👉 Cada ejercicio debe mostrar **procedimiento paso a paso**.

---

## 3. 🧠 Ejercicio Aplicado (Caso Real)
- 🌍 Plantear un problema cotidiano  
- 🔹 Definir proposiciones  
- 🔹 Expresar simbólicamente  
- 🔹 Analizar con lógica proposicional  
- 🔹 Concluir resultados  

---

## 4. 🔍 Reflexión Personal
Responde:

- 🤔 **¿Qué fue lo más difícil de entender?**
 Desde mi
  
- 💡 ¿Qué tema comprendí mejor?  
- 🚀 ¿Cómo puedo aplicar la lógica en mi carrera?  

---
 

