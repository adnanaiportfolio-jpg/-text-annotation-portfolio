# Intent Classification Labeling Guidelines

This document defines the intent categories used in this project for text annotation.

---

## 1. Information_Request
Text where the user is asking for information, clarification, or details.

Examples:
- What is the price of this product?
- Can you tell me your working hours?
- How does this service work?

---

## 2. Complaint
Text expressing dissatisfaction, frustration, or negative experience with a product or service.

Examples:
- I am not happy with the service.
- My order arrived damaged.
- This is the worst experience I’ve had.

---

## 3. Feedback
Text where the user is giving suggestions, opinions, or general feedback (positive or neutral).

Examples:
- The app interface is very user-friendly.
- You should improve the delivery time.
- Overall, it was a good experience.

---

## 4. Purchase_Intent
Text showing clear intention to buy, subscribe, or place an order.

Examples:
- I want to buy this product.
- How can I subscribe to this plan?
- I would like to place an order.

---

## 5. Threat
Text containing warning, aggressive tone, or legal/serious escalation.

Examples:
- I will take legal action.
- I will report this issue.
- Fix this immediately or face consequences.

---

## 6. Greeting
Text used for greetings, polite openings, or basic conversation starters.

Examples:
- Hello
- Good morning
- Hi there

---

## 7. Spam
Promotional, irrelevant, suspicious, or repetitive marketing content.

Examples:
- Buy now and earn money fast!
- Click this link to win a prize.
- Limited time offer, act now!

---

## Confidence Score
All annotations include a confidence score above 0.70 based on clarity of intent and context.

---

## Annotation Rule
Each text must be assigned only one primary intent label based on dominant user intention.
