# Part 2: Case Study Analysis

## Case 1: Biased Hiring Tool
**Scenario:** Amazon’s AI recruiting tool penalized female candidates.

### 1. Source of Bias
*   **Training Data:** The model was trained on resumes submitted to the company over a 10-year period. Since the tech industry has historically been male-dominated, the majority of "successful" resumes belonged to men. The AI learned to associate male-coded language (e.g., "executed," "captured") with success and female-coded language (e.g., "Women's Chess Club") with failure.

### 2. Proposed Fixes
1.  **Data Balancing:** Re-sample the training data to ensure an equal representation of male and female candidates, or use "Reweighing" techniques to give more weight to successful female candidates.
2.  **Feature Selection (Blindness):** Remove explicit gender indicators (names, pronouns) and proxies (e.g., "Women's College") from the input features.
3.  **Regularization/Fairness Constraints:** Train the model with a penalty term that increases if the model's False Negative Rate differs significantly between genders (Equalized Odds).

### 3. Evaluation Metrics
*   **Disparate Impact Ratio:** The ratio of the selection rate for women divided by the selection rate for men. Ideally, this should be between 0.8 and 1.25 (the "80% rule").
*   **Demographic Parity:** Ensuring that the percentage of women selected matches the percentage of women in the applicant pool.

---

## Case 2: Facial Recognition in Policing
**Scenario:** A facial recognition system misidentifies minorities at higher rates.

### 1. Ethical Risks
*   **Wrongful Arrests:** Higher false positive rates for minorities lead to innocent people being detained, interrogated, or arrested, causing trauma and loss of liberty.
*   **Privacy Violations:** Constant surveillance chills free speech and assembly rights, creating a "panopticon" effect where citizens feel constantly watched.
*   **Reinforcing Systemic Racism:** If the system is deployed more heavily in minority neighborhoods (predictive policing), it creates a feedback loop of over-policing.

### 2. Recommended Policies for Responsible Deployment
1.  **Human-in-the-Loop:** Facial recognition matches should never automatically trigger an arrest warrant. They must be treated as a "lead" that requires independent verification by a human investigator.
2.  **Public Audits:** The algorithm must be subjected to regular, independent audits by third-party experts to test for bias across different demographic groups.
3.  **Ban on Real-Time Surveillance:** Prohibit the use of real-time facial recognition on live video feeds (e.g., body cams, CCTV) to prevent mass surveillance. Restrict use to post-event investigation of serious crimes only.
