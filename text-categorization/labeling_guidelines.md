# Text Categorization Labeling Guidelines

## 📌 Purpose

This document defines the rules followed while labeling categories in the dataset.

The goal is to ensure consistency, clarity, and reproducibility of annotation.

---

## 🏷 Category Labels Definition

### 1️⃣ Sports

Definition:  
Text about sports events, teams, players, tournaments, or scores.

Examples:
- "The cricket team won the Asia Cup final."  
- "The basketball championship attracted global audiences."

Indicators:
- Sports terminology  
- Event names  
- Scores or results  

---

### 2️⃣ Politics

Definition:  
Text related to government, policies, legislation, political figures, or diplomatic events.

Examples:
- "Parliament debated the new cybersecurity law."  
- "The president met foreign diplomats to discuss trade."

Indicators:
- Political institutions or figures  
- Policy announcements  
- Legislative discussions  

---

### 3️⃣ Technology

Definition:  
Text about technological products, software, hardware, research, or innovation.

Examples:
- "Google launched a new AI-powered search feature."  
- "Researchers developed a new quantum computing chip."

Indicators:
- Tech company names  
- Product releases  
- Research or innovation news  

---

### 4️⃣ Entertainment

Definition:  
Text about movies, TV shows, music, celebrities, or cultural events.

Examples:
- "The movie broke box office records worldwide."  
- "The singer announced a world tour next month."

Indicators:
- Films, songs, or series  
- Celebrity news  
- Cultural or artistic events  

---

### 5️⃣ Health

Definition:  
Text related to medical updates, health advisories, or wellness topics.

Examples:
- "Doctors warned about rising cases of dengue fever."  
- "A new vaccine has been approved for children."

Indicators:
- Medical terms  
- Health alerts or advice  
- Public health information  

---

### 6️⃣ Education

Definition:  
Text related to schools, universities, academic policies, or learning activities.

Examples:
- "The university announced admissions for the new semester."  
- "The education board revised the exam syllabus."

Indicators:
- Academic announcements  
- Learning activities  
- Policy updates  

---

### 7️⃣ Finance

Definition:  
Text related to financial markets, investments, banking, or economic policies.

Examples:
- "The stock market closed at a record high today."  
- "Investors are shifting towards gold investments."

Indicators:
- Financial terms  
- Market or investment news  
- Policy announcements affecting finance  

---

### 8️⃣ Travel

Definition:  
Text about tourism, travel events, destinations, or transportation updates.

Examples:
- "Thousands of tourists visited Jaipur during the festival."  
- "Airlines reduced ticket prices for international routes."

Indicators:
- Destination names  
- Tourism activities  
- Travel updates or promotions  

---

## ⚖ Handling Ambiguous Cases

- If text could belong to multiple categories, label according to the dominant category.  
- Add explanation in COMMENT field for mixed-topic texts.  

---

## 🎯 Confidence Score Rules

0.90 – 1.00 → Clear category  
0.80 – 0.89 → Slight ambiguity  
Below 0.80 → Strong ambiguity (avoid if possible)  

---

## 📌 Annotation Principles Followed

- One primary category per text entry  
- Focus on overall topic rather than minor mentions  
- Maintain consistency across annotators  
- Use comments for complex or ambiguous cases  

---

These guidelines were used to maintain structured and reliable text categorization annotation for NLP applications.
