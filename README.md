# Face-Detection-and-Recognition-WorkshopCV
## Description
This project is a workshop assignment for the Computer Vision course. It involves a dataset containing 140 images of 7 individuals, with 20 images per person. The dataset is used to train a face recognition model using the Eigenface method combined with a Support Vector Machine (SVM) classifier. 

1. **README.md** — program guide.
2. **Tugas Workshop_512057_Amelia Syahla Aurellia Sambudi.ipynb** — a Jupyter notebook containing code to build and run a face recognition program.
3. **eigenface_pipeline.pkl** — a model file resulting from training using the PCA (Principal Component Analysis) method.
4. **images/** — Folder 'images' that contains the face image dataset to be used for training.

## Step
Here are the step-by-step instructions to run my code using the existing model, which was trained on 140 images.
1. Clone this repository
   ```
   git clone https://github.com/AmeliaSyahla/Face-Detection-and-Recognition-WorkshopCV.git
   cd 'Face-Detection-and-Recognition-WorkshopCV'
   ```
2. Install all the extensions requested by VSCode
3. Setup Virtual Environment
   ```
   python -m venv .venv
   .venv/Scripts/activate
   ```
4. Install packages to help run your code (library)
   ```
   pip install -r packages.txt
   ```
5. Real time implementation based on video mp4 recorded (because my webcam not available)
   Run the `main.py` on terminal
   ```
   python main.py
   ```

Notes:
-> If you want to try retrain this model with your new dataset image, you can follow this step: 
1. Add your images dataset to the 'images' folder
2. Follow the detailed step in 'Tugas Workshop_512027_Amelia Syahla Aurellia Sambudi'
3. Save the newly trained model ('eigenface_pipeline.pkl')
4. Execute 'main.py'
   
    
