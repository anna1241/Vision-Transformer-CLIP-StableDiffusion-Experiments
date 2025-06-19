# Vision Transformer, CLIP & Stable Diffusion Experiments

This project explores the use of Vision Transformers (ViT), CLIP, and Stable Diffusion for advanced computer vision tasks. The aim is to implement these state-of-the-art models for spoof detection, AI-powered visual search, style transfer, and product mockup generation using COCO and CelebA-Spoof datasets.

## Objectives

- Leverage ViT for face spoof detection in security applications
- Implement image retrieval using OpenAI's CLIP-ViT model
- Use Stable Diffusion for image variation, style transfer, and product mockup generation
- Analyze model outputs, parameters, and performance metrics

## Datasets

- **COCO Validation Set:** Images and annotations for image retrieval tasks
- **CelebA-Spoof (HuggingFace - nguyenkhoa/celeba-spoof-for-face-antispoofing-test):** Real vs. spoof face images for anti-spoofing model training


## Tasks

### 1️⃣ Spoof Detection
- Fine-tune ViT for binary classification (Real vs. Spoof)
- Evaluate using Accuracy, Precision, Recall, F1-score
- Include real and spoofed images (replay attack from mobile screen) in testing

### 2️⃣ AI-Powered Visual Search
- Encode COCO images and text queries using CLIP-ViT
- Retrieve and display top 5 similar images for a query with similarity scores

### 3️⃣ Stable Diffusion
- Generate image variations based on prompts and parameter tuning (strength, guidance_scale, num_inference_steps)
- Analyze impact of parameter changes on output realism and detail
- Create at least 5 different artistic styles and compare generated results

### 4️⃣ Mockup Generation 
- Generate product mockups (e.g., coffee mugs) with Stable Diffusion
- Tune parameters to adjust style intensity
- Showcase style diversity using different design prompts
