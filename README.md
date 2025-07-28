
# 🏆 Sports Person Image Classifier

This is an end-to-end **Machine Learning + Web App** project that classifies sports personalities based on image input. The classification is limited to **five well-known athletes**:

- Maria Sharapova  
- Serena Williams  
- Virat Kohli  
- Roger Federer  
- Lionel Messi  

---

## 📁 Folder Structure

```
├── UI/                       # Frontend - HTML, CSS, JS
├── server/                   # Flask backend server
├── model/                    # Jupyter notebook for model training
├── google_image_scrapping/  # Scripts to scrape training images
├── images_dataset/          # Collected dataset of images
```

---

## ⚙️ Technologies Used

### 🐍 Backend & ML
- **Python**
- **Flask** – For serving the ML model via API
- **NumPy** and **OpenCV** – For image preprocessing
- **Matplotlib** and **Seaborn** – For data visualization
- **Scikit-learn** – For model building
- **Jupyter Notebook**, **VS Code**, **PyCharm** – Development IDEs

### 🌐 Frontend
- **HTML/CSS/JavaScript** – For UI design

---

## 🚀 Features

- Image classification using ML model
- Clean UI to upload and classify images
- Custom dataset scraped from Google Images
- End-to-end project from dataset collection to deployment

---

## 🧠 Model Details

- Preprocessing done using OpenCV
- Trained using classical ML models from scikit-learn
- Evaluation through accuracy and confusion matrix
- Focused on face recognition of sports personalities

---

## 📷 Dataset

Images were collected manually using custom Python scripts to scrape **Google Images**. The dataset was organized per class (one folder per person) and used for training/testing the model.

---

## 🔧 How to Run the Project

1. Clone the repository  
2. Install required dependencies from `requirements.txt`
3. Train the model using the Jupyter notebook in the `model/` folder
4. Start the Flask server from the `server/` directory:
   ```bash
   python app.py
   ```
5. Open `UI/index.html` in your browser to access the front-end

---

## 📌 Project Status

✅ Dataset scraped  
✅ Model trained and evaluated  
✅ Flask server integrated  
✅ Frontend developed  
🚧 Future Improvement: Upgrade to deep learning for higher accuracy

---

## 🤝 Acknowledgements

Special thanks to open-source libraries and contributors that made this project possible.

---

## 📬 Contact

For any feedback or queries:  
**Dinesh Kumar** – [LinkedIn](https://www.linkedin.com/in/dinesh-kumar-276123289/)
