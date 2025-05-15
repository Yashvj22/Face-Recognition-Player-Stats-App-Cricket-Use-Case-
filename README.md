# Player Face Classifier & Cricket Stats Comparison 🚀

This Streamlit web application merges the power of **computer vision** and **data analytics** to create a unique and interactive experience for cricket enthusiasts. Upload images of two Indian cricket players, and the app will recognize them using facial recognition and visually compare their career statistics across **Test, ODI, T20, and IPL formats**.

---

## Features

### Face Detection & Recognition
- Uses **Haar Cascade** for face detection.
- Classifies players using a **Support Vector Classifier (SVC)** trained on facial images of **28 Indian cricket players**.

### Image-Based Player Identification
- Upload **clear, frontal face images** to let the model predict the player’s identity with high accuracy.

### Cricket Stats Comparison
Compare players on various metrics like:
- 🏏 **Total Runs & Wickets**
- ⚡ **Strike Rate vs. Runs**
- 🏆 **Milestones** (50s, 100s, 200s)
- 🧩 **Match Distribution** across formats

### Interactive Charts
- Uses **Plotly** and **Seaborn** to deliver stunning, dynamic visualizations for a rich user experience.

---

## 📁 Dataset
- Over **300 facial images per player** (augmented for robustness).
- Images flattened for ML training.
- Preprocessed career statistics of 28 Indian players
- **Source**: Collected and preprocessed from **RapidAPI**

---

## Tech Stack

| Area              | Tool/Library                 |
|-------------------|------------------------------|
| **Frontend**       | Streamlit                    |
| **ML Model**       | Support Vector Classifier (SVC) |
| **Face Detection** | OpenCV (Haar Cascade)        |
| **Data Handling**  | Pandas, NumPy                |
| **Visualization**  | Plotly, Seaborn, Matplotlib  |

---

## 🌐 Try it on Hugging Face 

No setup required — experience the app directly in your browser!

👉 **Check it out here**: [Hugging Face Spaces – CricCraze](https://huggingface.co/spaces/Yashvj123/CricCraze)


---
