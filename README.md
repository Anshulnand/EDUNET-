Image Generation using Stable Diffusion & ComfyUI

Overview

This project demonstrates image generation using Stable Diffusion with ComfyUI. Three different prompts were used to generate unique images.

Setup Instructions

Install ComfyUI and ensure dependencies are met.

Download and place Stable Diffusion model checkpoints (.safetensors) in the checkpoints folder.

Run ComfyUI and load the provided workflow.

Generated Images & Prompts

Futuristic Cityscape

Prompt: "A futuristic city skyline at sunset, with flying cars and glowing neon signs reflecting off glass skyscrapers."

Model Used: @runwayml/stable-diffusion-v1-5

Antique Library

Prompt: "An antique library with towering shelves filled with leather-bound books. An ancient chandelier hangs from the ceiling."

Model Used: dreamshaper_8.safetensors

Forest Stream

Prompt: "A tranquil forest stream with sunlight filtering through tall trees, a wooden foot bridge in the front, and a calm stream running through the middle."

Model Used: dreamshaper_8.safetensors

How to Customize

Modify prompts in CLIP Text Encode (Prompt) nodes.

Adjust sampling steps and seed values in the KSampler node.

Save generated images from the Save Image node.

Repository Structure

📂 Image-Generation
│── 📁 Snapshots   # Snapshots
│── 📁 Images     # Generated images
│── README.md     # Project details

Acknowledgments

Stable Diffusion by CompVis

ComfyUI for workflow-based image generation
