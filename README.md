# Portfolio Website Generator

An interactive and visually appealing web application for processing resumes and generating a professional portfolio. This project leverages cutting-edge technologies to simplify the process of resume parsing and portfolio creation.

---

## 🚀 **Purpose**
The Portfolio Generator is designed to:
- Extract text from uploaded PDF resumes.
- Classify the extracted content into well-defined sections such as **Summary**, **Skills**, **Experience**, **Projects**, **Education**, and **Certifications**.
- Display the classified information in an elegant, user-friendly portfolio format.

---

## ✨ **Main Features**
- **PDF Upload & Parsing**: Upload resumes in PDF format and extract text using PyMuPDF.
- **NLP-Powered Classification**: Automatically classify resume content into key sections using spaCy.
- **Interactive Portfolio Viewer**: View your resume data in a dynamic, card-based layout with smooth animations.
- **Dark Mode**: Toggle between light and dark themes for better accessibility.
- **Responsive Design**: Fully responsive interface for seamless use across devices.
- **Smooth Scrolling**: Intuitive navigation with smooth scrolling for an enhanced user experience.

---

## 🛠️ **Technologies Used**
- **Backend**: Python, Flask
- **PDF Parsing**: PyMuPDF (fitz)
- **Natural Language Processing (NLP)**: spaCy
- **Frontend**: HTML, CSS, JavaScript
- **Styling Frameworks**: Bootstrap
- **Additional Features**: FontAwesome for icons, custom animations

---

## 🖥️ **How to Run**
1. Clone the repository:
   ```
   git clone 
   cd 
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Run the Flask application:
   ```
   python app.py
   ```
4. Open your browser and navigate to:
   ```
   http://127.0.0.1:5000
   ```

---

## 📂 **Project Structure**
```
Portfolio Generator/
├── static/               # Static files (CSS, JS, images)
├── templates/            # HTML templates
├── app.py                # Flask application logic
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

---

## 🌟 **Screenshots**
### Light Mode
![image](https://github.com/user-attachments/assets/1d3de168-341c-4a8f-9e99-31354748544b)

### Dark Mode
![image](https://github.com/user-attachments/assets/3e4eedbe-b310-4712-b3ea-516b39372534)

---

## 🎨 **Customization**
You can easily customize the following:
1. Add more sections to the portfolio by modifying `classify_sections` in `app.py`.
2. Update styles in `static/style.css` to match your branding.
3. Enhance the UI/UX by adding more animations or interactivity in `static/script.js`.

---

## 🤝 **Contributing**
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a detailed description of your changes.

---

## 📜 **License**
This project is licensed under the MIT License.

