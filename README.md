# 🧠 Advancing Talking Head Generation: A Comprehensive Survey of Multi-Modal Methodologies, Datasets, Evaluation Metrics, and Loss Functions

> _"Ever wished your photo could argue back in meetings? We’re not there yet... but this is dangerously close."_  
> — The Authors (probably)

---

## 📘 About This Repository

Welcome to the **most expressive survey** on Talking Head Generation (THG) you'll ever read — or watch (spoiler: we include video results).

This repo accompanies the paper **“Advancing Talking Head Generation: A Comprehensive Survey of Multi-Modal Methodologies, Datasets, Evaluation Metrics, and Loss Functions”**, authored by [Vineet Kumar Rakesh](mailto:vineet@vecc.gov.in), [Soumya Mazumdar](mailto:reachme@soumyamazumdar.com), [Research Pratim Maity](mailto:researchpratimmaity2004@gmail.com), [Sarbajit Pal](mailto:sarbajit@vecc.gov.in), [Amitabha Das](mailto:amitabhad.snsa@jadavpuruniversity.in), [Tapas Samanta](mailto:tsamanta@vecc.gov.in). 

This work was supported by the Variable Energy Cyclotron Centre (VECC), Department of Atomic Energy, Government of India and Homi Bhabha National Institute, Department of Atomic Energy, Government of India, which provided comprehensive facilities and technical support for the research and the Department of Atomic Energy, Government of India, for sponsoring the open‑access publication of this work.

We explore 500+ research works from 2017 to 2025, dissect architectures like a neural coroner, evaluate datasets until they confess their secrets, and even benchmark some THG models for fun (and science).

---

## 🧪 What’s Inside

- 📚 **Survey** of over 500 papers
- 🗂️ **Categorization**: Audio, Video, Image, Text, 2D, 3D, GAN, NeRF, Transformers, etc.
- 📦 **Datasets**: VoxCeleb, GRID, LRS3, CelebV, and more
- 🧮 **Evaluation Metrics**: SSIM, PSNR, LMD, CPBD, WER, LPIPS, CSIM
- 🎯 **Loss Functions**: From pixel-wise pain to perceptual power
- 🤖 **Code**: Evaluation & visual quality assessment scripts
- 🎬 **Demo Videos**: See Wav2Lip and SadTalker in action (scroll 👇)
- ⚠️ **Warnings**: DeepFakes are not your friends

---

## 🎞️ Sample Outputs

| Model | Output |
|-------|--------|
| **Wav2Lip** | 🎥 [Watch](./GT_Wav2Lip.mp4) |
| **Output (Wav2Lip)** | 🎥 [Watch](./Wav2Lip.mp4) |
| **SadTalker** | 🎥 [Watch](./GT_SadTalker.mp4) |
| **Output (SadTalker)** | 🎥 [Watch](./SadTalker.mp4) |

---

## ⚙️ Code

Coming soon in the `eval-scripts/` directory:

- `compute_metrics.py`: SSIM, PSNR, LMD, CPBD & many more evaluations
- `align_faces.py`: Align input/output for fair comparison
- `visualize_lipsync.py`: Compare generated vs ground-truth sync

Stay tuned, or just `git pull --force` every hour (not recommended).

---

## 📈 Benchmarks Snapshot (Sample)

| Model         | Dataset     | SSIM ↑ | PSNR ↑ | LMD ↓ |
|---------------|-------------|--------|--------|--------|
| Wav2Lip       | VoxCeleb2   | 0.74   | 32.5   | 1.21   |
| FOMM          | VoxCeleb1   | 0.68   | 29.8   | 1.49   |
| Face-vid2vid  | GRID        | 0.72   | 31.2   | 1.33   |

*↑: Higher is better | ↓: Lower is better — just like your blood pressure after debugging Wav2Lip*

---

## 🧠 Core Contributions (TL;DR for humans with deadlines)

1. **Unified taxonomy** for all talking-head paradigms.
2. **Cross-paradigm benchmarks** using public models.
3. **Dataset decoding**: what's worth your GPU time.
4. **Metric mayhem**: which one really captures realism?
5. **Loss function symphony**: the good, the bad, the not-so-differentiable.

---

## 🔖 Citation

```bibtex
@misc{rakesh2025talkingheadreview,
  title={Advancing Talking Head Generation: A Comprehensive Survey of Multi-Modal Methodologies, Datasets, Evaluation Metrics, and Loss Functions},
  author={Vineet Kumar Rakesh and Soumya Mazumdar and Research Pratim Maity and Sarbajit Pal and Amitabha Das and Tapas Samanta},
  year={2025},
  note={Bolbona}
}
