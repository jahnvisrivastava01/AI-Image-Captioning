# 🖼️ AI Image Caption Generator

> Upload an image and let AI describe it automatically using a pretrained Hugging Face model.

---

## 🚀 What I Built

✨ My first Generative AI project focused on image captioning using Computer Vision, NLP, and a pretrained BLIP model from Hugging Face.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| 🐍 Python | Programming Language |
| 🤗 Transformers | AI Model Pipeline |
| BLIP | Image Captioning Model |
| Pillow (PIL) | Image Processing |
| Google Colab | Development Environment |

---

## 📚 What I Learned

✅ Installing AI libraries with pip

✅ Using Hugging Face Transformers

✅ Loading pretrained models

```python
pipeline(
    "image-text-to-text",
    model="Salesforce/blip-image-captioning-base"
)
```

---

### 🖼️ Image Upload

Learned how to upload files inside Google Colab.

```python
from google.colab import files

uploaded = files.upload()
```

---

### 🧠 Working with AI Models

Instead of training a model from scratch, I learned how to use a pretrained model to solve a real-world problem.

Input

```
Image
```

⬇️

AI Processing

⬇️

Output

```
"A picture of a dog playing in the park."
```

---

### 🖼️ Image Processing

Used Pillow to open uploaded images.

```python
from PIL import Image

image = Image.open(filename)
```

---

### 🤖 AI Caption Generation

Generated captions using the BLIP Image Captioning model.

```python
result = caption_helper(
    image,
    text="a picture of"
)
```

---

## 💡 Concepts Learned

- Computer Vision
- Image Captioning
- Hugging Face Pipelines
- Pretrained Models
- NLP + Vision
- PIL Image Handling
- Google Colab Workflow
- Python File Handling

---

## 📂 Project Workflow

```text
User Uploads Image
        │
        ▼
Google Colab
        │
        ▼
Pillow Opens Image
        │
        ▼
BLIPqwerty A AI Model
        │
        ▼
Generates Caption
        │
        ▼
Display Result
```

---

## 📸 Sample Output

```
Loading the AI...

AI is Ready!

Choose Files

Uploading image...

🤖 AI Caption:

"A picture of a smiling child riding a bicycle."
```

---

## ⭐ Skills Gained

- ✔ Python Programming
- ✔ AI Integration
- ✔ Hugging Face
- ✔ Computer Vision Basics
- ✔ NLP Basics
- ✔ Working with APIs & Pipelines
- ✔ Image Processing
- ✔ Google Colab

---

## 🎯 Future Improvements

- 🎙️ Voice output using Text-to-Speech
- 🌍 Multi-language captions
- 🎨 Better UI with Streamlit
- 📱 Web App Deployment
- 📷 Camera Capture Support
- 🔊 Speech-to-Text image queries

---

## Author 
Jahnvi Srivastava 
