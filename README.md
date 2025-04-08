SpeechPrint is a machine learning project that analyzes how native language and geographic background influence the way people speak English. Using an LSTM model trained on MFCC features from speech recordings, the model attempts to classify the speaker’s country of origin based on their English speech.

This project is designed as a learning journey into audio processing and sequence modeling using Python. It explores key concepts such as feature extraction (MFCCs), audio classification, LSTM networks, and handling real-world datasets with imbalances.

🚀 Project Goals
Convert raw English speech into usable machine learning features

Train a neural network to predict the speaker’s origin based on speech

Learn and apply techniques in:

Audio feature extraction (MFCC)

LSTM-based classification

Handling class imbalance

Model evaluation and training best practices

📁 Dataset
The dataset includes:

2,140 speech samples (.mp3), each from a different speaker reading the same English passage

Demographic metadata for each speaker

177 countries and 214 native languages represented

🛠️ Tech Stack
Python

Librosa (audio feature extraction)

Pandas / NumPy (data handling)

scikit-learn (data preprocessing and evaluation)

PyTorch or TensorFlow (LSTM model)

🔍 Why It Matters
SpeechPrint can help us understand how global accents shape spoken English and open up future applications like:

Accent recognition

Speech personalization

Linguistic research

Language education tools

Data Insights

Top native languages are English, Spanish, Arabic
<img width="1013" alt="Screenshot 2025-03-04 at 4 18 14 PM" src="https://github.com/user-attachments/assets/e0056067-194e-43bc-a3e8-b385c2e897c3" />
<img width="1013" alt="Screenshot 2025-03-04 at 4 18 49 PM" src="https://github.com/user-attachments/assets/eeafe2ef-5906-4e1a-a627-a3cf64459c94" />

Top countries of origin are USA, China, UK
<img width="1008" alt="Screenshot 2025-03-04 at 4 19 42 PM" src="https://github.com/user-attachments/assets/44d37d83-9230-41a7-b7ed-27912a1ca9a0" />
<img width="1020" alt="Screenshot 2025-03-04 at 4 20 09 PM" src="https://github.com/user-attachments/assets/20796af7-7b72-43e5-bcbf-8eed496d41b9" />

Gender Breakdown
<img width="1004" alt="Screenshot 2025-03-04 at 4 19 16 PM" src="https://github.com/user-attachments/assets/811eb6c7-e9d5-4aee-ba0e-59eb7b264e69" />

Age Breakdown
<img width="1033" alt="Screenshot 2025-03-04 at 4 21 06 PM" src="https://github.com/user-attachments/assets/7f08742d-81cc-4cae-a096-0f16e9cb6645" />



