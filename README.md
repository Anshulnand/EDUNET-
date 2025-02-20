# Image Generation using Stable Diffusion & ComfyUI

## 🚀 Overview
This project demonstrates image generation using **Stable Diffusion** with **ComfyUI**. Three different prompts were used to generate unique and visually appealing images.

---

## 🔧 Setup Instructions
1. **Install ComfyUI** and ensure all dependencies are met.
2. **Download Stable Diffusion model checkpoints (.safetensors)** and place them in the `checkpoints` folder.
3. **Run ComfyUI** and load the provided workflow to start generating images.

---

## 🖼️ Generated Images & Prompts

### 🌆 Futuristic Cityscape
- **Prompt:** _"A futuristic city skyline at sunset, with flying cars and glowing neon signs reflecting off glass skyscrapers."_
- **Model Used:** `@runwayml/stable-diffusion-v1-5`

### 📚 Antique Library
- **Prompt:** _"An antique library with towering shelves filled with leather-bound books. An ancient chandelier hangs from the ceiling."_
- **Model Used:** `dreamshaper_8.safetensors`

### 🌿 Forest Stream
- **Prompt:** _"A tranquil forest stream with sunlight filtering through tall trees, a wooden footbridge in the front, and a calm stream running through the middle."_
- **Model Used:** `dreamshaper_8.safetensors`

---

## 🎨 How to Customize
- **Modify prompts** in the `CLIP Text Encode (Prompt)` nodes.
- **Adjust sampling steps & seed values** in the `KSampler` node.
- **Save generated images** from the `Save Image` node.

---

## 📁 Repository Structure
```
📂 Image-Generation
│── 📁 Snapshots   # Workflow snapshots
│── 📁 Images      # Generated images
│── README.md      # Project details
```

---

## 🙌 Acknowledgments
- **[Stable Diffusion](https://github.com/CompVis/stable-diffusion)** by CompVis.
- **[ComfyUI](https://github.com/comfyanonymous/ComfyUI)** for workflow-based image generation.

---

🔥 Happy Generating! 🚀

