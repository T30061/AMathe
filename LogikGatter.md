# Logikgatter & Boolesche Algebra

## Einleitung zur Booleschen Algebra

Die Boolesche Algebra ist die Grundlage der digitalen Logik und basiert auf zwei Werten: 0 (Falsch) und 1 (Wahr). Mit booleschen Operationen können logische Aussagen mathematisch dargestellt und vereinfacht werden.

Die wichtigsten Operatoren sind: UND (AND), ODER (OR), NICHT (NOT).

---

## Grundlegende Logikgatter

### 1. NOT-Gatter (Inverter)
- **Funktion:** Negation (Invertiert den Eingang)
- **Formel:**  
  \[
  Y = \overline{A}
  \]
- **Bedeutung:** Wenn \( A = 1 \), dann \( Y = 0 \), und umgekehrt.

| A | Y = NOT A |
|---|-----------|
| 0 | 1         |
| 1 | 0         |

---

### 2. AND-Gatter
- **Funktion:** Logisches UND
- **Formel:**  
  \[
  Y = A * B
  \]
- **Bedeutung:** \( Y = 1 \) nur wenn \( A = 1 \) und \( B = 1 \).

| A | B | Y = A AND B |
|---|---|-------------|
| 0 | 0 | 0           |
| 0 | 1 | 0           |
| 1 | 0 | 0           |
| 1 | 1 | 1           |

---

### 3. OR-Gatter
- **Funktion:** Logisches ODER
- **Formel:**  
  \[
  Y = A + B
  \]
- **Bedeutung:** \( Y = 1 \) wenn mindestens einer der Eingänge 1 ist.

| A | B | Y = A OR B |
|---|---|------------|
| 0 | 0 | 0          |
| 0 | 1 | 1          |
| 1 | 0 | 1          |
| 1 | 1 | 1          |

---

### 4. NAND-Gatter
- **Funktion:** Negiertes AND (NICHT UND)
- **Formel:**  
  \[
  Y = \overline{A * B}
  \]
- **Bedeutung:** Invertiertes AND-Ergebnis.

| A | B | Y = NAND |
|---|---|----------|
| 0 | 0 | 1        |
| 0 | 1 | 1        |
| 1 | 0 | 1        |
| 1 | 1 | 0        |

---

### 5. NOR-Gatter
- **Funktion:** Negiertes OR (NICHT ODER)
- **Formel:**  
  \[
  Y = \overline{A + B}
  \]
- **Bedeutung:** Invertiertes OR-Ergebnis.

| A | B | Y = NOR |
|---|---|---------|
| 0 | 0 | 1       |
| 0 | 1 | 0       |
| 1 | 0 | 0       |
| 1 | 1 | 0       |

---

### 6. XOR-Gatter (Exklusives OR)
- **Funktion:** Exklusives ODER (Genau ein Eingang ist 1)
- **Formel:**  
  \[
  Y = A \oplus B = (A * \overline{B}) + (\overline{A} * B)
  \]
- **Bedeutung:** \( Y = 1 \) wenn genau einer der Eingänge 1 ist.

| A | B | Y = XOR |
|---|---|---------|
| 0 | 0 | 0       |
| 0 | 1 | 1       |
| 1 | 0 | 1       |
| 1 | 1 | 0       |

---

### 7. XNOR-Gatter (Exklusives NOR)
- **Funktion:** Negiertes XOR
- **Formel:**  
  \[
  Y = \overline{A \oplus B} = (A * B) + (\overline{A} * \overline{B})
  \]
- **Bedeutung:** \( Y = 1 \) wenn beide Eingänge gleich sind.

| A | B | Y = XNOR |
|---|---|----------|
| 0 | 0 | 1        |
| 0 | 1 | 0        |
| 1 | 0 | 0        |
| 1 | 1 | 1        |

---

## Wichtige Gesetze der Booleschen Algebra

1. **Kommutativgesetz:**  
   \[
   A + B = B + A,       A * B = B * A
   \]

2. **Assoziativgesetz:**  
   \[
   (A + B) + C = A + (B + C),       (A * B) * C = A * (B * C)
   \]

3. **Distributivgesetz:**  
   \[
   A * (B + C) = (A * B) + (A * C)
   \]
   \[
   A + (B * C) = (A + B) * (A + C)
   \]

4. **Identitätsgesetze:**  
   \[
   A + 0 = A,       A * 1 = A
   \]

5. **Null- und Eins-Gesetze:**  
   \[
   A + 1 = 1,       A * 0 = 0
   \]

6. **Idempotenzgesetze:**  
   \[
   A + A = A,       A * A = A
   \]

7. **Komplementgesetz:**  
   \[
   A + \overline{A} = 1,       A * \overline{A} = 0
   \]

8. **De Morgan'sche Gesetze:**  
   \[
   \overline{A * B} = \overline{A} + \overline{B}
   \]
   \[
   \overline{A + B} = \overline{A} * \overline{B}
   \]

---

## Zusammenfassung

- Logikgatter bilden die Grundbausteine digitaler Schaltungen.
- Boolesche Algebra ermöglicht die mathematische Darstellung und Vereinfachung dieser Schaltungen.
- Die wichtigsten Gesetze helfen, Schaltungen effizient zu gestalten und zu verstehen.

---

