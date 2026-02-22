# Named Entity Recognition (NER) Labeling Guidelines

## 📌 Purpose

This document defines the rules followed while labeling entities in the dataset.

The goal is to ensure consistency, clarity, and reproducibility of annotation.

---

## 🏷 Entity Labels Definition

### 1️⃣ Person

Definition:  
Any named individual (real or fictional).

Examples:
- "Sundar Pichai"  
- "Albert Einstein"  

Indicators:
- Names of people
- First name + Last name combinations

---

### 2️⃣ Organization

Definition:  
Any named organization, company, institution, or group.

Examples:
- "Google"  
- "UNICEF"  

Indicators:
- Official company names  
- Educational institutions  
- NGOs or government bodies

---

### 3️⃣ Location

Definition:  
Named geographical locations (cities, countries, landmarks).

Examples:
- "Jaipur"  
- "Mount Everest"  

Indicators:
- Cities, states, countries  
- Natural or man-made landmarks

---

### 4️⃣ Date & Time

Definition:  
Any reference to a specific date, time, or period.

Examples:
- "July 10, 2020"  
- "next Monday"  
- "3 PM"  

Indicators:
- Calendar dates  
- Specific time references  
- Relative temporal expressions

---

### 5️⃣ Money

Definition:  
Monetary amounts, currency references, financial figures.

Examples:
- "$2 billion"  
- "INR 5000"  

Indicators:
- Currency symbols or abbreviations  
- Numeric monetary values

---

### 6️⃣ Product

Definition:  
Any named product, device, or software.

Examples:
- "iPhone 14"  
- "Windows 11"  

Indicators:
- Brand + product name  
- Software or physical goods

---

### 7️⃣ Event

Definition:  
Named events, festivals, conferences, competitions, or programs.

Examples:
- "Asia Cup"  
- "Tech Summit 2023"  

Indicators:
- Named competitions or tournaments  
- Conferences or exhibitions  

---

## ⚖ Handling Ambiguous Cases

- If text contains multiple entities, label each one separately.  
- If unsure about entity type, add explanation in COMMENT field.  
- Avoid mislabeling similar categories (e.g., Organization vs Event).  

---

## 🎯 Confidence Score Rules

0.90 – 1.00 → Clear entity  
0.80 – 0.89 → Slight ambiguity  
Below 0.80 → Strong ambiguity (avoid if possible)  

---

## 📌 Annotation Principles Followed

- One entity type per labeled mention  
- Capture exact span of the entity  
- Maintain consistency across annotators  
- Add comments for complex or ambiguous cases  

---

These guidelines were used to maintain structured and reliable NER annotation for NLP and AI applications.
