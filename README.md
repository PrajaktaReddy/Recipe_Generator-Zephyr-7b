# AI Recipe Generator

An AI-powered web app that generates accurate, structured recipes based on user-provided ingredients using the **Zephyr-7B** language model.

---

## Features

-  **LLM-powered generation** using HuggingFace's `zephyr-7b-beta`
-  Generates recipes with **title, ingredients, and steps**
-  Clean, interactive **Gradio web interface**
-  Accurate and realistic recipes, ideal for daily cooking
-  Future-ready: Extend with OCR, PDF export, or pantry database

---

## Demo
<img width="900" height="815" alt="Screenshot 2025-08-01 172317" src="https://github.com/user-attachments/assets/dcf681a6-3ad0-4e1c-bd73-0b7a7551249d" />



---

##  How It Works

1. **User inputs** ingredients (e.g. `chicken, garlic, potatoes`)
2. Model receives a structured **prompt** to behave like a chef assistant
3. Output is returned in recipe format:
   - Title
   - Ingredients list
   - Step-by-step instructions

---

## Tech Stack

| Component      | Tech Used                         |
|----------------|-----------------------------------|
| Language Model | [`zephyr-7b-beta`](https://huggingface.co/HuggingFaceH4/zephyr-7b-beta) (Instruction-tuned) |
| Backend        | `Transformers`, `Accelerate`, `BitsandBytes` |
| Frontend UI    | `Gradio`                          |
| Deployment     | Google Colab (or Localhost)       |

---
