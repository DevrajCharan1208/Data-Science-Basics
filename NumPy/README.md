# NumPy Learning Roadmap 🧮

This directory contains a structured learning path for **NumPy**, moving from basic array creation to advanced statistical operations.

## 📜 Phase Breakdown

I have divided the learning process into 5 distinct phases:

| File | Key Concepts Covered |
| :--- | :--- |
| **Phase 1** | `Array & Basis` - Introduction to `ndarray`, checking dimensions (`ndim`, `shape`), and data types. |
| **Phase 2** | `Array Operations` - Arithmetic operations, slicing, indexing, and iteration. |
| **Phase 3** | `Advance Operations` - The concept of **Broadcasting**, reshaping arrays, and boolean masking. |
| **Phase 4** | `Image Color Reverse` - A practical application treating images as 3D arrays to manipulate RGB channels. |
| **Phase 5** | `Statistics & Matrix Vectors` - Dot products, matrix multiplication, standard deviation, and variance. |

## 💡 Key Takeaways
* **Vectorization:** Replaced slow Python loops with optimized NumPy C-bindings.
* **Broadcasting:** Learned how NumPy handles operations between arrays of different shapes.
* **Image Processing:** Understood how digital images are represented as numerical matrices.

## 📁 File Notes
* `numpy logo.npy`: This is a binary file storing array data used for the visualization exercises in **Phase 4**. Please keep it in the same directory as the notebooks.

## 🚀 How to Run
Ensure you have Jupyter installed:
```bash
pip install jupyter numpy
jupyter notebook
