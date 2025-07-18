# lingua-franca
# 🌐 Lingua Franca Project – Codecademy

The **Lingua Franca (LF)** project is a hands-on educational experience offered by Codecademy that introduces learners to LF — a **coordination language** designed for building **deterministic, concurrent, real-time, and distributed** systems.

Lingua Franca supports multiple **target languages** (C, C++, Python, TypeScript, Rust) and allows programmers to define modular, reactive components that communicate through events, actions, and timers.

---

## 🧠 Core Concepts

### 🧱 Reactors
- The primary building blocks in LF.
- Contain **input/output ports**, **actions**, **timers**, and **reactions**.

### ⚡ Reactions
- Code snippets written in a target language.
- Executed in response to **trigger events** such as:
  - Input from ports
  - Timers
  - Actions

### 🧩 Composition
- Reactors can be **nested hierarchically**, enabling modular and scalable system design.

### ⏳ Events & Flow of Time
- All events are **timestamped**.
- LF guarantees **strictly increasing timestamps** for all reaction executions, ensuring **temporal correctness**.

### 🧵 Concurrency & Determinism
- Reactions that are **independent** can run **in parallel**.
- All reactions within a single reactor are **mutually exclusive (atomic)**.
- **Determinism** is the default; non-determinism must be explicitly introduced by the developer.

---

## 🎯 Project Goals

- ✅ **Learn the reactor-oriented programming paradigm**  
  Understand how applications are structured using reactors.

- ✅ **Master LF syntax and semantics**  
  Write LF code that defines system behavior precisely and concisely.

- ✅ **Develop concurrent and distributed applications**  
  Build applications that scale across **cores** or **machines**.

- ✅ **Build real-time systems**  
  Ensure predictable and temporally correct execution for embedded or critical applications.

- ✅ **Explore code generation**  
  Learn how LF translates your program into executable code in **C, C++, Python, Rust, or TypeScript**.

---

## 🛠️ Technologies

- **Lingua Franca CLI**
- **Target languages:** C, C++, Python, Rust, TypeScript
- **Code Generation System**
- **Simulator (for testing event flow and timing)**

---

## 📦 Example Project Structure

```bash
lingua-franca-project/
├── src/
│   └── main.lf           # Main LF file defining reactors and reactions
├── dist/
│   └── generated/        # Auto-generated code based on selected target
├── Makefile              # Used to build the project
└── README.md             # Project documentation
🧪 Learning Outcomes
By completing this project, you will be able to:

Write real-time, deterministic programs using the LF syntax.

Compose complex systems using reactor hierarchies.

Understand the semantics of event tagging, logical time, and reaction scheduling.

Leverage parallelism and mutual exclusion safely.

Generate and run LF applications across multiple target languages.

🔮 Future Exploration
Integrate with hardware platforms (e.g., Raspberry Pi, Arduino).

Extend to multi-machine systems using LF’s federated mode.

Profile real-time performance and latency using LF’s tracing tools.