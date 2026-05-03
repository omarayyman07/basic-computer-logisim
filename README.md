<img width="790" height="900" alt="image" src="https://github.com/user-attachments/assets/d70c9dae-60eb-4328-ac04-1f3f021c6b33" /># 💻 Basic Computer Design (Logisim)

A simulation of a basic computer system implemented using Logisim, including memory, registers, ALU, and a shared bus architecture.

---

## 🚀 Features

- 256 × 16-bit RAM
- Common bus system (S2, S1, S0)
- Registers: DR, AC, AR, PC, IR, TR
- Arithmetic Logic Unit (ALU)
- RTL-based execution

---

## ⚙️ ALU Operations

| C2 C1 C0 | Operation |
|--------|----------|
| 001 | Transfer A |
| 010 | Add A + B |
| 011 | Subtract A - B |
| 100 | Multiply |
| 101 | Divide |
| 110 | Complement |
| 111 | XOR |

---

## 🔌 Bus Selection

| S2 S1 S0 | Source |
|---------|--------|
| 001 | Memory |
| 010 | AR |
| 011 | PC |
| 100 | DR |
| 101 | AC |
| 110 | IR |
| 111 | TR |

---

## 🧪 Test Case

Memory initialized as:

| Address | Value |
|--------|------|
| 0 | 10 |
| 1 | -5 |
| 2 | 0 |
| 3 | 2 |
| 4 | 0 |

Final result:

M[4] = -5

## 📊 Screenshots

<img width="790" height="900" alt="Shared Bus" src="https://github.com/user-attachments/assets/b447597b-33cd-488c-974c-4afa04105531" />



## 🛠️ Tool

- Logisim



## 👨‍💻 Author

Omar Ayman Elkhodary
