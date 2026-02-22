# Intent Classification Labeling Guidelines

## 📌 Purpose

This document defines the rules followed while labeling intents in the dataset.

The goal is to ensure consistency, clarity, and reproducibility of annotation.

---

## 🏷 Intent Labels Definition

### 1️⃣ Information Request

Definition:  
Text where the user asks for information or clarification.

Examples:
- "What is your refund policy?"  
- "Can you tell me the store timings?"  

Indicators:
- Questions seeking details
- Requests for explanations or instructions

---

### 2️⃣ Complaint

Definition:  
Text expressing dissatisfaction or problems with a product or service.

Examples:
- "My order has not arrived yet."  
- "The app keeps crashing every time I open it."  

Indicators:
- Expressions of dissatisfaction  
- Problem reporting  
- Negative experience description

---

### 3️⃣ Feedback

Definition:  
Text giving opinions, suggestions, or evaluations.

Examples:
- "The new interface looks great."  
- "It would be better if the app allowed dark mode."  

Indicators:
- Suggestions  
- Comments on experience  
- Recommendations

---

### 4️⃣ Purchase Intent

Definition:  
Text expressing intent to buy or inquire about purchasing.

Examples:
- "I want to buy this laptop."  
- "Do you have this product in stock?"  

Indicators:
- Action-oriented intent to purchase  
- Product inquiry or order intent

---

### 5️⃣ Threat

Definition:  
Text that contains threatening or harmful intent toward someone or something.

Examples:
- "I will make sure you regret this!"  
- "If this continues, there will be consequences."  

Indicators:
- Threatening language  
- Harm or intimidation

---

### 6️⃣ Greeting

Definition:  
Text that serves to greet or welcome.

Examples:
- "Hello!"  
- "Good morning, team."  

Indicators:
- Salutations  
- Polite opening phrases

---

### 7️⃣ Spam

Definition:  
Unsolicited, irrelevant, or promotional messages.

Examples:
- "Buy cheap watches now at xyz.com!"  
- "Click this link to win a free phone!"  

Indicators:
- Advertising links  
- Repeated promotions  
- Irrelevant or unwanted content

---

## ⚖ Handling Ambiguous Cases

- If a sentence could belong to multiple intents, label according to dominant intent.  
- If unsure, add explanation in COMMENT field.  
- Avoid labeling harmful content as Greeting or Feedback.  

---

## 🎯 Confidence Score Rules

0.90 – 1.00 → Clear intent  
0.80 – 0.89 → Slight ambiguity  
Below 0.80 → Strong ambiguity (avoid if possible)  

---

## 📌 Annotation Principles Followed

- One primary intent per text entry  
- Focus on overall purpose of the text  
- Maintain consistency across annotators  
- Add comments for complex or multi-intent cases  

---

These guidelines were used to maintain structured and reliable intent annotation for NLP and AI applications.
