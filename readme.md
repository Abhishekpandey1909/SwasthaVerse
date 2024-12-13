<h1>B.Tech Major Project under the guidance of Prof. Shivesh Sharma</h1>
Summary for GitHub README

**Swasthaverse: Yoga Recommendation System with Real-Time Pose Detection**

This project aims to promote a healthier lifestyle by combining traditional yoga practices with modern technology. Swasthaverse provides personalized yoga recommendations and real-time feedback on yoga poses using machine learning techniques.

#### Features
1. **Yoga Recommendation System**:
   - Suggests yoga poses based on user demographics, fitness levels, medical conditions, and personal goals.
2. **Real-Time Pose Detection**:
   - Utilizes MediaPipe and neural networks to detect and classify yoga poses with high accuracy.
   - Provides alignment feedback to ensure correct postures, reducing the risk of injuries.
3. **User-Friendly Interface**:
   - Streamlit-based app allows seamless interaction with features like pose selection, real-time pose visualization, and progress tracking.

#### Tools and Technologies
- **Programming**: Python
- **Libraries**: MediaPipe, OpenCV, TensorFlow/Keras, XGBoost, Random Forest
- **Framework**: Streamlit

#### Methodology
1. **Data Collection**:
   - Collected yoga pose images labeled with classes (e.g., Downdog, Tree, Plank).
   - Extracted 33 body keypoints using MediaPipe.
2. **Model Training**:
   - Built models using Neural Networks, XGBoost, and Random Forest.
   - Achieved test accuracies of ~96%, ~93%, and ~91%, respectively.
3. **Real-Time Feedback**:
   - Captures live video frames, processes pose landmarks, and predicts alignment with immediate feedback.

#### Future Work
- Expand pose library with more asanas, including Suryanamaskar.
- Develop a recommendation system using advanced models like Llama.
- Enhance UI/UX for better accessibility and engagement.

#### References
This project integrates insights from yoga literature, market analysis, and state-of-the-art machine learning techniques using sources like Yoga Journal, TensorFlow, Kaggle, and Google MediaPipe.

---

This summary highlights the project's objectives, methodology, and technologies for your README. Let me know if you want any modifications!
