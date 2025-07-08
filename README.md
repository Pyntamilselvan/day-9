# ➖ Day 9 – Subtractors

## 🧠 Concepts:
- Half Subtractor: Subtracts two bits A - B.
- Full Subtractor: Subtracts three bits A - B - Bin.

## ✅ Truth Tables

### Half Subtractor

| A | B | D (Diff) | B_out (Borrow) |
|---|---|----------|----------------|
| 0 | 0 |    0     |      0         |
| 0 | 1 |    1     |      1         |
| 1 | 0 |    1     |      0         |
| 1 | 1 |    0     |      0         |

- Diff = A ⊕ B
- B_out = A' · B

### Full Subtractor

| A | B | Bin | D | Bout |
|---|---|-----|---|------|
| 0 | 0 |  0  | 0 | 0    |
| 0 | 0 |  1  | 1 | 1    |
| 0 | 1 |  0  | 1 | 1    |
| 0 | 1 |  1  | 0 | 1    |
| 1 | 0 |  0  | 1 | 0    |
| 1 | 0 |  1  | 0 | 0    |
| 1 | 1 |  0  | 0 | 0    |
| 1 | 1 |  1  | 1 | 1    |

- D = A ⊕ B ⊕ Bin
- Bout = A'·B + (A⊕B)'·Bin

## 🧩 Diagram: Not included. Described in theory.
# day-9
