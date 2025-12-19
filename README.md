
---

## 🎓 Slides (`/slides`)

📄 **Explainable_GNNs.pdf**

The slide deck covers:

- What graphs *really* mean in learning systems
- How GNNs are constructed from graphs (step-by-step)
- Message passing explained using intuition and analogies
- Why classical graph theory is *not replaced* but *operationalized*
- Why explainability is essential for graph-based learning
- A structured taxonomy of **GNN explainers**
- Brain network examples and motivation from neuroscience

➡️ The slides are **intuition-first**, with minimal mathematics and heavy use of analogies, visuals, and conceptual grounding.

---

## 🧪 Colab Notebooks (`/notebooks`)

All notebooks are:
- ✅ **Google Colab–safe**
- ✅ **CPU-only**
- ✅ Tested with compatible package versions
- ✅ Beginner-friendly, with extensive comments

---

### 📘 Notebook A: GNN Basics  
**`Notebook_A_GNN_Basics.ipynb`**

What you’ll learn:
- How a graph is represented as tensors
- What node features, edge indices, and labels mean
- How message passing works computationally
- How graph structure becomes learnable information

Audience:
> Ideal for mathematicians and graph theorists seeing GNNs for the first time.

---

### 📗 Notebook B: Training a GNN  
**`Notebook_B_GNN_Training.ipynb`**

What you’ll learn:
- How a simple GCN is defined
- How node classification works
- What loss functions mean in graph settings
- Why training GNNs is different from CNNs / RNNs

Includes:
- Karate Club dataset
- Clear separation of **model**, **data**, and **training loop**

---

### 📙 Notebook C: Explainability for GNNs  
**`Notebook_C_GNN_Explainability.ipynb`**

This is the heart of the repository.

Covers:
- GNNExplainer (subgraph-based explanations)
- Feature attribution on graphs
- Node vs edge importance
- Visualization of explanations
- Why explanations are *local* and *model-specific*

Key takeaway:
> An explanation is not “why the graph is like this”,  
> but “why the **model** behaved this way on this graph”.

---

## 🖥️ Demo App (`/demo_app`)

🎯 **`gnn_explainer_app.py`**

A lightweight demo application that:

- Loads a trained GNN
- Runs inference on a graph
- Visualizes **important nodes and edges**
- Allows users to *see* explanations instead of just numbers

Designed for:
- Live demos
- Classroom use
- Workshops and interdisciplinary talks

---

## 🧠 Why Explainable GNNs?

In graph-based domains such as:
- Brain connectomes
- Social networks
- Biological interaction networks
- Infrastructure graphs

Predictions alone are **not sufficient**.

We must ask:
- Which nodes mattered?
- Which connections mattered?
- Is the explanation stable?
- Does it align with domain knowledge?

This repository treats explainability as a **scientific requirement**, not a cosmetic add-on.

---

## 🎯 Who is this for?

This material is especially suitable for:

- Mathematici
