Genau! ✅

Die Aussage **„Bei stetigen Zufallsvariablen ist $P(X = x) = 0$“** bedeutet:

> **Ja, weil stetige Werte unendlich teilbar sind.**
> Oder mathematischer: Weil eine **Stetige Zufallsvariable** auf einem **kontinuierlichen Wertebereich** definiert ist (z. B. alle reellen Zahlen zwischen 0 und 1, oder $\mathbb{R}$ insgesamt), ist die **Wahrscheinlichkeit, genau einen einzigen Punkt zu treffen, null**.

---

### 🧠 Warum ist das so?

Ein paar Schlüsselideen:

* **Stetige Verteilungen** wie Normalverteilung, Exponentialverteilung, usw. verteilen die Wahrscheinlichkeit **über ein Intervall**, nicht auf einzelne Punkte.
* Es gibt **unendlich viele Werte** in einem Intervall wie \[0, 1]. Die Wahrscheinlichkeit verteilt sich also auf unendlich viele mögliche Werte.
* Deshalb:

  $$
  P(X = x) = \int_{x}^{x} f(t)\,dt = 0
  $$

  → Die Fläche **unter einem Punkt** ist null.

---

### 🔍 Vergleich mit diskreten Variablen

| Art der Variable | Beispiel-Werte                 | $P(X = x)$             |
| ---------------- | ------------------------------ | ---------------------- |
| **Diskret**      | z. B. Wurf einer Münze: {0, 1} | z. B. $P(X = 1) = 0.5$ |
| **Stetig**       | z. B. Körpergröße in cm        | $P(X = 180) = 0$       |

Man kann bei stetigen Variablen **nur über Intervalle** sinnvoll Wahrscheinlichkeiten angeben:

* ✅ $P(170 < X < 180)$
* ❌ $P(X = 180)$

---

Wenn du willst, kann ich dir das Ganze gerne mit einem Plot visualisieren.
