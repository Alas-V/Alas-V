<!-- <div align="center">
  <img src=".jpg" width="180" height="180" style="border-radius:50%"/> -->
  <h1>Artem V.</h1>
  <h3>Computer Vision Engineer · Deep Learning Architect</h3>
  <p><em>Efficient computer vision on limited hardware - maximising performance under tight compute budgets.</em></p>
</div>

[![Hugging Face](https://img.shields.io/badge/🤗%20Models-ffd21e?style=flat-square&logo=huggingface)](https://huggingface.co/Alas-V)
[![Kaggle](https://img.shields.io/badge/Kaggle-alasvl-20BEFF?style=flat-square&logo=kaggle)](https://www.kaggle.com/alasvl)
[![GitHub followers](https://img.shields.io/github/followers/Alas-V?label=Follow&style=social)](https://github.com/Alas-V)

---

### 🧠 What I Do

I design and train neural networks for **computer vision**, with a focus on **semantic segmentation** and **multi‑label classification**.  
My strength is solving real‑world bottlenecks: fitting large models into limited GPU memory, cleaning noisy datasets, and pushing architectures to their practical limits.

- 🎓 Currently pursuing a degree in **Applied Mathematics and Artificial Intelligence**.
- 🔬 Currently exploring **domain‑adaptive segmentation** and efficient multi‑task learning.
- 📄 Scientific paper on domain‑specific segmentation challenges *(in preparation)*.
- 🧪 Ongoing R&D: squeezing state‑of‑the‑art quality out of consumer‑grade hardware.

---

### 📊 Featured Project

**ConvNeXt‑CLF‑75** - food ingredient classifier (75 classes) built on **ConvNeXt‑Tiny** with **CBAM attention** and **GeM pooling**.  
Trained on a heavily cleaned subset of MM‑Food‑100K (~88,600 images) for 75 classes with severe class imbalance (smallest classes contain only ~100 images). Despite this, the model achieves strong results.

| Metric | Value |
| :--- | :--- |
| Macro F1 | **0.6546** |
| mAP | **0.7142** |
| Input size | 640×640 |
| Training hardware | Single RTX 2060 (6 GB) |

The model is optimised to serve as a semantic guide for a downstream segmentation network.

[![GitHub](https://img.shields.io/badge/GitHub-Repo-black?style=flat-square&logo=github)](https://github.com/Alas-V/ConvNeXt-CLF-75)
[![Hugging Face](https://img.shields.io/badge/🤗%20Model-ffd21e?style=flat-square)](https://huggingface.co/Alas-V/convnext-clf-75)

But can be used completely independently as a food classifier

[![HF Space](https://img.shields.io/badge/HF%20Space-🚀%20Try%20for%20free-FFB800?style=for-the-badge&logo=huggingface)](https://huggingface.co/spaces/Alas-V/ConvNeXt-Food-CLF-75)


---

### 🚧 Work in Progress

**Custom segmentation model (100+ classes, single RTX 2060 6 GB)**  
Designing a memory‑efficient architecture from scratch, integrating deformable convolutions, advanced attention blocks, and deep supervision - all while keeping peak VRAM below 5.5 GB. Early results are promising; full open‑source release is planned *(repo coming soon)*.

---

### ⚙️ How I Work

**Computer Vision Core**  
`PyTorch` `timm` `Albumentations` `OpenCV` `HuggingFace` - used daily for model prototyping and training.

**Architectural Design**  
Custom architectures based on `CNNs`, `U‑Net`, `ConvNeXt`, `ResNet`, `deformable convolutions`, `ASPP`, `deep supervision`, and more.

**Memory & Performance Optimisation**  
Reduced peak GPU memory by over **40 %** on a 104‑class segmentation model through `gradient checkpointing`, `mixed precision`, and custom memory‑efficient attention blocks. Used `PyTorch` profiling and `torch.compile`.

**Data Preparation**  
Cleaned and consolidated ~4,000 raw fine‑grained labels into **75 balanced classes** with manual merging and automated filtering. [Full step‑by‑step documentation](https://github.com/Alas-V/ConvNeXt-CLF-75/tree/main/dataset_preparation).

**Deployment & MLOps**  
`FastAPI` `Docker` `Redis` `PostgreSQL` `Git` - building lightweight inference APIs and reproducible pipelines.

---

### 🤝 Open to Opportunities

I’m actively looking for a **full‑time Computer Vision / Deep Learning position**.

- 🌍 **Remote or relocation** (ready to relocate worldwide, visa sponsorship required).
- 🕒 Currently in the **GMT+3** timezone.
- 🇬🇧 English **C1**.
- 💬 Always open to discussions about exciting projects - fastest way to reach me is via Telegram.

[![Email](https://img.shields.io/badge/Email-Contact%20me-red?style=flat-square&logo=gmail)](mailto:ntibestt@gmail.com)
[![Telegram](https://img.shields.io/badge/Telegram-@sentrybuster-2CA5E0?style=flat-square&logo=telegram)](https://t.me/sentrybuster)

---

<div align="center">
  <sub>“An expert is a person who has made all the mistakes that can be made in a very narrow field.” – Niels Bohr</sub>
</div>
