# 🚀 Multimodal Story Generation  
### From Image Analysis → AI Generated Narratives

<p align="center">
  <img src="https://img.shields.io/badge/AI-Multimodal-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Model-BLIP%20%7C%20FLAN--T5-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-Academic-orange?style=for-the-badge" />
</p>

<p align="center">
  <b>Transform Images into Intelligent Stories using AI 🤖📖</b>
</p>

---

## 📌 Overview

This project introduces a **multimodal AI pipeline** that converts images into **human-like narrative stories**.

It combines:
- 🖼️ **Computer Vision (Image Captioning)**
- ✍️ **Natural Language Generation (Story Creation)**
- ⚡ **Efficient Fine-Tuning (LoRA)**

The system extracts meaning from images and generates **context-aware, stylistic narratives**.

---

## 🧠 What We Built

- 📷 Image → Caption using **BLIP Model**
- ✍️ Caption → Story using **FLAN-T5 / T5 Models**
- 🎯 Multiple storytelling styles:
  - Creative  
  - Emotional  
  - Factual  
  - Concise  
- ⚡ Fine-tuning using **LoRA (Parameter Efficient Training)**
- 📊 Evaluation using:
  - BLEU  
  - ROUGE-L  
  - BERTScore  
  - Perplexity  
  - Diversity  

---

## 🏗️ System Architecture

  <img src="https://github.com/muhammadSabeelAhmed/MultiModal-Story-Generation/blob/main/multi-modal-architecture.jpeg"/>


---

## ⚙️ Tech Stack

### 🧠 Models
- BLIP (Image Captioning)
- FLAN-T5 / T5 (Text Generation)

### 🔧 Frameworks
- PyTorch
- HuggingFace Transformers
- PEFT (LoRA)

### 📊 Evaluation Tools
- NLTK
- ROUGE
- BERTScore

---

## ▶️ How to Run the Project

### Clone Repository
```bash
git clone https://github.com/your-username/multimodal-story-generation.git
cd multimodal-story-generation
```

### Create Virtual Environment
```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```
### Install Dependencies
```bash
pip install -r requirements.txt
```

### Run the Project
```bash
python main.py

OR

jupyter notebook
```
### Provide Input

- Add image path
- Select storytelling style:
  - creative
  - emotional
  - factual
  - concise

### Output
- 📝 Image Caption
- 📖 AI Generated Story


🖼️ Example
Input → Caption → Story

Input Image:


## Generated Caption:

"Two men in a kitchen preparing food"

### Generated Story:

In a small, lively kitchen, two friends worked side by side, laughing as they experimented with flavors. What began as a simple meal turned into a moment of connection, creativity, and shared memories.

### 📊 Results & Insights
- ✅ FLAN-T5 delivers balanced creativity + coherence
- 🚀 LoRA improves performance with minimal compute
- ⚡ Smaller models are faster but less expressive
- 📈 Metrics confirm quality improvement after fine-tuning

### ⚠️ Limitations
- Limited dataset (subset of Flickr30k)
- Story quality depends on caption accuracy
- Computational constraints for large-scale models

### 🔮 Future Enhancements
- Multi-image storytelling
- Real-time story generation API
- Human evaluation metrics
- Integration with GPT / LLaMA
- UI/UX for interactive storytelling
  
### 📂 Project Structure
- ├── data/
- ├── models/
- ├── notebooks/
- ├── src/
- ├── main.py
- ├── requirements.txt
- └── README.md

### 🤝 Contribution
Contributions are welcome!

### Fork the repo
Create a new branch
Commit your changes
Submit a Pull Request

### ⭐ Support
If you like this project:

- 👉 Give it a star ⭐
- 👉 Share it with others

### 📜 License

```bash
This project is intended for academic and research purposes only.

<p align="center"> Made with ❤️ by Muhammad Sabeel Ahmed </p> ```

