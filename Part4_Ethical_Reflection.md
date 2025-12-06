# Part 4: Ethical Reflection

## Personal Project: Movie Recommendation System

**Reflection:**
In a previous project where I built a movie recommendation engine, I focused primarily on accuracy (RMSE). Reflecting on this through an ethical lens, I realize I neglected potential biases. For example, the dataset might have been skewed towards Western, English-language films, implicitly filtering out diverse cultural content for users.

**Future Ethical Adherence:**
To ensure my future projects adhere to ethical AI principles, I will implement the following:

1.  **Data Auditing (Justice):** Before training, I will audit my datasets for representation. If I am building a recommender, I will check the distribution of content across genres, languages, and regions to ensure I am not creating a "filter bubble."
2.  **User Control (Autonomy):** I will add features that allow users to reset their profile or explicitly exclude certain data points from being used (e.g., "Don't use my watch history from 2020").
3.  **Transparency:** I will implement a "Why this recommendation?" feature. Instead of just showing a movie poster, the UI will state, "Recommended because you watched *Inception* and enjoy *Sci-Fi Thrillers*."
4.  **Privacy (Non-maleficence):** I will practice data minimization. Instead of storing raw user logs indefinitely, I will aggregate data where possible and implement retention policies to delete old data that is no longer needed for the model.
