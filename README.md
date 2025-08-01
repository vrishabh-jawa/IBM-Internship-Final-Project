# IBM-Internship-Final-Project
This project automates the scheme classification of rural roads and bridges across India by applying machine learning to historical PMGSY data. It provides an interactive REST API that returns predicted scheme labels based on project details.
# Intelligent Classification of Rural Infrastructure Projects (PMGSY) 🚜

An AI-powered system designed to classify rural infrastructure projects under PMGSY-I, PMGSY-II, and RCPLWE schemes using only IBM Cloud tools. Built using IBM Watsonx.ai and AutoAI, this intelligent model enables accurate classification based on real project data like cost, road length, completion status, and location.
<img width="1024" height="1024" alt="ChatGPT Image Aug 1, 2025, 03_58_24 PM" src="https://github.com/user-attachments/assets/ebdf9d72-3c16-420c-9f07-b53e54b3b03a" />


---

## 🧩 Problem Statement

Thousands of rural infrastructure projects across India are managed under schemes like PMGSY-I, PMGSY-II, and RCPLWE. Manual classification is inefficient, error-prone, and does not scale well. Accurate classification is essential for project monitoring, funding decisions, and scheme-wise analytics.

---

## 💡 Proposed Solution

A machine learning model trained using IBM Watsonx.ai AutoAI that automatically classifies projects into their respective PMGSY schemes using project attributes. The model is deployed using IBM Watson Machine Learning and integrated with a REST API for real-time classification.

---

## 🧠 Technologies Used

- IBM Watsonx.ai Studio (Notebook & AutoAI)
- IBM Cloud Object Storage
- IBM Watson Machine Learning (WML)
- Python: pandas, numpy, scikit-learn, matplotlib

---

## ☁️ IBM Cloud Services Used

- IBM Cloud Object Storage (dataset upload)
- IBM Watsonx.ai Studio (data processing & AutoAI)
- IBM Watson Machine Learning (model deployment)
- IBM Cloud Lite Account (free-tier resources)

---

## 👥 End Users

- Government officers handling rural development data  
- Data analysts evaluating PMGSY project outcomes  
- NGOs monitoring infrastructure impact  
- Policy makers needing scheme-wise segmentation  
- Researchers studying rural connectivity programs  

---

## 🌟 WOW Factors

- Built entirely using IBM Cloud Lite tools  
- No external platforms or paid services used  
- Real PMGSY dataset with state/district-level features  
- Supports live classification via API  
- Fully automated modeling via IBM AutoAI  
- Scalable for thousands of entries with minimal delay  

---

## 🧪 Key Features

- AutoAI-driven classification of rural projects  
- REST API deployment for real-time predictions  
- Handles multiple scheme labels accurately  
- Visual outputs and performance metrics  
- End-to-end reproducible using IBM Cloud Lite  

---

## 🚀 How It Works

1. Upload PMGSY dataset to IBM Cloud Object Storage  
2. Clean and encode features in Watson Studio Notebook  
3. Train model using IBM Watson AutoAI  
4. Deploy best model using Watson Machine Learning  
5. Use REST API for project classification  

---

## 🖼️ Screenshots

🔹 Dataset in Cloud Object Storage  
<img width="1919" height="926" alt="Storage" src="https://github.com/user-attachments/assets/8753dfb6-9646-4cd6-ab29-b70012a516ee" />

🔹 Notebook Data Preprocessing 
<img width="1919" height="927" alt="Notebook - 1" src="https://github.com/user-attachments/assets/b54847bc-2978-45d8-b437-f6bd4fdc3e6a" />

🔹 Deployment via Watson Machine Learning 
<img width="1919" height="930" alt="Deployment" src="https://github.com/user-attachments/assets/7e3d72ea-59fb-440d-9e72-51c43490021b" />

🔹 Model created for refinement
<img width="1919" height="929" alt="Auto AI - Model" src="https://github.com/user-attachments/assets/9e7c0fcb-35ef-4119-8a49-094cbfdbe20b" />



---

## 📌 How to Run or Deploy

1. Login to IBM Cloud Lite: [https://cloud.ibm.com](https://cloud.ibm.com)  
2. Launch Watsonx.ai Studio  
3. Upload project dataset to Cloud Object Storage  
4. Open Notebook for preprocessing  
5. Use AutoAI to train and rank models  
6. Deploy top model via Watson Machine Learning  
7. Test API with project data input

---

## 🛣️ Future Scope

- Expand to other government programs (e.g., Smart Cities)  
- Use terrain/weather data for smarter classification  
- Integrate with dashboards or mobile apps  
- Add multilingual support for rural field officers  
- Automate monthly classification reports  

---

## 🔗 Useful Links

- [IBM Watsonx.ai](https://www.ibm.com/cloud/watsonx)  
- [IBM Cloud Lite](https://cloud.ibm.com)  
- [AI Kosh Dataset Portal](https://data.gov.in)  
- [IBM SkillsBuild](https://skillsbuild.org)  

---

## ⚖️ License

This project is licensed under the MIT License.  
Created with ❤️ during the IBM SkillsBuild for Academia Internship 2025 by **Vrishabh Jawa** – Galgotias University, CSE (Data Science).
Let’s connect! 👉 linkedin.com/in/vrishabh-jawa
