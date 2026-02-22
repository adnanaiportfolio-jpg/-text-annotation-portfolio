# Sentiment Annotation Labeling Guidelines

## 📌 Purpose

This document defines the rules followed while labeling sentiment in the dataset.

The goal is to ensure consistency, clarity, and reproducibility of annotation.

---

## 🏷 Sentiment Labels Definition

### 1️⃣ Positive

Definition:
Text expresses happiness, satisfaction, appreciation, excitement, or approval.

Examples:
- "The service was excellent."
- "I really loved the experience."
- "The product quality is amazing."

Indicators:
- Positive adjectives (great, amazing, wonderful)
- Praise or appreciation
- Expressions of satisfaction

---

### 2️⃣ Negative

Definition:
Text expresses dissatisfaction, criticism, frustration, or negative emotion.

Examples:
- "The delivery was delayed."
- "I am disappointed with the service."
- "This is the worst experience ever."

Indicators:
- Negative adjectives (bad, terrible, disappointing)
- Complaints
- Expressions of anger or frustration

---

### 3️⃣ Neutral

Definition:
Text is factual, informational, or does not express clear emotion.

Examples:
- "The event starts at 5 PM."
- "The company released its annual report."
- "The meeting was held yesterday."

Indicators:
- Informational tone
- No emotional words
- Balanced statements

---

## ⚖ Handling Ambiguous Cases

If a sentence contains mixed sentiment:
- Determine dominant emotional tone.
- If unclear, label as Neutral.
- Add explanation in COMMENT field.

Example:
"The product is good but delivery was slow."
→ Label: Neutral (Mixed sentiment, no dominant tone)

---

## 🎯 Confidence Score Rules

0.90 – 1.00 → Clear sentiment  
0.80 – 0.89 → Slight ambiguity  
Below 0.80 → Strong ambiguity (avoid if possible)

---

## 📌 Annotation Principles Followed

- One sentiment per sentence
- Focus on overall tone, not individual words
- Avoid personal bias
- Maintain labeling consistency

---

These guidelines were used to maintain structured and reliable sentiment annotation.
