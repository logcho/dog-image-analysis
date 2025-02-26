# dog-image-analysis

## Overview  
This project focuses on preprocessing and exploratory analysis of an image dataset. We analyze statistical summaries, visualize attributes, and address data quality issues.  

## Dataset  
- Contains at least 1,000 images  
- Image size > 20x20 pixels  
- Each image is labeled for a well-defined prediction task  

## Objectives  
1. **Business Understanding**  
   - Describe the dataset, its purpose, and potential third-party interests  
   - Discuss the importance and usefulness of the prediction task  

2. **Data Preparation**  
   - Load images as numpy arrays  
   - Resize and recolor images if necessary  
   - Linearize images into a 1-D feature table  
   - Visualize sample images  

3. **Data Reduction**  
   - Perform Principal Component Analysis (PCA)  
   - Perform Randomized PCA  
   - Compare both dimensionality reduction techniques  
   - Perform feature extraction (e.g., Gabor filters, DAISY, etc.)  

4. **Evaluation & Analysis**  
   - Assess the effectiveness of feature extraction  
   - Use visualizations to compare feature statistics across classes  
   - Optional: Perform key point matching with DAISY  

## Requirements  
- Python  
- Jupyter Notebook  
- NumPy, Pandas, OpenCV, scikit-learn, matplotlib, seaborn  
