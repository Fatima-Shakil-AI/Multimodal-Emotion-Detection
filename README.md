**Multimodal Emotion Detection**

**Description:**  
A Python-based AI project for detecting human emotions using **facial expressions** and **voice cues**. This project leverages **ResNet50** for face feature extraction and **MFCCs** for audio feature extraction, combining them in a **fusion neural network** for accurate emotion recognition. Designed for real-time and offline testing, this project demonstrates multimodal affective computing applications, including mental health monitoring and human-computer interaction.

**Features**
- **Multimodal Input:** Combines visual (face) and auditory (voice) features.
- **Pretrained CNN:** Uses ResNet50 for facial feature extraction.
- **Audio Processing:** Extracts MFCC features from speech signals.
- **Fusion Model:** Fully connected neural network for emotion classification.
- **Demo Ready:** Includes sample image and audio testing cells for Colab.

**Usage**

Clone the repository:

git clone https://github.com/<your-username>/Multimodal-Emotion-Detection.git
cd Multimodal-Emotion-Detection

Open the Emotion_Detection_Colab.ipynb in Google Colab.
Run the cells to extract features, train the model, and test sample data.

**Dataset**

RAVDESS: RAVDESS Emotional Speech & Song Dataset
Includes labeled audio and video files for multiple emotions.

**Results**

Real-time predictions for uploaded face images and audio clips.
Visualizations of facial input and audio waveform.
Fusion-based emotion classification.
