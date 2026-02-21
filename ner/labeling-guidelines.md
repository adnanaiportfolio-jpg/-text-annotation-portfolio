# Named Entity Recognition (NER) Labeling Guidelines

This document defines the entity categories used in this NER annotation project.

---

## 1. PERSON
Names of individuals (real or fictional).

Examples:
- Steve Jobs
- Virat Kohli
- Elon Musk

---

## 2. LOCATION
Geographical places such as cities, countries, landmarks.

Examples:
- New Delhi
- India
- Seattle
- Eiffel Tower

---

## 3. ORGANIZATION
Names of companies, institutions, brands, or agencies.

Examples:
- Google
- Microsoft
- United Nations
- Apple

---

## 4. DATE
Specific dates or calendar references.

Examples:
- 15 August 2025
- January 1, 2024
- 10/12/2023

---

## 5. TIME
Specific time references.

Examples:
- 10 AM
- 5:30 PM
- Midnight

---

## 6. MONEY
Monetary values or currency expressions.

Examples:
- 500 dollars
- ₹10,000
- $99

---

## Annotation Rule
- Only clearly identifiable entities should be labeled.
- Each row represents one entity extracted from the text.
- The dominant and exact entity phrase should be selected.
- Confidence score must be above 0.70.

---

## Confidence Score
Confidence reflects clarity and correctness of entity recognition.
