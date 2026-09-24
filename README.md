# AI/ML Foundations — Intro to Data Science (Colab Walkthroughs)

Prerequisite refresher for the course. Each notebook below is **cloned, executed with all outputs saved, archived here**, and paired with **one YouTube video** that walks through it code-block by code-block — explaining the *theory* behind the block, the *key* lines (UX/plotting boilerplate skipped), and the *output*.

**Goal:** a solid, first-principles grip on the basics of AI/ML — Python & the data stack, tensors/arrays, linear algebra, and calculus.

---

## How to use this repo
1. Open a topic below.
2. Read the archived notebook (it already contains the executed outputs).
3. Watch the linked video for the block-by-block explanation.

**Legend:** 🔗 original source · 📓 archived notebook (with outputs) · ▶️ video · 🎥 recorded (paste link)

---

## Contents

| # | Topic | Notebook | Video |
|---|-------|----------|-------|
| 1 | Introduction to Python | `https://github.com/Anshi-12/ai-ml-foundations/blob/main/notebooks/final_Intro_to_Python_for_Machine_Learning.ipynb` | 🎥 _paste link_ |
| 2 | Introduction to NumPy | `notebooks/02_intro_numpy.ipynb` | 🎥 _paste link_ |
| 3 | Introduction to pandas | `notebooks/03_intro_pandas.ipynb` | 🎥 _paste link_ |
| 4 | Introduction to Matplotlib | `notebooks/04_intro_matplotlib.ipynb` | 🎥 _paste link_ |
| 5 | Basic Linear Algebra | `notebooks/05_linear_algebra_basic.ipynb` | 🎥 _paste link_ |
| 6 | Calculus I | `notebooks/13_calculus_1.ipynb` | 🎥 _paste link_ |

---

## 1 · Foundations

### 1.1 Introduction to Python
🔗 https://colab.research.google.com/drive/17E_cjURtuCBcPte6qUrMlCCdHRJ0QUB4
📓 `notebooks/01_intro_python.ipynb` · ▶️ **Video:** 🎥 recorded — _paste link_
**Key ideas to explain:** variables & types, lists/dicts/tuples, control flow, functions, comprehensions — the Python you need before touching the data stack.

### 1.2 Introduction to NumPy
🔗 https://colab.research.google.com/drive/1DM_MCjCC6IzY2WK0vHlk90Ri7OAsT6df
📓 `notebooks/02_intro_numpy.ipynb` · ▶️ **Video:** 🎥 recorded — _paste link_
**Key ideas to explain:** the ndarray as a **tensor**, shape/dtype, indexing & slicing, vectorization vs. loops, broadcasting, axis-wise reductions. This is where "tensor" becomes concrete.

### 1.3 Introduction to pandas
🔗 https://colab.research.google.com/drive/1atdrsQqKndPn3puN0K5241iMkpC57FNq
📓 `notebooks/03_intro_pandas.ipynb` · ▶️ **Video:** 🎥 recorded — _paste link_
**Key ideas to explain:** Series vs. DataFrame, selection (`loc`/`iloc`), filtering, `groupby`/aggregation, handling missing data — the shape data is really in before modelling.

### 1.4 Introduction to Matplotlib
🔗 https://colab.research.google.com/drive/18kGkqhPMpsrEVCdS7gKxwEZskJRnV1EP
📓 `notebooks/04_intro_matplotlib.ipynb` · ▶️ **Video:** 🎥 recorded — _paste link_
**Key ideas to explain:** figure/axes model, line vs. scatter vs. histogram, and *reading* a plot (distribution, correlation, outliers). Skip styling boilerplate; focus on what each plot tells you.

---

## 2 · Linear Algebra

### 2.1 Basic Linear Algebra
🔗 https://colab.research.google.com/drive/1tbGIBiTCEmdcrU7ZnrSsiZlQ0qZ17C1G
📓 `notebooks/05_linear_algebra_basic.ipynb` · ▶️ **Video:** 🎥 recorded — _paste link_
**What it covers:** one dataset (200 flowers, 2 features) carried from "what is a vector" to a hand-built PCA. Vectors (arrow/list/point), add/scale/length/unit vectors, the **dot product** (algebraic = geometric, sign = agreement, projection, cosine similarity), matrices as data and as **transformations** (columns = where the basis lands, determinant = area scale), **matrix multiplication** built from the dot product (and `y = Wx + b` as a neural-network layer), systems/inverses/rank/least-squares, **eigenvectors** (directions that don't turn), and **PCA** on the covariance matrix. Recurring practical thread: `(2,)` vs `(2,1)` shapes and broadcasting traps, and `*` (elementwise) vs `@` (matrix/dot).

---

## 3 · Calculus

### 3.1 Calculus I
🔗 https://colab.research.google.com/drive/1euBXLqidelKsk8FhBZF726JELTmEGNxG
📓 `notebooks/13_calculus_1.ipynb` · ▶️ **Video:** 🎥 recorded — _paste link_

---

## Recording brief (applies to every video)
- One video per colab; go **code block by code block**.
- For each block: state the **concept/theory** first, then the **important lines** (skip UX/plotting boilerplate), then read the **output** and say what it means.
- Keep it tight and authentic — teach it, don't narrate line-by-line.
- Unlisted YouTube upload is enough to share by link; paste the link into the table and the section above.

## Repo structure
```
.
├── README.md
└── notebooks/
    ├── 01_intro_python.ipynb
    ├── 02_intro_numpy.ipynb
    ├── 03_intro_pandas.ipynb
    ├── 04_intro_matplotlib.ipynb
    ├── 05_linear_algebra_basic.ipynb
    └── 13_calculus_1.ipynb
```
