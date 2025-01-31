# 🏥 LLM-Based Healthcare Schemes Predictor  

This project fine-tunes a **Large Language Model (LLM)** to predict and retrieve information on various **Indian Government Healthcare Schemes** using publicly available datasets and sources.  

## 🚀 Features  
✅ Uses `llm.predict()` to answer healthcare-related queries  
✅ Fine-tuned on **Indian government health scheme data**  
✅ Provides **accurate and structured responses**  
✅ Uses **reliable sources** for fact-based predictions  

---

## 🔗 **Data Sources**  
The model is fine-tuned using government healthcare information from the following sources:  

- [Medical Facilities in India](https://wellnessdestinationindia.com/success-story/medical-facilities-in-india)  
- [Government Schemes for Cancer Treatment](https://www.cancerassist.in/govt-schemes-for-cancer-treatment-)  
- [National Organ Transplant Programme](https://dghs.gov.in/content/1353_3_NationalOrganTransplantProgramme.aspx)  
- [More sources](https://pmc.ncbi.nlm.nih.gov/articles/PMC7480502/)  

---

## 🛠️ **Setup & Installation**  

1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/yourusername/llm-healthcare-bot.git
cd llm-healthcare-bot
2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
3️⃣ Add API Keys (if required)

    Create a .env file and add your API keys:

API_KEY=your_openai_api_key

4️⃣ Run the Model

from your_model import llm

query = "What Healthcare Schemes are available?"
response = llm.predict(query)
print(response)
📌 Example Query & Response
Query:

llm.predict("What Healthcare Schemes are available?")

Expected Output:

1️⃣ Ayushman Bharat Yojana (ABY) - Provides financial assistance for hospitalization.  
2️⃣ Rashtriya Swasthya Bima Yojana (RSBY) - Health insurance for low-income families.  
3️⃣ National Organ Transplant Programme - Supports organ transplant patients.  
...

🖥️ Open in Google Colab

To test the model in Google Colab, click below:
🤝 Contributing

    Feel free to fork the repo and submit pull requests.
    Raise issues if you find any bugs or improvements.

📜 License

This project is licensed under MIT License.

