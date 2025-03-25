# 🧠🎨 Controllable Image Generation using with Stable Diffusion and T2I-Adapter

Welcome to the **Controllable Image Generation** project! This repository explores how to guide image synthesis using **T2I-Adapter** models with different types of conditioning inputs like **edge maps**, **line poses**, and **depth maps**. Perfect for researchers, creatives, and AI enthusiasts who want **precise control** over generative models. ✨

---

## 📁 Notebooks Overview

| Notebook | Input Modality | Description |
|---------|----------------|-------------|
| [`T2IAdapter_EdgeMask.ipynb`](./T2IAdapter_EdgeMask.ipynb) | 🖍️ **Edge Mask** | Generate images guided by structural outlines (edges). Helps retain object shape and boundary. |
| [`T2IAdapter_LinePose.ipynb`](./T2IAdapter_LinePose.ipynb) | 🕴️ **Line Pose** | Condition on pose information to generate people or objects in specific configurations. |
| [`T2IAdapter_depth.ipynb`](./T2IAdapter_depth.ipynb) | 🌄 **Depth Map** | Leverage spatial depth information to generate 3D-aware scenes. |

---

## 🚀 Getting Started

Follow these steps to run the notebooks:

### 1. 📥 Clone the repository
```bash
git clone https://github.com/meghakalia/Controllable_Image_Generation.git
cd Controllable_Image_Generation
```
### 2. 📓 Launch Jupyter Notebook
```bash
jupyter notebook
```
### 3. ▶️ Run Any Notebook
Choose a notebook based on your use case and run the cells to generate amazing images!

## 📚 References

[T2I-Adapter Paper (arXiv)](https://arxiv.org/abs/2302.08453) 📄
[Original GitHub Repository (TencentARC)](https://github.com/TencentARC/T2I-Adapter) 💻


## 🤝 Contributing
Feel free to open issues or submit pull requests to improve the project. Feedback is always welcome!
