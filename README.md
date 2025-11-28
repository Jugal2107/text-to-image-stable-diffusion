# Text to Image Generator using Stable Diffusion

This project implements a **Text-to-Image Generator** using the **Stable Diffusion v1-4** model from the `diffusers` library.  
It converts natural language prompts into high-quality images using state-of-the-art latent diffusion models.

This project demonstrates my understanding of **generative AI**, **latent diffusion**, and **prompt-based image synthesis**.  
Developed as part of my academic and research-focused learning.

---

## 🚀 Features

- Generate images from text prompts  
- Uses **Stable Diffusion v1-4 (CompVis)**  
- GPU-accelerated inference with **CUDA**  
- Save generated images as PNG  
- Simple and clean inference pipeline  

---

## 🧠 Model Used

The project uses:


Loaded using:

from diffusers import DiffusionPipeline
pipe = DiffusionPipeline.from_pretrained("CompVis/stable-diffusion-v1-4")
pipe.to("cuda")


📥 Example Prompts Used

"A Japanese anime eye catchy girl"

📂 Repository Structure

text-to-image-stable-diffusion/
│── text_to_image.ipynb             
│── README.md                       
│── requirements.txt                
└── results/                        

▶️ How to Run
🔹 Run on Google Colab

- Upload the notebook

- Run all cells from top to bottom

- Ensure GPU runtime is enabled (Runtime → Change runtime → GPU)

🔹 Run Locally (Requires GPU)

1. Clone the repository:
git clone https://github.com/Jugal2107/text-to-image-stable-diffusion.git
cd text-to-image-stable-diffusion

2. Install dependencies:
pip install -r requirements.txt

3. Run the notebook:
Open text_to_image.ipynb using Jupyter or VS Code and execute all cells.

📦 Requirements

diffusers
accelerate
torch
transformers
safetensors


🔮 Future Improvements

- Add Streamlit/Gradio UI for prompt → image

- Fine-tune Stable Diffusion for custom datasets

- Add negative prompts & CFG scale control

- Add batch prompt generation

- Integrate support for SD v1.5 or SDXL

📚 Research Relevance

This project highlights my skills in:

- Generative AI & Diffusion Models

- NLP + Vision multimodal systems

- GPU-based model inference

- Practical ML experimentation

This repository demonstrates my interest in AI research and creativity-focused machine learning applications.





