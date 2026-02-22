# Text Moderation Labeling Guidelines

## 📌 Purpose

This document defines the rules followed while labeling moderation categories in the dataset.

The goal is to ensure consistency, clarity, and reproducibility of annotation.

---

## 🏷 Moderation Labels Definition

### 1️⃣ Safe

Definition:  
Text that is appropriate, non-offensive, and poses no risk.

Examples:
- "Looking forward to our team meeting tomorrow."  
- "Happy birthday to you!"  

Indicators:
- Positive or neutral content
- No offensive language

---

### 2️⃣ Spam

Definition:  
Unsolicited, irrelevant, or repetitive messages intended to advertise or annoy.

Examples:
- "Buy cheap products now at xyz.com"  
- "Click here to win a free iPhone!"  

Indicators:
- Advertising links  
- Repeated promotions  
- Irrelevant content  

---

### 3️⃣ Abusive

Definition:  
Content that insults, threatens, or attacks someone personally.

Examples:
- "You are a complete idiot!"  
- "I hate your guts!"  

Indicators:
- Profanity  
- Personal attacks  
- Harassment  

---

### 4️⃣ Violence

Definition:  
Text describing or encouraging physical harm or violent acts.

Examples:
- "I will hurt him if he comes here."  
- "Massive fights broke out at the protest."  

Indicators:
- Threats of violence  
- Graphic violent descriptions  

---

### 5️⃣ Hate Speech

Definition:  
Content attacking a group or individual based on race, religion, gender, or identity.

Examples:
- "All [group] are worthless."  
- "Hate everyone from [country]."  

Indicators:
- Discrimination  
- Intolerance  
- Derogatory slurs  

---

### 6️⃣ Sarcastic

Definition:  
Text that uses irony or sarcasm, often meaning the opposite of literal words.

Examples:
- "Oh great, another Monday, just what I needed."  
- "Yeah, that went really well… not."  

Indicators:
- Tone contrast between words and intended meaning  
- Use of punctuation or phrasing for irony  

---

## ⚖ Handling Ambiguous Cases

- If text could belong to multiple categories, label according to dominant category.  
- If unsure, add explanation in COMMENT field.  
- Avoid labeling unsafe content as Safe.  

---

## 🎯 Confidence Score Rules

0.90 – 1.00 → Clear category  
0.80 – 0.89 → Slight ambiguity  
Below 0.80 → Strong ambiguity (avoid if possible)  

---

## 📌 Annotation Principles Followed

- One moderation label per text entry  
- Focus on context, not single words only  
- Maintain consistency across annotators  
- Add comments for any complex cases  

---

These guidelines were used to maintain structured and reliable moderation annotation for NLP applications.
