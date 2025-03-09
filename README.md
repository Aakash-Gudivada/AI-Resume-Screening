# RecruitEdge – Smart Resume Screening & AI-Matched Candidate Shortlisting

RecruitEdge is an AI-powered resume screening tool that ranks resumes based on their relevance to a given job description. It uses **TF-IDF Vectorization** and **Cosine Similarity** to compare resumes against the job description and rank them accordingly.

## 🚀 Features
- 📄 **Extract text from PDF resumes** using `PyPDF2`
- 🎯 **Rank resumes** based on job description relevance
- 📊 **Interactive ranking display** using Streamlit
- ⚡ **Fast and efficient** AI-based resume screening
- 🏆 **Helps recruiters** shortlist the best candidates instantly

---
## 🛠 Tech Stack
- **Python**
- **Streamlit** (for UI)
- **PyPDF2** (for extracting text from PDFs)
- **Scikit-learn** (for NLP processing and similarity measurement)
- **Pandas** (for data handling)

---
## 📌 How It Works
1. 📝 **Enter the job description** in the text box.
2. 📄 **Upload multiple resumes** in PDF format.
3. ⚙️ **AI ranks the resumes** based on relevance to the job description.
4. 📊 **View the ranking** in an interactive table.

---
## 🚀 Installation & Setup
### 1️⃣ Clone the repository
```sh
git clone https://github.com/your-username/recruitedge.git
cd recruitedge
```

### 2️⃣ Install dependencies
```sh
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit App
```sh
streamlit run app.py
```

---
## 🛂 Generating `requirements.txt`
To create a `requirements.txt` file with all necessary dependencies, run:
```sh
pip freeze > requirements.txt
```
This will save all installed dependencies in a file that can be used for easy installation.

---
## 📦 Dependencies
Ensure you have the following Python libraries installed:
```sh
pip install streamlit PyPDF2 scikit-learn pandas
```

