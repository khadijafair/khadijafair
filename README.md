<div align="center">

# Hi there, I'm khadija abdoune 👋
### Data & Software Engineer | MLOps & Systems Specialist

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=61AFEF&center=true&vCenter=true&width=550&width=550&lines=Data+%26+Software+Engineering;MLOps+%26+Intelligent+Automation;Backend+APIs+%26+Cloud+Systems;Telecom+%26+Network+Architecture)](https://git.io/typing-svg)

---

</div>

## 👨‍💻 About Me

- 🔭 **Focus Areas:** Building end-to-end data pipelines, microservice backends, intelligent workflow automations, and edge ML deployments.
- ⚡ **Technical Synergy:** Bridging the gap between **Software Development**, **Data/AI Engineering**, and **Network Infrastructure**.
- 🛠️ **Currently Building:** Scalable RESTful APIs, distributed automation workflows, and predictive analytics dashboards.
- 🌱 **Learning & Exploring:** Advanced MLOps pipelines, cloud-native architectures on AWS, and network QoS optimization.

---

## 🛠️ Tech Stack & Tools

### 💻 Programming Languages
[![Languages](https://skillicons.dev/icons?i=python,java,js,ts,php,cpp,dart,c,bash)](https://skillicons.dev)

### ⚙️ Backend, Web & Mobile
[![Frameworks](https://skillicons.dev/icons?i=fastapi,spring,bootstrap,react,flutter,tailwind,express,nodejs)](https://skillicons.dev)

### 📊 Data Engineering, ML & Analytics
[![Data Stack](https://skillicons.dev/icons?i=postgres,mysql,sqlite,supabase,tensorflow,matlab,powerbi)](https://skillicons.dev)
> **Data & ML Tools:** `dbt` • `Prophet` • `TensorFlow Lite` • `TensorFlow.js` • `Scikit-Learn` • `Pandas` • `NumPy`

### ☁️ Cloud, DevOps & Networking
[![Cloud & Tools](https://skillicons.dev/icons?i=docker,aws,gns3,linux,postman,git,github,n8n)](https://skillicons.dev)
> **Networking Tools:** `Wireshark` • `3CX IP-PBX` • `QGIS` • `Radio Mobile` • `iPerf`

---

## 🚀 Featured Projects

<div align="center">

| Project | Domain | Stack |
| :--- | :--- | :--- |
| **[n8n OrderFlow](#1-n8n-orderflow--intelligent-e-commerce-automation)** | Automation & Backend | `n8n` `Docker` `PostgreSQL` `Supabase` `Twilio` |
| **[Demand Forecasting Pipeline](#2-demand-forecasting--data-engineering-pipeline)** | Data Engineering & AI | `dbt` `PostgreSQL` `Prophet` `Power BI` |
| **[RESTful URL Shortener API](#3-restful-url-shortener-api)** | Backend Microservice | `FastAPI` `SQLAlchemy` `Pydantic` `pytest` |
| **[Pneumonia Detection & Edge ML](#4-pneumonia-detection--edge-ml-deployment)** | Deep Learning & Edge | `TensorFlow` `TFLite` `Android` `TF.js` |
| **[VoIP & Telecom Infrastructure](#5-voip-infrastructure--telecom-qos-evaluation)** | Telecom & Networking | `3CX` `SIP/RTP` `GNS3` `Wireshark` |
| **[Sentinel Spam & Phishing Detector](#6-sentinel-spam--phishing-detector)** | ML & Security | `FastAPI` `Scikit-Learn` `Streamlit` `Ollama` |
| **[Sanaye3i — Artisans Marketplace](#7-sanaye3i--mobile-service-marketplace)** | Cross-Platform Mobile | `React Native` `Expo` `Firebase` |
| **[Enterprise HR & Leave System](#8-enterprise-hr--leave-management-platform)** | Backend Web | `Spring Boot` `Java EE` `MySQL` `Spring Security` |
| **[2G/3G/4G Propagation Optimization](#9-2g3g4g-radio-propagation--coverage-optimization)** | Radio Telecom & GIS | `Radio Mobile` `QGIS` `Octave` |
| **[SmartApp Real-Time Vision](#10-smartapp--real-time-camera-object-detection)** | Mobile AI / Vision | `Android Studio` `Java` `TensorFlow Lite` |

</div>

<br/>

### 1. n8n OrderFlow — Intelligent E-Commerce Automation
*Automated end-to-end e-commerce order validation, inventory synchronization, payment processing, and customer notification system.*

- **Technical Breakdown:** Built a resilient webhook-driven workflow utilizing `n8n` in Docker. Handles transaction validation, integrates PostgreSQL/Supabase for real-time state management, and triggers automated SMS/email alerts via Twilio and PayPal webhooks. Tested across 200+ simulated orders.
- **Tech Stack:**
  ![n8n](https://img.shields.io/badge/n8n-FF6C37?style=flat-square&logo=n8n&logoColor=white)
  ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
  ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
  ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
  ![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white)
  ![PayPal API](https://img.shields.io/badge/PayPal_API-003087?style=flat-square&logo=paypal&logoColor=white)
- 🔗 **[Repository](https://github.com/khadijafair/n8n-orderflow)** | **[Live Demo / Workflow Diagram](https://github.com/khadijafair/n8n-orderflow#demo)**

---

### 2. Demand Forecasting & Data Engineering Pipeline
*Complete analytics engineering platform transforming raw data into predictive business intelligence.*

- **Technical Breakdown:** Architected modular dbt staging layers and data marts over a PostgreSQL warehouse. Leveraged Facebook Prophet for weekly time-series demand forecasting and designed multi-page interactive Power BI dashboards for executive decision-making.
- **Tech Stack:**
  ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
  ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
  ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
  ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
- 🔗 **[Repository](https://github.com/khadijafair/demand-forecasting-pipeline)** | **[View Dashboards](https://github.com/khadijafair/demand-forecasting-pipeline#dashboards)**

---

### 3. RESTful URL Shortener API
*Enterprise-grade API service featuring custom link expiration, click metrics tracking, and high test coverage.*

- **Technical Breakdown:** Built with FastAPI and SQLAlchemy using modern asynchronous patterns. Includes custom expiration logic, SQLite database persistence, Pydantic schemas for request validation, and an automated pytest test suite for CI/CD readiness.
- **Tech Stack:**
  ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
  ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
  ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
  ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
  ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
- 🔗 **[Repository](https://github.com/khadijafair/url-shortener-api)** | **[API Docs](https://github.com/khadijafair/url-shortener-api#documentation)**

---

### 4. Pneumonia Detection & Edge ML Deployment
*Binary CNN image classifier and cross-platform mobile/edge deployment pipeline.*

- **Technical Breakdown:** Trained a Convolutional Neural Network achieving **>90% accuracy** on chest X-ray scans. Exported optimized weights via TensorFlow Lite (TFLite) and TensorFlow.js for low-latency, offline inference on native Android (Java/XML) and web interfaces.
- **Tech Stack:**
  ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
  ![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
  ![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
  ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white)
  ![TensorFlow.js](https://img.shields.io/badge/TensorFlow.js-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
- 🔗 **[Repository](https://github.com/khadijafair/pneumonia-detection-edge)** | **[Live Demo](https://github.com/khadijafair/pneumonia-detection-edge#demo)**

---

### 5. VoIP Infrastructure & Telecom QoS Evaluation
*Enterprise communication architecture and quality-of-service simulation under variable traffic loads.*

- **Technical Breakdown:** Deployed a full 3CX IP-PBX system with PoE switching, SIP/RTP routing, and Wireshark packet analysis. Conducted benchmark simulations evaluating IntServ, DiffServ, and MPLS paradigms in GNS3 to mitigate latency and bandwidth bottlenecks.
- **Tech Stack:**
  ![3CX](https://img.shields.io/badge/3CX-00B2E3?style=flat-square&logo=3cx&logoColor=white)
  ![GNS3](https://img.shields.io/badge/GNS3-2E3842?style=flat-square&logo=gns3&logoColor=white)
  ![Wireshark](https://img.shields.io/badge/Wireshark-167EC1?style=flat-square&logo=wireshark&logoColor=white)
  ![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=flat-square&logo=cisco&logoColor=white)
- 🔗 **[Repository](https://github.com/khadijafair/telecom-voip-qos)** | **[Architecture Report](https://github.com/khadijafair/telecom-voip-qos#report)**

---

### 6. Sentinel Spam & Phishing Detector
*Hybrid message classification system combining classical ML algorithms with local LLM verification.*

- **Technical Breakdown:** Built a multi-stage classification pipeline using TF-IDF vectorization and Linear SVM served through FastAPI and Streamlit. Features a secondary verification layer powered by local LLM models (Ollama) and dynamic active-feedback retraining loops.
- **Tech Stack:**
  ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
  ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
  ![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
  ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
  ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
- 🔗 **[Repository](https://github.com/khadijafair/sentinel-spam-detector)** | **[Live Demo](https://github.com/khadijafair/sentinel-spam-detector#demo)**

---

### 7. Sanaye3i — Mobile Service Marketplace
*Cross-platform mobile application connecting users with local service providers and home artisans.*

- **Technical Breakdown:** Designed and built cross-platform mobile interfaces using React Native and Expo. Integrates Firebase authentication, real-time Firestore synchronization for service booking updates, and cloud messaging for instant notifications.
- **Tech Stack:**
  ![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
  ![Expo](https://img.shields.io/badge/Expo-000000?style=flat-square&logo=expo&logoColor=white)
  ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
- 🔗 **[Repository](https://github.com/khadijafair/sanaye3i-app)** | **[App Preview](https://github.com/khadijafair/sanaye3i-app#preview)**

---

### 8. Enterprise HR & Leave Management Platform
*Robust Java backend web application for tracking corporate leave requests, user roles, and operational workflows.*

- **Technical Breakdown:** Developed a modular Spring Boot architecture utilizing Spring Data JPA/Hibernate for MySQL transactions. Configured Spring Security for role-based authorization (Employee vs. HR Manager) and implemented audit logs for request tracking.
- **Tech Stack:**
  ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
  ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white)
  ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
  ![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
- 🔗 **[Repository](https://github.com/khadijafair/hr-leave-management)** | **[Documentation](https://github.com/khadijafair/hr-leave-management#docs)**

---

### 9. 2G/3G/4G Radio Propagation & Coverage Optimization
*Geospatial cellular coverage modeling and signal quality optimization over real terrain environments.*

- **Technical Breakdown:** Simulated base station (eNB) site placements, sector orientations, and propagation losses using Radio Mobile and QGIS. Designed custom Octave scripts to evaluate RSRP distributions and Cumulative Distribution Function (CDF) metrics across 2G, 3G, and 4G bands.
- **Tech Stack:**
  ![QGIS](https://img.shields.io/badge/QGIS-589632?style=flat-square&logo=qgis&logoColor=white)
  ![GNU Octave](https://img.shields.io/badge/GNU_Octave-079104?style=flat-square&logo=gnuoctave&logoColor=white)
  ![Telecommunications](https://img.shields.io/badge/Telecom-Radio_Mobile-blue?style=flat-square)
- 🔗 **[Repository](https://github.com/khadijafair/radio-propagation-optimization)** | **[Simulation Report](https://github.com/khadijafair/radio-propagation-optimization#report)**

---

### 10. SmartApp — Real-Time Camera Object Detection
*Native mobile computer vision app carrying out real-time object detection via device camera streams.*

- **Technical Breakdown:** Integrated pre-trained TensorFlow object recognition models into a native Android architecture using Java and XML layouts. Optimized frame processing loops to deliver low-latency real-time inference directly on edge device hardware.
- **Tech Stack:**
  ![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
  ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white)
  ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
  ![TensorFlow Lite](https://img.shields.io/badge/TFLite-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
- 🔗 **[Repository](https://github.com/khadijafair/smartapp-object-detection)** | **[Demo Video](https://github.com/khadijafair/smartapp-object-detection#demo)**

---

## 📫 Connect & Socials

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/khadijaabdoune)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)]
(mailto:abdounekhadija833@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-121011?style=for-the-badge&logo=react&logoColor=61DAFB)](https://yourportfolio.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/khadijafair)

<br/>

<sub><i>"Building scalable software, engineering data, and optimizing network intelligence."</i></sub>

</div>
