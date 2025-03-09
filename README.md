# Medical Visual Question Answering (VQA) Model

![Medical VQA](assests/Screenshot 2025-03-09 212836.png)
## Overview
The **Medical Visual Question Answering (VQA) Model** leverages **Bootstrapped Language-Image Pretraining (BLIP)** to interpret complex medical images and provide accurate answers to clinical questions. This AI-powered system enhances decision-making in diagnostics by combining vision and language models.

## Features
- **Automated Medical Image Interpretation**: Generates precise answers for clinical queries.
- **Deep Learning-Based Model**: Utilizes BLIP for multimodal learning.
- **Supports Open-Ended & Yes/No Questions**: Enhances flexibility in medical diagnostics.
- **Efficient Training & Inference**: Optimized for large-scale pathology datasets.

## Dataset
The dataset consists of **32,799 medical-related questions** linked to **4,998 pathology images**, sourced from:
- "Textbook of Pathology"
- "Basic Pathology"
- Pathology Education Informational Resource (PEIR)


### Dataset Splits:
- **Training**: 19,654 samples
- **Validation**: 6,259 samples
- **Testing**: 6,719 samples

## Methodology
### 1. Data Preprocessing
- Image resizing & normalization  
- Text tokenization & padding  
- Answer encoding for supervised training  

### 2. Model Architecture
- **Visual Encoder**: Vision Transformer (ViT) extracts image features  
- **Text Encoder**: Transformer-based text processing  
- **Cross-Attention Mechanism**: Aligns visual and textual representations  
- **Multimodal Pretraining**: Joint contrastive and generative learning  

### 3. Training Process
- **Loss Function**: Cross-entropy loss for answer prediction  
- **Optimizer**: Adam optimizer  
- **GPU Acceleration**: Trained on high-performance hardware  

### 4. Evaluation Metrics
- **Accuracy**: Measures correct answers  
- **BLEU Score**: Evaluates linguistic similarity to ground truth  

## Results
### Quantitative Performance
- **Validation BLEU Score**: 0.042  
- **Validation Loss**: 37  


## Contributors
Gratitude to all contributors who made this project possible.

<div align="left">
  <a href="https://github.com/your-github-username">
      <img src="https://github.com/your-github-merna-abdelmoez.png" width="100px" alt="@your-github-username">
  </a>
</div>

## License
This project is licensed under the [MIT License](LICENSE.md).
