# Enhancing Data Literacy and Model Explainability

Welcome to the official repository for the technical workshop, **"Enhancing Data Literacy and Model Explainability through Bayesian Statistics"**, presented at **DjangoCon Africa 2025**.

This workshop explores the crucial intersection of data literacy, model explainability, and the Bayesian approach to statistical thinking. The goal is to empower data practitioners to not only build accurate models but also to understand and communicate the "why" behind their predictions.

---

## 🏛️ About the Workshop

In today's data-driven world, being able to "speak data" is a fundamental skill. This session dives into:
- **Statistical Thinking:** The foundational mindset for interpreting data correctly.
- **Explainable AI (XAI):** Techniques to peek inside the "black box" of machine learning models.
- **Bayesian Statistics:** A powerful framework for reasoning under uncertainty and building more transparent models.
- **Practical Demonstration:** A hands-on walkthrough of creating and interpreting Partial Dependence Plots (PDPs) and Individual Conditional Expectation (ICE) plots using Python and scikit-learn.

---

## 📂 Repository Contents

This repository contains all the materials from the workshop:

-   `slides/`: The presentation slides (`Enhancing Data Literacy and Model Explainability.pdf`).
-   `demo/`: A Jupyter Notebook (`1_Partial_Dependence_Plots.ipynb`) with the hands-on code demo.
-   `README.md`: This file, providing an overview and instructions.
-   `requirements.txt`: A list of Python packages needed to run the demo.

---

## 🚀 Getting Started

To run the demo on your local machine, please follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/mwanyumba7/model-explainability-through-bayesian-statistics-workshop
    cd Data-Literacy-and-Explainable-AI-Workshop
    ```

2.  **Set up a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Launch Jupyter Notebook and open the demo file:**
    ```bash
    jupyter notebook demo/1_Partial_Dependence_Plots.ipynb
    ```

---

## 🏆 Takeaway Assignment

Ready to put your new skills to the test and win some swag? Complete one of the assignments below using the Titanic dataset and share your notebook via a Pull Request. The best submissions will win a GitHub T-shirt!

### 🔰 Beginner-Friendly Assignment

**Objective:** Create and interpret your first Partial Dependence Plots.

1.  **Load & Prep:** Load the Titanic dataset and prepare it for modeling (handle missing values, encode categorical features).
2.  **Train:** Build a `RandomForestClassifier` to predict survival.
3.  **Plot:** Generate 1D PDPs for the `age`, `fare`, and `pclass` features.
4.  **Interpret:** For each plot, write a short paragraph explaining what it shows about the feature's relationship with survival probability.

### 🚀 Advanced Assignment

**Objective:** Discover and explain feature interactions using 2D Partial Dependence Plots.

1.  **Build on Beginner:** Complete the beginner steps, but use a `GradientBoostingClassifier`.
2.  **Go Deeper with 1D:** Generate 1D PDPs for `age` and `fare`, but also include the Individual Conditional Expectation (ICE) lines to see individual trends.
3.  **Uncover Interactions:** Create a **2D Partial Dependence Plot** for an interacting feature pair (e.g., `age` and `pclass`).
4.  **Analyze & Explain:** Write a detailed analysis of your 2D plot. Explain the interaction: How does the effect of one feature change based on the value of the other? What does the variation in your ICE plots tell you?

---

## 📚 Additional Resources

-   **Books:**
    -   [Practical Statistics for Data Scientists](https://www.oreilly.com/library/view/practical-statistics-for/9781492072935/)
    -   [An Introduction to Statistical Learning](https://www.statlearning.com/)
    -   [Interpretable Machine Learning by Christoph Molnar](https://christophm.github.io/interpretable-ml-book/)
-   **Python Packages:**
    -   [scikit-learn Inspection Module (PDPs)](https://scikit-learn.org/stable/modules/partial_dependence.html)
    -   [ArviZ](https://arviz-devs.github.io/arviz/): Exploratory analysis of Bayesian models.
    -   [PyMC](https://www.pymc.io/welcome.html): A flexible library for Bayesian modeling.

---

## 👨‍🏫 Presenter

-   **Brayan Kai Mwanyumba**
-   [LinkedIn]( https://www.linkedin.com/in/brayan-mwanyumba-309498227 )
-   [Twitter](https://x.com/Kai_mwanyumba)
-   [GitHub](https://github.com/mwanyumba7)

---

## 📜 License

This project is licensed under the MIT License - see the `LICENSE` file for details.