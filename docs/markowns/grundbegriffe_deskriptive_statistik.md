Gerne! Hier ist der **Überblick über die wichtigsten Begriffe der beschreibenden Statistik inklusive der zentralen Formeln**.

---

## 📚 **Beschreibende Statistik – Begriffe & Formeln**

---

### 🔢 **1. Grundbegriffe** *(ohne Formeln)*

| Begriff             | Bedeutung                                           |
| ------------------- | --------------------------------------------------- |
| **Grundgesamtheit** | Alle Elemente, über die man Aussagen treffen möchte |
| **Stichprobe (n)**  | Teilmenge der Grundgesamtheit                       |
| **Merkmal (X)**     | Untersuchte Eigenschaft                             |
| **Merkmalswert**    | Einzelner beobachteter Wert $x_i$                   |

---

### 📍 **2. Lagemaße**

| Maß                           | Formel                                                           | Beschreibung                           |
| ----------------------------- | ---------------------------------------------------------------- | -------------------------------------- |
| **Mittelwert** (arithmetisch) | $\bar{x} = \frac{1}{n} \sum_{i=1}^{n} x_i$                       | Durchschnitt aller Werte               |
| **Gewogener Mittelwert**      | $\bar{x}_\text{gewichtet} = \frac{\sum x_i \cdot w_i}{\sum w_i}$ | Mit Gewichten $w_i$                    |
| **Median**                    | –                                                                | Wert in der Mitte der sortierten Daten |
| **Modus**                     | –                                                                | Häufigster Wert                        |

---

### 📊 **3. Streuungsmaße**

| Maß                            | Formel                                                   | Bedeutung                                             |
| ------------------------------ | -------------------------------------------------------- | ----------------------------------------------------- |
| **Range (Spannweite)**         | $\text{Range} = x_{\text{max}} - x_{\text{min}}$         | Einfacher Streubereich                                |
| **Varianz** (Stichprobe)       | $s^2 = \frac{1}{n - 1} \sum_{i=1}^{n} (x_i - \bar{x})^2$ | Maß für die durchschnittliche quadratische Abweichung |
| **Standardabweichung**         | $s = \sqrt{s^2}$                                         | Quadratwurzel der Varianz                             |
| **Interquartilsabstand (IQR)** | $IQR = Q_3 - Q_1$                                        | Bereich der mittleren 50 %                            |

---

### ↕️ **4. Schiefe (Skewness)**

| Maß                                                 | Formel                                                               | Bedeutung          |
| --------------------------------------------------- | -------------------------------------------------------------------- | ------------------ |
| **Schiefe γ**                                       | $\gamma = \frac{1}{n} \sum \left( \frac{x_i - \bar{x}}{s} \right)^3$ | Maß für Asymmetrie |
| **Interpretation**                                  |                                                                      |                    |
| → $\gamma > 0$: **positive Schiefe** (rechtsschief) |                                                                      |                    |
| → $\gamma < 0$: **negative Schiefe** (linksschief)  |                                                                      |                    |
| → $\gamma = 0$: **symmetrisch**                     |                                                                      |                    |

---

### 📐 **5. Visualisierung** *(keine Formeln)*

| Diagrammtyp   | Verwendung                            |
| ------------- | ------------------------------------- |
| Histogramm    | Verteilung metrischer Daten           |
| Boxplot       | Quartile, Median, Ausreißer           |
| Stabdiagramm  | Häufigkeiten kategorialer Daten       |
| Streudiagramm | Beziehung zweier metrischer Variablen |

---

### 📈 **6. Zusammenhangsmaße**

| Maß                                   | Formel                                                                   | Bedeutung                                     |
| ------------------------------------- | ------------------------------------------------------------------------ | --------------------------------------------- |
| **Kovarianz**                         | $\text{Cov}(X, Y) = \frac{1}{n - 1} \sum (x_i - \bar{x})(y_i - \bar{y})$ | Gemeinsame Streuung zweier Variablen          |
| **Korrelation (Pearson)**             | $r = \frac{\text{Cov}(X, Y)}{s_X \cdot s_Y}$                             | Stärke des linearen Zusammenhangs (−1 bis +1) |
| **Lineare Regression**                | $y = a x + b$                                                            |                                               |
| mit                                   |                                                                          |                                               |
| $a = \frac{\text{Cov}(X, Y)}{s_X^2}$, |                                                                          |                                               |
| $b = \bar{y} - a \bar{x}$             | Vorhersage-Modell                                                        |                                               |

---

### 🧠 Merksatz:

> Die deskriptive Statistik **beschreibt Daten**:
> → Wo liegt der Durchschnitt?
> → Wie stark schwanken die Werte?
> → Gibt es Muster oder Ausreißer?

---

Wenn du möchtest, kann ich dir diesen Überblick auch als übersichtliches PDF-Dokument exportieren oder eine **visuelle Karte (z. B. Mindmap oder Poster)** dazu machen. Sag einfach Bescheid!
