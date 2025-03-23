## 📩 Smart Email Assistant – AI-Powered Email Management

An AI-driven email assistant built using Spring Boot & Spring AI, integrated with a Chrome Extension for seamless email automation and smart suggestions.# 📩 Smart Email Assistant – AI-Powered Email Management
**An AI-driven email assistant built using Spring Boot & Spring AI, integrated with a Chrome Extension for seamless email automation and smart suggestions.**

## 🔥 Key Features
✅ **AI-Powered Email Suggestions** – Uses **Spring AI** to generate smart email replies.  
✅ **Context-Aware Responses** – Understands email context for better automation.  
✅ **Seamless Chrome Extension** – Provides AI-powered suggestions directly inside Gmail.  
✅ **Natural Language Processing (NLP)** – AI analyzes and generates meaningful responses.  
✅ **Efficient Email Categorization** – Helps prioritize emails using AI.  
✅ **Secure & Scalable Backend** – Built using **Spring Boot, Spring AI, and REST APIs**.  

---

## 🛠️ Tech Stack
### **Backend (Spring Boot + AI)**
- **Spring Boot 3** – REST API Development  
- **Spring AI** – AI-powered email response generation  
- **OpenAI/GPT Integration** – For intelligent email drafting  
- **Spring Security** – Secure authentication  
- **MongoDB / PostgreSQL** – Email storage and retrieval  

### **Frontend (Chrome Extension)**
- **HTML, CSS, JavaScript** – Chrome extension UI  
- **Manifest v3** – Secure and modern extension development  
- **JavaScript Content Script & Background Script** – Handles AI suggestions in Gmail  

---

## 🎯 How It Works
1️⃣ The **Chrome Extension** injects an AI-powered assistant inside Gmail.  
2️⃣ When composing an email, the assistant **suggests responses** based on context.  
3️⃣ The extension **sends the email content** to the Spring Boot backend.  
4️⃣ The **Spring AI-powered backend** generates smart responses.  
5️⃣ The extension displays **AI-generated replies**, helping users craft emails faster.  

---

## 🚀 Installation & Setup  

### 🏗️ **Backend – Spring Boot AI Server**  
#### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/your-username/smart-email-assistant.git
cd smart-email-assistant
```
#### **2️⃣ Configure API Keys**  
- Set up **OpenAI API key** (or any other LLM provider).  
- Configure **Spring Boot properties** in `application.yml`:  
```yaml
spring:
  ai:
    openai:
      api-key: YOUR_OPENAI_API_KEY
```

#### **3️⃣ Run the Application**  
```bash
./mvnw spring-boot:run
```
- Backend runs on **`http://localhost:8080`**  

---

### 🏗️ **Chrome Extension – Setup & Installation**  
#### **1️⃣ Clone & Navigate to the Extension Directory**  
```bash
cd chrome-extension
```

#### **2️⃣ Load the Extension in Chrome**  
1. Open **Chrome** and go to `chrome://extensions/`  
2. Enable **Developer Mode** (toggle in the top-right).  
3. Click **"Load unpacked"** and select the `chrome-extension` folder.  

#### **3️⃣ Using the Extension**  
- Open **Gmail**.  
- Click on the **Smart Email Assistant** icon inside the compose window.  
- The AI generates suggested responses instantly! 🚀  

---

## 📝 API Endpoints (Backend)  
| Method | Endpoint | Description |  
|--------|----------|-------------|  
| `POST` | `/api/email/generate-reply` | AI-generated email reply |  
| `GET` | `/api/email/history` | Fetch past AI-generated emails |  
| `POST` | `/api/email/categorize` | AI-based email categorization |  

---

## 📷 Screenshots  
*(Add UI screenshots of the Chrome extension and AI-generated emails for better visualization.)*  

---

## 🤝 Contributing  
We welcome contributions! Fork the repo, improve features, and submit a PR.  

---

## 🛡️ License  
This project is licensed under the **MIT License**.  

---

### 🚀 Want to Enhance This Project?  
- Add **voice-to-text email dictation** 🎙️  
- Integrate with **Google Calendar** for smart scheduling 📅  
- Improve **email tone customization** (casual, formal, etc.) 🎭
