# 🧠 **Talking Heads, but Make It Science**  
### *A Funny Yet Serious Survey on Deepfake’s Nerdy Cousin: Talking Head Generation*

> _“Ever wished your selfie could talk during Zoom calls? We’re not quite there... but we’ve already made it nod in agreement and blink suspiciously."_  
> — @mazumdarsoumya

---

## 📘 What’s Going On Here?

Welcome to the wildest ride in neural rendering: **Talking Head Generation (THG)**. This repo is your **cheat code** to understanding a field that blends deep learning with deep confusion, peppered with a little madness and a lot of **metrics**.

⚠️ **DISCLAIMER:**  
The **preprint paper titled**  
📄 **“Advancing Talking Head Generation: A Comprehensive Survey of Multi-Modal Methodologies, Datasets, Evaluation Metrics, and Loss Functions”** is **NOT going to be published**. It’s the *mother of all drafts* — split into multiple, more detailed children destined for **Scopus-indexed journals and conferences**. [arXiv:2507.02900](https://doi.org/10.48550/arXiv.2507.02900)

---

## 📚 The Paper Children (Coming Soon™️, but Real)

These aren’t clones. They are deeper, sharper, peer-reviewed cousins of the main survey. Once they pass reviewer boss fights, we’ll drop the DOIs and links here:

### 🔍 1. **Advancing Talking Head Generation: A Systematic Review of Methodologies and Evaluation Metrics**  
🧪 *Journal Submission - The Visual Computer, Springer Nature*  
> Dive into the model jungle — from GANs to NeRFs and Transformers, all neatly dissected like a biology lab frog.

### 📃️ 2. **Comprehensive Dataset Analysis for Talking Head Generation**  
📘 *Book Chapter Submission*  
> What’s inside VoxCeleb? Why is GRID so... griddy? This one's for dataset diggers.

### 📏 3. **Quantitative Assessment in Talking Head Generation: Metrics and Loss Functions**  
📗 *Journal Submission*  
> If you've ever said "SSIM is enough," this chapter is about to throw shade and math at you.

### 🧪 4. **Experimental Validation of Modern Talking Head Generation Architectures**  
🛠️ *Conference Paper Submission*  
> Benchmarks, metrics, results, regrets — actual experimental results with charts and enough tables to furnish an IKEA showroom.

🔬 **Links will appear here** like magic scrolls, post-acceptance. Until then... stay tuned.

---

## 🧪 What's in This Repo?

A **research buffet** for your GPU and gray matter:

- 🧠 *500+ Research Papers* distilled into human language  
- 🧑‍🏫 *Categorization* across modalities: Audio, Video, Image, Text, 2D/3D, GAN, NeRF, Transformer-based, and more  
- 🎞️ *Datasets Decoded*: VoxCeleb, GRID, LRS3, CelebV, and other acronyms we pretend to remember  
- 🔬 *Evaluation Metrics Galore*: SSIM, PSNR, CPBD, LPIPS, LMD, WER, CSIM — enough for a PhD defense  
- 💥 *Loss Functions Explained*: From Mean Squared Error to “Oh no, my perceptual loss exploded”  
- 🧪 *Code + Sample Outputs* — because seeing is believing, and benchmarks don’t screenshot themselves

---

## 🎮 Sample Outputs

| Model | Output |
|-------|--------|
| **Wav2Lip** | 🎥 [Watch](./GT_Wav2Lip.mp4) |
| **Wav2Lip (Generated)** | 🎥 [Watch](./Wav2Lip.mp4) |
| **SadTalker** | 🎥 [Watch](./GT_SadTalker.mp4) |
| **SadTalker (Generated)** | 🎥 [Watch](./SadTalker.mp4) |

Not DeepFakes. Just DeepWork.

---

## ⚙️ Code Zone

Coming soon in `eval-scripts/`:

- `compute_metrics.py` – For SSIM, PSNR, CPBD, LMD, and that one metric your professor insists on using  
- `align_faces.py` – Because misaligned faces are worse than misaligned deadlines  
- `visualize_lipsync.py` – For pixel-by-pixel judgement of your model's karaoke skills

Wanna try it? Just:

```bash
git clone --depth 1 --force https://github.com/VineetKumarRakesh.git
```

(Replace `VineetKumarRakesh` when you’re not lazy.)

---

## 📊 Benchmarks Snapshot

| Model         | Dataset     | SSIM ↑ | PSNR ↑ | LMD ↓ |
|---------------|-------------|--------|--------|--------|
| Wav2Lip       | VoxCeleb2   | 0.74   | 32.5   | 1.21   |
| FOMM          | VoxCeleb1   | 0.68   | 29.8   | 1.49   |
| Face-vid2vid  | GRID        | 0.72   | 31.2   | 1.33   |

> *↑ Good. ↓ Also good. ∞? You messed up somewhere.*

---

## 🧠 Core Contributions (aka "Too Long, Just Tell Me Why It Matters")

- 📀 Unified taxonomy for THG — no more buzzword soup  
- 🔬 Benchmarked open-source models — because someone had to do the hard part  
- 📦 Dataset comparison — what’s hot, what’s not  
- 📏 Metrics mayhem — why SSIM isn’t always your friend  
- 🎼 Loss functions and why they love making your training unstable

---

## 🔖 Citation (For When It’s Published. Soon.)

```bibtex
@misc{rakesh2025talkingheadreview,
  title={Advancing Talking Head Generation: A Comprehensive Survey of Multi-Modal Methodologies, Datasets, Evaluation Metrics, and Loss Functions},
  author={Vineet Kumar Rakesh and Soumya Mazumdar and Research Pratim Maity and Sarbajit Pal and Amitabha Das and Tapas Samanta},
  year={2025},
  note={Preprint – Will not be published. Child papers incoming.}
}
```

---

## 📣 Final Words

If you're into:
- Machines that talk with your face
- Academic deep dives that make your brain sweat
- And humor that makes research tolerable

You're in the right repo.

**Stars appreciated. Forks encouraged. Pull requests cautiously welcomed.**  
🥸 _Your talking head just said thanks._

