
# 🎨 Interactive Graph Coloring & Edge Coloring Lab

An interactive, web-based educational platform designed for **B.Tech CSE – Discrete Mathematics & Graph Theory** to visualize, experiment with, and understand **Vertex Coloring** and **Edge Coloring**.

**Author:** Surajit Sahoo
🚀 **Live Demo:** [https://surajit-sahoo-iitian.github.io/graph-coloring-lab/](https://surajit-sahoo-iitian.github.io/graph-coloring-lab/)
---

## ✨ Features

### 1. Vertex Coloring

- 📖 **Mathematical Foundation:** Definitions, properties, and important theorems, including Brooks' Theorem.
- 📝 **Real-World Applications:**
  - **Examination Scheduling:** Interactive conflict graph demonstrating clique lower bounds and minimum time-slot allocation.
  - **Compiler Register Allocation:** Visualization of live-range interference using path and complete graphs.
- 🕹️ **Interactive Vertex Coloring Sandbox:**
  - Create custom graphs with up to **20 vertices**.
  - Add straight, curved, and self-loop edges.
  - Color vertices using an 8-color palette.
  - Detect adjacent vertex coloring conflicts in real time.
  - Calculate the chromatic number and maximum degree.
  - Built-in presets: Crown Graph, C5, C6, K5, Petersen Graph, Exam Conflict Graph, and more.
- 🎯 **Greedy Coloring Simulator:**
  - Compare Default Greedy Rule and Welsh–Powell Algorithm.
  - Step-by-step execution with synchronized graph coloring.
  - Highlighted pseudocode and execution trace logs.
  - Playback speed controls.

### 2. Edge Coloring

- 📖 **Mathematical Foundation:** Definitions, properties, and important theorems, including König's Line Coloring Theorem and Vizing's Theorem.
- 📝 **Real-World Applications:**
  - **Tournament Scheduling:** Interactive K4 match scheduler illustrating edge partitions into disjoint matchings.
  - **Network Channel Assignment:** Understanding edge coloring and line graph equivalence.
- 🔗 **Interactive Edge Coloring Sandbox:**
  - Paint edges using different colors.
  - Visualize the corresponding line graph L(G) simultaneously.
  - Display Vizing's bounds and overfull graph diagnostics.
  - Built-in presets: K4, K5, C5, C6, K1,3, Triangular Prism, and K3,3.
- ⚡ **Greedy Edge Coloring Simulator:**
  - Compare Default Greedy Rule and Welsh–Powell Edge Order.
  - Step-by-step coloring execution.
  - Dry-run trace logs and synchronized visualization.

### 3. Important Mathematical Results

**Vizing's Theorem:**

$$
\Delta(G) \leq \chi'(G) \leq \Delta(G)+1
$$

**Line Graph Equivalence:**

$$
\chi'(G) = \chi(L(G))
$$

---

## 🛠️ Tech Stack

- HTML5
- Tailwind CSS
- Vanilla JavaScript (ES6+)
- HTML5 Canvas
- KaTeX

---

## 📂 Repository Structure

```text
graph-coloring-lab/
├── index.html      # Main interactive web application
└── README.md       # Project documentation
```

---

## 🚀 Local Usage

No installation, package managers, or backend servers are required.

1. Clone or download the repository.
2. Open the project folder.
3. Run `index.html` in any modern web browser.

---

*An interactive learning resource for exploring the theory, algorithms, and applications of Graph Coloring.*
