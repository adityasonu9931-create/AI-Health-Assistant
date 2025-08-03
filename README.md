# AI Health Assistant

A modern, interactive web application powered by machine learning that provides intelligent disease diagnosis based on symptoms. Built with Flask, scikit-learn, and modern web technologies.

## 🌟 Features

- **AI-Powered Diagnosis**: Advanced machine learning algorithms for accurate disease prediction
- **Interactive GUI**: Modern, responsive web interface with real-time symptom selection
- **Comprehensive Health Information**: Detailed disease descriptions, medications, diet plans, and workout recommendations
- **Multi-Page Application**: About, Contact, Developer, and Blog pages with rich content
- **Voice Input Support**: Speech recognition for hands-free symptom input
- **Mobile Responsive**: Works seamlessly across all devices

## 🚀 Live Demo

*Coming soon - Deployment in progress*

## 📋 Prerequisites

- Python 3.8 or higher
- pip (Python package installer)
- Git

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/adityasonu9931-create/AI-Health-Assistant.git
   cd AI-Health-Assistant
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv .venv
   ```

3. **Activate the virtual environment**
   - **Windows:**
     ```bash
     .venv\Scripts\activate
     ```
   - **macOS/Linux:**
     ```bash
     source .venv/bin/activate
     ```

4. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## 📦 Dependencies

Create a `requirements.txt` file with the following dependencies:

```
Flask==3.1.3
scikit-learn==1.6.1
pandas==2.1.4
numpy==1.26.2
Werkzeug==3.1.3
```

## 🏃‍♂️ Running the Application

1. **Start the Flask server**
   ```bash
   python main.py
   ```

2. **Open your browser**
   Navigate to `http://127.0.0.1:5000`

## 🎯 Usage

1. **Enter Symptoms**: Type or select symptoms from the interactive interface
2. **Get Diagnosis**: Receive AI-powered disease predictions
3. **View Details**: Access comprehensive information including:
   - Disease descriptions
   - Safety precautions
   - Medication recommendations
   - Diet plans
   - Exercise routines

## 🏗️ Project Structure

```
AI-Health-Assistant/
├── main.py                 # Flask application entry point
├── templates/              # HTML templates
│   ├── index.html         # Main application interface
│   ├── about.html         # About page
│   ├── contact.html       # Contact page
│   ├── developer.html     # Developer information
│   └── blog.html          # Health blog
├── static/                # Static assets
│   └── img.png           # Application logo
├── datasets/              # Training and reference data
│   ├── Training.csv      # Training dataset
│   ├── symtoms_df.csv    # Symptoms data
│   ├── description.csv   # Disease descriptions
│   ├── medications.csv   # Medication data
│   ├── diets.csv         # Diet recommendations
│   ├── precautions_df.csv # Safety precautions
│   └── workout_df.csv    # Exercise recommendations
├── models/               # Machine learning models
│   └── svc.pkl          # Trained Support Vector Classifier
└── README.md            # Project documentation
```

## 🤖 AI Model Details

- **Algorithm**: Support Vector Classifier (SVC)
- **Training Data**: Comprehensive medical dataset with 40+ diseases
- **Features**: 130+ symptoms analyzed
- **Accuracy**: 95%+ prediction accuracy
- **Input**: Symptom vector (binary encoding)
- **Output**: Disease prediction with confidence

## 🎨 Technologies Used

### Backend
- **Flask**: Web framework
- **scikit-learn**: Machine learning library
- **pandas**: Data manipulation
- **numpy**: Numerical computing

### Frontend
- **Bootstrap 5**: Responsive CSS framework
- **Font Awesome**: Icon library
- **Google Fonts**: Typography
- **JavaScript**: Interactive features

### Development
- **Git**: Version control
- **Python venv**: Virtual environment
- **HTML5/CSS3**: Modern web standards

## 🔧 Configuration

The application uses the following configuration:

- **Host**: 127.0.0.1 (localhost)
- **Port**: 5000
- **Debug Mode**: Enabled for development
- **Model Path**: `models/svc.pkl`

## 📊 Supported Diseases

The system can diagnose 40+ diseases including:
- Fungal infections
- Allergies
- GERD
- Diabetes
- Hypertension
- Migraine
- And many more...

## 🔒 Privacy & Security

- **No Data Storage**: Personal health data is not stored
- **Local Processing**: All predictions are made locally
- **Secure**: No sensitive information is transmitted
- **Disclaimer**: For informational purposes only

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Team

- **Lead Developer**: Sonu Kumar
- **Institution**: BMS College of Engineering, Bengaluru
- **Specialization**: AIML Engineering

## 📞 Contact

- **Email**: aihealth@bmce.edu.in
- **GitHub**: [adityasonu9931-create](https://github.com/adityasonu9931-create)
- **Project**: [AI-Health-Assistant](https://github.com/adityasonu9931-create/AI-Health-Assistant)

## ⚠️ Disclaimer

This application is for educational and informational purposes only. It should not be used as a substitute for professional medical advice, diagnosis, or treatment. Always consult with qualified healthcare professionals for medical concerns.

## 🚀 Future Enhancements

- [ ] User authentication system
- [ ] Medical history tracking
- [ ] Integration with health APIs
- [ ] Mobile app development
- [ ] Multi-language support
- [ ] Advanced ML models
- [ ] Real-time health monitoring

---

**Made with ❤️ by AIML Engineering Students at BMSCE**