Gerne! Der **Quartile Coefficient of Dispersion (QCD)** ist ein **maßstabloses Streuungsmaß**, das auf **Quartilen** basiert – also auf den **oberen und unteren 25 % der Daten**.

---

## 📌 **Definition**

Der **Quartile Coefficient of Dispersion (QCD)** wird berechnet mit:

$$
\text{QCD} = \frac{Q_3 - Q_1}{Q_3 + Q_1}
$$

Dabei ist:

* $Q_1$: **1. Quartil** (25%-Wert)
* $Q_3$: **3. Quartil** (75%-Wert)

---

## 🎯 **Zweck**

* Misst die **relative Streuung** der mittleren 50 % der Werte (robust gegenüber Ausreißern).
* **Unabhängig von der Maßeinheit** (im Gegensatz zu Range oder Varianz).
* Gut geeignet für **nicht-normalverteilte Daten** oder **ordinalskalierte Daten**, bei denen Median und Quartile sinnvoll sind.

---

## 🔍 **Interpretation**

* **QCD = 0**: Keine Streuung (alle Werte gleich)
* **Je größer der QCD**, desto **höher die Streuung**
* Werte meist zwischen **0 und 1**

---

## 📊 **Beispiel**

Angenommen, du hast folgende Quartile:

* $Q_1 = 20$
* $Q_3 = 60$

Dann ist:

$$
\text{QCD} = \frac{60 - 20}{60 + 20} = \frac{40}{80} = 0{,}5
$$

→ 50 % relative Streuung im interquartilen Bereich

---

## ✅ **Vorteile**

* **Robust gegenüber Ausreißern**
* **Einfach zu interpretieren**
* Vergleichbar zwischen Datensätzen

---

Wenn du möchtest, kann ich dir ein kleines Python- oder Pandas-Beispiel machen, um es live zu berechnen.
