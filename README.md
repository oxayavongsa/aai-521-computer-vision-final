# **_"A Picture is Worth a Thousand Words: Unleashing the Power of OCR"_**<br>
📸AAI-521 Computer Vision Final Project - University of San Diego, School of Engineering - Masters of Applied Artificial Intelligence

---

### **🚀 Project Overview**  - Active
In an age dominated by digital transformation, extracting actionable insights from unstructured visual data is a significant challenge across industries. Optical Character Recognition (OCR) serves as a powerful bridge between visual content and textual information, enabling applications like document digitization, automated data processing, and accessibility enhancements for individuals with disabilities.

Our project, developed for AAI-521: Computer Vision, explores the creation of a robust and versatile OCR pipeline. By leveraging state-of-the-art models—EasyOCR and TrOCR—we tackle diverse real-world challenges such as multilingual text, arbitrary orientations, and noisy image conditions. This pipeline provides a scalable and efficient solution, showcasing the potential of OCR technology to redefine data extraction. 🌟

---

### **🗂 Repository Contents**
Here’s what you’ll find in this repository:  
1. **📄 Final Report**  
   - A detailed technical report outlining our methods, experiments, results, and conclusions.  
   - File: [**Technical Report**](https://docs.google.com/document/d/1FkOGeryOPFlnyoB-tbzl1q5u4E5uhubmwrL6qrZZNIE/edit?usp=sharing)  

2. **💻 Codebase**  
   - Python scripts and Jupyter Notebooks for data preprocessing, model implementation, and performance evaluation. 
   - Launch the notebook directly in Google Colab:  
     [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/oxayavongsa/aai-521-computer-vision-final/blob/main/Model_EasyOCR-and-TrOCR_Complete.ipynb)  

3. **🎥 Presentation Video**  
   - A concise 10-12 minute video summarizing our work, methods, and findings. 
   - [**YouTube Link**](https://youtu.be/Em239t2VNRY)<br><br>
   [![A Picture is Worth a Thousand Words: Unleashing the Power of OCR](https://img.youtube.com/vi/Em239t2VNRY/0.jpg)](https://youtu.be/Em239t2VNRY)

4. **📂 Organized Files**  
   - **`/final`**: Contains the polished deliverables, including the final report, presentation, and base code.
   - **`/processed`**: Files used for preprocessing and experimental work.
   - **`/images`**: Images contained in our code file _"Model_EasyOCR-andTrOCR_Complete.ipynb"_
   - **`requirement.txt`**: Library and Dependency packages
   - **`Model_EasyOCR-and-TrOCR_Complete.ipynb`**: The primary notebook for running the OCR pipeline.  

---

### **🎯 Project Goals**
This project addresses real-world challenges in text recognition by:
- **Implementing Advanced OCR Models**: Comparing EasyOCR and TrOCR for multilingual and complex text recognition. 
- **Designing a Text Extraction Pipeline**: Developing preprocessing steps to optimize input quality and enhance model accuracy 
- **Optimizing Performance**: Fine-tuning models and evaluating their scalability for practical applications like document digitization and accessibility tools.  

---

### **📊 Dataset**
We utilized the TextOCR Dataset, available on Kaggle:
🌐[**TextOCR: Text Extraction from Images Dataset**](https://www.kaggle.com/datasets/robikscube/textocr-text-extraction-from-images-dataset)  

- **Source:** TextVQA images annotated for OCR tasks.  
- **Key Features:**  
  - 900,000+ word-level annotations.  
  - Annotated images with varied resolutions, orientations, and multilingual content.  
  - JSON labels for structured parsing.
    
- **Challenges Addressed:**
  - Diverse image qualities and text layouts.
  - Multilingual and curved text.
  - Noise from shadows, clutter, and distortions.
    
---

### **🛠️ How to Use**

1. **Clone the repository:**  
   Run the following command in your terminal to clone the repository to your local machine:  
   ```bash
   git clone https://github.com/oxayavongsa/aai-521-computer-vision-final.git

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt

3. Open the main notebook:
   Run locally or open directly in Google Colab via the provided badge.

4. Run the pipeline:
   Preprocess images, train models, and evaluate results directly within the notebook.

## **🛠 Technologies Used**  
  - Python: Programming language for data processing and modeling.
  - EasyOCR: Lightweight OCR model for simple layouts.
  - TrOCR: Transformer-based VisionEncoderDecoder model for complex and multilingual scenarios.
  - Jiwer Library: Evaluation metrics for WER (Word Error Rate) and CER (Character Error Rate).
  - Hugging Face Transformers: Framework for implementing TrOCR.
---
### **📊 Results and Key Insights**

- TrOCR demonstrated superior accuracy, achieving:
  - WER: 1.00%
  - CER: 0.99%

- EasyOCR offered faster inference but struggled with complex layouts:
  - WER: 3.10%
  - CER: 3.87%

- Advanced preprocessing techniques—grayscale conversion, binarization, and deskewing—significantly improved OCR performance.

- Both models excel in different scenarios:
  - EasyOCR is ideal for simple, structured text.
  - TrOCR is better suited for noisy, multilingual, or distorted text.

---

### **📅 Task List - Team Members**

**Outhai Xayavongsa (Ms. Thai)** _(Team Leader)_  
- Created task lists, organized meets, and managed team coordination.  
- Implemented and validated the TrOCR model.  
- Integrated and Completed **EasyOCR** and **TrOCR** models.  
- Evaluated model performance and fine-tuned metrics.
- Created pipelines and documented processes.  

**Jay Patel** _(Team Member)_
- Selected dataset and assessed quality.  
- Cleaned and preprocessed the dataset.  
- Experimented with various Model Methods

**Daniel Shifrin** _(Team Member)_ 
- Performed EDA and extracted dataset features.
- Assisted with EasyOCR implementation and optimization.

---

✨ Future Work

To further enhance OCR performance:
- Address challenges with low-light and low-resolution images.
- Explore additional models like PaddleOCR or fine-tune existing ones.
- Implement real-time OCR pipelines for large-scale applications.

---

📫 Contact

For inquiries or collaboration opportunities, feel free to reach out to the Team Leader:
- Outhai Xayavongsa (Ms. Thai): [**LinkedIn Profile**](https://www.linkedin.com/in/oxayavongsa/)
