🎨 **Face to Anime Translation using DiscoGAN (TensorFlow)**
📌** Project Overview
**
This project implements a DiscoGAN-inspired model using TensorFlow/Keras to convert human face images into anime-style images.

It uses an encoder-decoder architecture with skip connections (similar to U-Net) and learns mappings between two domains:

👤 Human Faces (Domain A)
🎭 Anime Faces (Domain B)# Copy_of_Generative_Adversarial_Network.ipynb


🚀** Features**

🔄 Image-to-image translation (Face → Anime)

🧠 Deep learning using TensorFlow

🧩 Encoder-Decoder with skip connections

🎯 Instance Normalization for better style transfer

📊 Visualization of dataset samples

☁️ Google Colab + Google Drive integration


Dataset/


├── trainA/       # Human faces (training)

├── trainB/       # Anime faces (training)

├── testA/        # Human faces (testing)

├── testB/        # Anime faces (testing)

⚙️  **Installation**

Run the following in Google Colab or locally:

pip install tensorflow opencv-python matplotlib tqdm segmentation-models-pytorch scikit-image

🔗 **Google Drive Setup (Colab)**

from google.colab import drive
drive.mount('/content/gdrive')


🖼️ Data Visualization

The project randomly displays sample images from both domains:

Human Faces
Anime Faces

Images are:

Resized to 128×128
Converted from BGR → RGB


📌 **Future Improvements**

🔁 Add full DiscoGAN training loop

🎯 Improve style conditioning

⚡ Use CycleGAN loss functions

📊 Add evaluation metrics (FID score)

🌐 Build web app using Streamlit


**sample output**

<img width="1307" height="649" alt="image" src="https://github.com/user-attachments/assets/807be467-55f3-4456-985c-e5ef589ceed1" />
