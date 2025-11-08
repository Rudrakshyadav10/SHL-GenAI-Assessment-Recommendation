# 🧠 SHL GenAI Assessment Recommendation Engine  
### by **Rudraksh Yadav**

This project was developed as part of the **SHL Research Intern Assignment (November 2025)**.  
It demonstrates the application of Generative AI for automating the process of recommending SHL assessments based on job descriptions.

---

## 🎯 Objective  
To build an AI-driven system that analyzes job descriptions and recommends the most relevant SHL assessments — balancing technical, cognitive, and behavioral evaluation needs.  
This solution aims to make SHL’s recommendation process faster, more intelligent, and context-aware.

---

## ⚙️ Approach  
The solution uses **Generative AI** combined with **Retrieval-Augmented Generation (RAG)** logic to map job requirements to SHL’s product catalogue.  

**System Flow:**
1. Takes job descriptions as natural language input.  
2. Extracts key skills, attributes, and behavioral cues.  
3. Matches them with SHL’s catalogue of assessments.  
4. Returns 5–10 most relevant assessments with reasoning.  

The final recommendations were generated for the 9 unlabelled test queries provided in the dataset.

---

## 📂 Files Included  
| `predictions.csv` | Recommended assessments for each job description (unlabelled test set) |
| `2_page_report.pdf` | Detailed explanation of the project, dataset, and methodology |


---

## 🌐 Live App  
Access the deployed web application here:  
👉 [**SHL Assessment Recommendation Engine**]- (https://shl-intern.vercel.app/) 

The app allows users to input a job description and view the top 5–10 SHL assessments suited for that role.

---

## 🧩 Tech Stack  
- **Generative AI** (LLM-based reasoning)  
- **RAG (Retrieval-Augmented Generation)** for context mapping  
- **Vercel Deployment** for public web hosting  
- **GitHub** for version control and documentation  

---

## 📈 Results  
The engine successfully generated accurate and diverse assessment recommendations for all 9 job descriptions in the dataset, covering:
- **Technical Skills** – e.g., Verify Programming Test, SQL  
- **Cognitive Ability** – e.g., Verify Cognitive Ability  
- **Behavioral Traits** – e.g., Work Styles Questionnaire  

Example Output:  
> **Input:** “Looking to hire mid-level professionals proficient in Python, SQL, and JavaScript.”  
> **Output:** Verify Programming Test, Verify Cognitive Ability, Work Styles Questionnaire  

---

## 🚀 Future Enhancements  
- Add scoring and ranking for confidence-based recommendations  
- Enable filtering by duration or role type  
- Fine-tune a domain-specific LLM for improved precision  
- Batch upload for multiple job descriptions  

---


**Rudraksh Yadav**  

---

⭐ *Developed for the SHL Research Intern Hiring Challenge — Generative AI Assessment Recommendation System.*
