# Part 1: Theoretical Understanding

## 1. Short Answer Questions

### Q1: Define algorithmic bias and provide two examples of how it manifests in AI systems.
**Definition:** Algorithmic bias refers to systematic and repeatable errors in a computer system that create unfair outcomes, such as privileging one arbitrary group of users over others. It often stems from biased training data or flawed model assumptions.

**Examples:**
1.  **Hiring Algorithms:** An AI trained on resumes of past successful employees (mostly men) might downgrade resumes containing the word "Women's" (e.g., "Women's Chess Club"), effectively discriminating against female candidates.
2.  **Facial Recognition:** Systems trained primarily on lighter-skinned faces often have significantly higher error rates when identifying people with darker skin tones, leading to misidentification and potential wrongful arrests.

### Q2: Explain the difference between transparency and explainability in AI. Why are both important?
*   **Transparency:** Refers to the openness about the AI system's existence, data sources, and ownership. It answers "What is this system, and who built it?" (e.g., knowing that a chatbot is an AI, not a human).
*   **Explainability (XAI):** Refers to the ability to understand *how* the model arrived at a specific decision. It answers "Why did the model predict X?" (e.g., knowing a loan was denied because of "high debt-to-income ratio").

**Importance:** Both are crucial for **Trust**. Transparency ensures accountability, while explainability allows users to challenge incorrect decisions and developers to debug errors.

### Q3: How does GDPR (General Data Protection Regulation) impact AI development in the EU?
GDPR imposes strict rules on data privacy that directly affect AI:
*   **Right to Explanation:** Users have the right to meaningful information about the logic involved in automated decision-making.
*   **Data Minimization:** AI developers must only collect data that is strictly necessary for the purpose.
*   **Consent:** Explicit consent is required to process personal data, making it harder to scrape massive datasets without permission.

## 2. Ethical Principles Matching

| Principle | Definition |
| :--- | :--- |
| **B) Non-maleficence** | Ensuring AI does not harm individuals or society. |
| **C) Autonomy** | Respecting users’ right to control their data and decisions. |
| **D) Sustainability** | Designing AI to be environmentally friendly. |
| **A) Justice** | Fair distribution of AI benefits and risks. |
