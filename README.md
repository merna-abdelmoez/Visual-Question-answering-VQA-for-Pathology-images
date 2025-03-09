# Medical Visual Question Answering (VQA) Model

<p align="center">
  <img src="https://github.com/merna-abdelmoez/Visual-Question-answering-VQA-for-Pathology-images/blob/main/assests/Screenshot%202025-03-09%20212836.png" alt="Medical VQA"/>
</p>

## Overview
The Medical Visual Question Answering (VQA) Model leverages Bootstrapped Language-Image Pretraining (BLIP) to interpret complex medical images and provide accurate answers to clinical questions. This AI-powered system enhances decision-making in diagnostics by combining vision and language models.

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

<table>
  <tr>
    <td align="center">
    <a href="https://github.com/merna-abdelmoez" target="_black">
    <img src="https://github.com/merna-abdelmoez.png" width="150px;" alt="Merna Abd ElMoez"/>
    <br />
    <sub><b>Merna Abd ElMoez</b></sub></a>
    <td align="center">
    <a href="https://github.com/Omartarek78" target="_black">
    <img src="https://github.com/Omartarek78.png" width="150px;" alt="Omar Tarek"/>
    <br />
    <sub><b>Omar Tarek</b></sub></a>
    </td>
    </td>
    <td align="center">
    <a href="https://github.com/abdallahahmed11" target="_black">
    <img src="https://github.com/abdallahahmed11.png" width="150px;" alt="Abdallah Ahmed"/>
    <br />
    <sub><b>Abdallah Ahmed</b></sub></a>
    </td>
    <td align="center">
   <td align="">
    <a href="https://github.com/mayar" target="_black">
    <img src="https://github.com/mayar.png" width="150px;" alt="Mayar Ahmed"/>
    <br />
    <sub><b>Mayar Ahmed</b></sub></a>
    </td>
 </table>

## Acknowledgments
**This project was supervised by Dr.Inas Yassin, who provided invaluable guidance and expertise throughout its development as a part of the Deep Learning Course at Cairo University Faculty of Engineering.**


<div style="text-align: right">
    <img src="https://imgur.com/Wk4nR0m.png" alt="Cairo University Logo" width="100" style="border-radius: 50%;"/>
</div>
