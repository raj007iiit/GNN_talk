
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

🎯 **`https://neurograph-fmri-gnn-explorer-695890547372.us-west1.run.app/`**

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

- Mathematicians curious about ML on graphs
- Graph theorists exploring modern learning paradigms
- Researchers working on brain and biological networks
- Faculty teaching AI to interdisciplinary audiences
- Students seeking intuition before equations

No prior deep learning expertise is required.

---

## 🛠️ How to use this repository

1. **Start with the slides** to build intuition  
2. **Run Notebook A** to understand how graphs enter neural networks  
3. **Proceed to Notebook B** to see learning in action  
4. **Explore Notebook C** to understand explainability  
5. **Use the demo app** for visualization and engagement  

---

## 📚 Suggested Background Reading

- Kipf & Welling, *Semi-Supervised Classification with Graph Convolutional Networks*
- Gilmer et al., *Neural Message Passing for Quantum Chemistry*
- Ying et al., *GNNExplainer: Generating Explanations for Graph Neural Networks*
- Battaglia et al., *Relational Inductive Biases, Deep Learning, and Graph Networks*

---

## 👤 Author

**Ebin Deni Raj**  
FACTS-H Lab  
Indian Institute of Information Technology Kottayam  

Focus areas:
- Responsible & Explainable AI
- Graph-based learning
- Interdisciplinary AI education
- Trustworthy machine learning systems

---

## ⭐ Final Note

If this repository helps you:
- understand GNNs better,
- explain them more clearly,
- or trust them a little more,

then it has served its purpose.

Feel free to fork, reuse, and adapt for teaching and research.
