# 🏥 Indian Surgical Emergency Patients Generator

![Version](https://img.shields.io/badge/version-2.2-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Medical Education](https://img.shields.io/badge/education-MBBS%20%7C%20NEET--PG-orange.svg)
![Platform](https://img.shields.io/badge/platform-Web-lightgrey.svg)

## 🎯 Live Demo

**[Try the Application](https://same-0e34kcm6k2r-latest.netlify.app)**

## 📋 Overview

The **Indian Surgical Emergency Patients Generator** is a comprehensive synthetic data generation tool specifically designed for the Indian medical education system. This application generates realistic surgical emergency patient data with authentic Indian names, addresses, medical practices, and insurance schemes.

Perfect for **MBBS students**, **surgery departments**, **medical colleges**, and **NEET-PG preparation**, this tool creates educational case studies that mirror real Indian healthcare scenarios.

## ✨ Key Features

### 🇮🇳 Indian Medical Localization
- **Authentic Indian Names**: Regional first and last names from across India
- **Indian Cities & Addresses**: Real cities with local address formats (Sector, Block, Colony, etc.)
- **Indian Insurance Systems**: ESI, CGHS, Ayushman Bharat, Private Insurance schemes
- **Metric Units**: Temperature in Celsius, weight in kg, height in cm
- **Indian Medical Terminology**: Local medical practices and medication names

### 🩺 Surgical Specializations (7 Emergency Conditions)
1. **Acute Appendicitis** (K35.9)
2. **Strangulated Inguinal Hernia** (K40.4)
3. **Acute Cholecystitis** (K80.0)
4. **Acute Pancreatitis** (K85.9)
5. **Perforated Ulcer** (K25.1)
6. **Acute Intestinal Obstruction** (K56.9)
7. **Peritonitis** (K65.9)

### 🎓 Educational Features
- **Student Questions**: Category-wise clinical questions for each diagnosis
  - History Taking
  - Physical Examination
  - Differential Diagnosis
  - Investigations
  - Management & Surgery
- **Realistic Medical Records**: Complete patient histories, medications, lab results
- **Surgical Procedures**: Condition-specific surgical interventions
- **Case Severity Levels**: Mild, Moderate, Severe presentations

### 📊 Advanced Analytics
- **Interactive Charts**: Age distribution and diagnosis breakdown
- **Smart Filtering**: Search by name, diagnosis, or any patient field
- **Data Export**: CSV and JSON formats for research and education
- **Batch Generation**: Generate up to 1000 patients efficiently

## 🔧 Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Charts**: Chart.js for data visualization
- **Responsive Design**: Mobile-first approach with CSS Grid/Flexbox
- **Data Export**: Built-in CSV/JSON export functionality
- **No Backend Required**: Fully client-side application

## 🚀 Getting Started

### Quick Start
1. **[Open Live Demo](https://same-0e34kcm6k2r-latest.netlify.app)**
2. Set your generation parameters (patient count, age range, gender, severity)
3. Click "Generate Surgical Patients"
4. Explore patient details, view charts, and export data

### Local Setup
```bash
# Clone the repository
git clone https://github.com/adrenolitik/indian-surgical-patients-generator.git

# Navigate to project directory
cd indian-surgical-patients-generator

# Open index.html in your browser
# Or serve with a local web server
python -m http.server 8000
# Then visit http://localhost:8000
```

## 📖 Usage Guide

### 🔢 Generation Parameters
- **Patient Count**: 1-1000 patients per generation
- **Age Ranges**: Young Adults (18-35), Middle Age (36-60), Elderly (60+), or All Ages
- **Gender**: Mixed, Male Only, or Female Only
- **Severity**: Mixed, Mild Cases, Moderate Cases, or Severe Cases

### 📊 Patient Data Includes
- **Demographics**: Name, age, gender, address, phone, email
- **Clinical Data**: Diagnosis with ICD-10 codes, vital signs, severity
- **Medical History**: Prescriptions, surgical history, visit notes
- **Laboratory Results**: WBC, neutrophils, lactate, creatinine, organ-specific markers
- **Educational Content**: Diagnosis-specific student questions

### 🔍 Advanced Features
- **Search & Filter**: Real-time search across all patient fields
- **Detailed View**: Complete patient records with medical history
- **Export Options**: CSV for spreadsheets, JSON for programming
- **Responsive Design**: Works on desktop, tablet, and mobile

## 🎯 Target Audience

### 👨‍🎓 Medical Students
- **MBBS Students**: Clinical case studies and exam preparation
- **Surgery Residents**: Emergency surgical case scenarios
- **NEET-PG Aspirants**: Practice with realistic surgical cases

### 🏥 Medical Institutions
- **Medical Colleges**: Teaching material for surgery departments
- **Hospitals**: Training scenarios for emergency medicine
- **Research Centers**: Synthetic data for medical research

### 📚 Educational Applications
- **Case-Based Learning**: Interactive patient scenarios
- **Examination Preparation**: NEET-PG, AIIMS, JIPMER
- **Clinical Skills**: History taking and examination practice
- **Differential Diagnosis**: Pattern recognition training

## 🧪 Sample Data Structure

```json
{
  "id": "A7F2K9M3L",
  "name": "Priya Sharma",
  "age": 28,
  "gender": "Female",
  "city": "Delhi",
  "diagnosis": "Acute Appendicitis",
  "diagnosisCode": "K35.9",
  "severity": "moderate",
  "temperature": "37.8°C",
  "bloodPressure": "115/75 mmHg",
  "heartRate": "98 bpm",
  "painScore": "6/10",
  "medicalRecords": {
    "prescriptions": [...],
    "surgicalHistory": [...],
    "labResults": {...},
    "studentQuestions": [...]
  }
}
```

## 🔬 Medical Accuracy

### Indian Healthcare Context
- **Insurance Schemes**: Authentic Indian health insurance providers
- **Medication Names**: Generic and brand names commonly used in India
- **Clinical Protocols**: Following Indian medical practice guidelines
- **Laboratory Values**: Ranges appropriate for Indian population

### Educational Standards
- **MBBS Curriculum**: Aligned with Indian medical education standards
- **Examination Pattern**: Questions formatted for NEET-PG style
- **Clinical Reasoning**: Step-by-step diagnostic approach
- **Evidence-Based**: Current surgical management protocols

## 🤝 Contributing

We welcome contributions from the medical education community! Please see our [Contributing Guidelines](CONTRIBUTING.md) for:

- **Medical Content**: Improving clinical scenarios and questions
- **Localization**: Adding more regional names and medical practices
- **Features**: Enhancing functionality for educational use
- **Bug Reports**: Helping improve the application

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Indian Medical Council**: For educational standards and guidelines
- **NEET-PG Community**: For feedback on examination-style questions
- **Medical Colleges**: For insights into teaching requirements
- **Healthcare Professionals**: For clinical accuracy review

## 📞 Support & Contact

- **Issues**: [GitHub Issues](https://github.com/adrenolitik/indian-surgical-patients-generator/issues)
- **Discussions**: [GitHub Discussions](https://github.com/adrenolitik/indian-surgical-patients-generator/discussions)
- **Educational Queries**: For medical college collaborations

---

## 🏷️ Version History

### v2.2 - Indian Medical Edition (Current)
- ✅ Complete Indian localization
- ✅ 7 surgical emergency conditions
- ✅ Student educational questions
- ✅ Metric units and Indian medical terminology
- ✅ Advanced analytics and export features

---

**Made with ❤️ for Indian Medical Education**

*Supporting MBBS students, surgery departments, and medical colleges across India*