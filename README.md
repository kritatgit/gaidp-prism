# 🚀 Project Name

## 📌 Table of Contents
- [Introduction](#introduction)
- [Demo](#demo)
- [Inspiration](#inspiration)
- [What It Does](#what-it-does)
- [How We Built It](#how-we-built-it)
- [Challenges We Faced](#challenges-we-faced)
- [How to Run](#how-to-run)
- [Tech Stack](#tech-stack)
- [Team](#team)

---

## 🎯 Introduction
We have developed an intelligent Data Profiling Agent that automates data validation in the banking sector, ensuring compliance with regulatory standards set by organizations like the Federal Reserve. Our solution efficiently processes large datasets, identifying regulatory violations, assessing risk scores, detecting anomalies, and providing record-specific remediation actions. This streamlines compliance, enhances data integrity, and mitigates financial risks for banks.

## 🎥 Demo
🔗 [Live Demo](#) (if applicable)  
📹 [Video Demo](#) (if applicable)  
🖼️ Screenshots:

![Screenshot 1](link-to-image)

## 💡 Inspiration
Validating is traditionally done manually and is a very time taking process. Moreover, investigating the cause for failed validation requires high level of skill and expertise.
Generative AI has proven its abilities to be useful in any level of complexity  of task and we thought why not leverage GenAI to reduce effort of the mountain of a task!
## Architecture Diagram:

## ⚙️ What It Does
Functionalities:<br>
->Interprets data validation rules extracted from the federal reserve document and auto generates validation scripts.<br>
->Allows users to customise, refine or add rules as per requirement via an interactive chat interface.<br>
->The chatbot acts as an SME in the banking regulations.Our chatbot is expertised to Corporate Loan Regulations and can even clarify doubts of users.<br>
->Provides risk scoring and anomaly detection  to provide deeper understanding of customer patterns.<br>
->Provides a comprehensive report containing all findings and remediation actions for further investigation.<br>
->Facilitates downloading the report in a readable pdf format for single records or entire user data as per need.<br>
->Close ended application which prevents misuse of GENAI capabilities other than intended use.


## 🛠️ How We Built It
The application uses the following tools and technologies:<br>
->Python libraries (e.g. pdfplumber,tabula,reportlab) to perform extraction and conversion operations on pdfs.<br>
->Data processing libraries such as pandas,numpy to perform dataframe operations.<br>
->Gemini 1.5 pro LLM model for content and script generation tasks.<br>
->Prompt engineering techniques to customise the LLM context to generate accurate validations as script and providing remediations.<br>
->Isolation Forest unsupervised model for pattern and anomaly detection.<br>
->Streamlit framework for seemless UI and integration to the pipeline.<br>


## 🚧 Challenges We Faced
Processing the bulky federeral reserve documents to accurately extract rules was challenging.<br>
Since the model is accessed via API keys and they have fixed RPM and usage limits recurssive testing of the application was challenging.<br>
## 🏃 How to Run
1. Clone the repository  
   ```sh
   git clone https://github.com/your-repo.git
   ```
2. Install dependencies  
   ```sh
   pip install -r requirements.txt
   ```
3. Run the project  : Navigate to the src folder and enter the command below:
   ```sh
   streamlit run app.py
   ```

## 🏗️ Tech Stack
- 🔹 Frontend: Streamlit
- 🔹 Backend: Python script
- 🔹 Database: csv/excel files, text files
- 🔹 LLM: Google Gemini 1.5-pro

## 👥 Team
- **Dishita Mohan* - [GitHub](https://github.com/dishitamohan) | [LinkedIn]()
- **Krithika Ramachandran** - [GitHub](https://github.com/kritatgit) | [LinkedIn](www.linkedin.com/in/krithika-ramachandran-42a1471b1)
