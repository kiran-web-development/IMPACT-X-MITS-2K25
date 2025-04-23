# 🚑 MedScanAI – AI-Based Early Disease Detection from Medical Imaging

## 👥 Team Details

- **Team Name:** `Web Lines Fun`  
- **Team Lead:** `M. Kiran Kumar` 
- **Team Members:** `G.Mallikarjuna`                        `K.Munichanchu Reddy`  

---

## 🧠 Overview

**MedScanAI** is an AI-powered diagnostic system designed to assist healthcare professionals by analyzing medical images such as **X-rays**, **CT scans**, and **MRIs**. The platform detects early signs of **lung cancer**, **brain tumors**, and **cardiac anomalies**, providing real-time diagnostic suggestions and visual annotations for enhanced decision-making.

Built with scalability, speed, and accuracy in mind, MedScanAI is especially valuable in **resource-limited or rural healthcare setups**.

---

## ✅ Functional Features

### 1. Multi-Modal Medical Image Analysis
- Accepts image inputs in **DICOM, PNG, JPG** formats.
- Powered by pre-trained deep learning models using:
  - **NIH ChestX-ray14**
  - **BraTS**
  - **LUNA16**

### 2. Real-Time Diagnosis Suggestions
- **<5-second** prediction time.
- Provides:
  - Disease probability scores (e.g., “Lung Nodule: 93%”)
  - Annotated **Grad-CAM** or **saliency heatmaps**
  - **Urgency indicators**: Low / Medium / High risk

### 3. Integration with Medical Software
- Supports **REST APIs** for easy integration.
- Compatible with **HL7/FHIR standards**.
- Export results as **PDF** or auto-email reports to practitioners.

### 4. Accuracy & Validation
- Uses:
  - **Cross-validation**
  - **Ensemble models**
  - **Active learning with feedback loop**
- Maintains accuracy **>95%** with physician-driven improvements.

---

## ⚙️ Non-Functional Features

- ⚡ **Fast Response:** Inference within **<5 seconds**.
- 📴 **Offline Mode:** Operates with locally deployed models (ONNX or TFLite).
- 📱 **Device Friendly:** Compatible with low-spec smartphones and laptops.
- 🔒 **Data Privacy:** Fully compliant with **HIPAA/GDPR** standards.

---

## 🛠️ Tech Stack

### Frontend
- Web: **React.js**
- Mobile: **Flutter**

### Backend / AI
- **Python**, **FastAPI**
- **TensorFlow** / **PyTorch**
- **OpenCV** (image preprocessing)

### Deployment
- **ONNX** (Edge devices)
- **TensorFlow Lite** (Mobile)
- **Docker** (Clinical environments)

### Database
- **SQLite** (Offline support)
- Optional **Firebase** or **PostgreSQL** sync for cloud storage

---

## 📈 Extra Features (Optional but Impactful)

- 🔄 **Physician Feedback Loop:** Improve model accuracy from real-world usage.
- 🧭 **Risk Timeline:** Track disease progression if patient history is available.
- 🌍 **Multi-Language Support:** For use in multilingual and rural clinics.

---

## 📂 Project Status

> ✅ Prototype in development | 🚧 Deployment testing pending | 💬 Physician feedback module next

---

## 📧 Contact

For collaborations or inquiries:
**Email:** medscanai.team@example.com  
**GitHub:** [github.com/your-repo-name](https://github.com/your-repo-name)





---

## 🚀 Getting Started: Local Development Setup

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Install & Configure Tailwind CSS
Follow these steps to add Tailwind CSS to your React project:

```bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

- In `tailwind.config.js`, set the content paths:
  ```js
  module.exports = {
    content: [
      "./src/**/*.{js,jsx,ts,tsx}",
    ],
    theme: {
      extend: {},
    },
    plugins: [],
  }
  ```
- In `src/index.css`, add:
  ```css
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
  ```

### 4. Install Material-UI (MUI)
```bash
npm install @mui/material @emotion/react @emotion/styled @mui/icons-material
```

### 5. Start the Development Server
```bash
npm start
```

---

## 🗂️ Suggested Project Structure

```
/src
  /components
    /common
      Navbar.jsx
      Footer.jsx
      CTASection.jsx
      ...
    /Home
      HeroHeaderSection.jsx
      FeaturesListSection.jsx
      ...
    /AboutUs
      HeaderSection.jsx
      AboutSection.jsx
      ...
    /Blog
      FeaturedBlogListHeaderSection.jsx
      BlogListSection.jsx
      ...
    /Products
      HeaderSection.jsx
      FeaturesListSection.jsx
      ...
    /Product
      HeaderSection.jsx
      FeatureSection.jsx
      ...
  /pages
    Home.jsx
    AboutUs.jsx
    Blog.jsx
    Products.jsx
    Product.jsx
  App.jsx
  index.js
```

---

## 📱 Mobile Responsiveness
- All components are designed mobile-first using Tailwind CSS utility classes and Material-UI responsive props.
- Tested for device widths from 320px to 430px (2020–2025 smartphones).
- Use Chrome DevTools or [Responsively App](https://responsively.app/) for testing.

---

## 🧩 Sample Usage
- See `/src/pages/Home.jsx` and `/src/components/Home/` for sample wireframe code using Tailwind CSS and Material-UI.

---

## 📝 Contribution
Feel free to fork, open issues, or submit pull requests!

---

