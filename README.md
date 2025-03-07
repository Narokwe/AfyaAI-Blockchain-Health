# AfyaAI - AI, Blockchain, and DeFi for Decentralized Healthcare  

AfyaAI is a **Decentralized Science (DeSci)** project revolutionizing healthcare by integrating **AI, blockchain, and DeFi** to improve access, ownership, and financial empowerment. The platform allows individuals to securely store and manage their health records on the blockchain, ensuring **privacy and ownership** while leveraging AI-powered disease risk assessment models. By participating in health monitoring, users earn **Afya tokens**, incentivizing preventive healthcare behaviors.  

Additionally, AfyaAI integrates **DeFi mechanisms**, enabling users to stake their tokens in a **smart contract-based health risk pool** that grows through high-interest rates. These tokens can be used for healthcare payments, reducing financial barriers to medical access. Healthcare providers are also rewarded with Afya tokens for **granting patients access to data** and **maintaining high service quality**.  

## 🚀 Features  
- 🔐 **Blockchain-Based Health Data Storage** – Users own and control their medical records.  
- 🤖 **AI-Powered Disease Risk Assessment** – Predicts risks for **cancer, HIV/AIDS, diabetes, tuberculosis, and more**.  
- 💰 **Afya Token Incentives** – Earn Afya tokens by participating in health monitoring and risk assessment.  
- 🏦 **DeFi Staking for Healthcare Payments** – Users stake tokens in a health risk pool with high returns.  
- 🏥 **Healthcare Provider Rewards** – Providers earn tokens for ensuring **quality services and data transparency**.  
- ☁️ **Deployed on Railway** – Fast, scalable cloud deployment.  

## 📂 Project Structure  
AFYAAI APP/ │── instance/ # Contains the SQLite database file │── venv/ # Virtual environment (not included in GitHub) │── Afyaai.py # Main Flask application │── requirements.txt # Dependencies │── Procfile # Deployment configuration for Railway │── README.md # Project documentation


## 🔧 Installation & Setup  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/your-username/AfyaAI-Blockchain-Health.git
cd AfyaAI-Blockchain-Health

2️⃣ Set Up a Virtual Environment
python -m venv venv
venv\Scripts\activate   # On Windows
source venv/bin/activate  # On Mac/Linux

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run the Application Locally
python Afyaai.py
The API will run at http://127.0.0.1:5000/

🌍 Deployment on Railway
Push your code to GitHub.
Connect your GitHub repository to Railway.
Add environment variables if needed.
Deploy and get your API URL!

📖 API Endpoints
Endpoint	Method	Description
/register	POST	Register a new user
/login	POST	User login, returns JWT token
/submit_data	POST	Submit health data (Authenticated)
/stake_tokens	POST	Stake Afya tokens (Authenticated)
🛠 Built With
Flask
Flask-SQLAlchemy
JWT (PyJWT)
Gunicorn
Blockchain & DeFi Integration
AI Risk Assessment Models
Railway Deployment

🤝 Contributing
We welcome contributions! To contribute:

Fork the repository.
Create a feature branch.
Submit a pull request with detailed changes.

📜 License
MIT License - You are free to use and modify.

🚀 Developed by Augustine Narokwe
