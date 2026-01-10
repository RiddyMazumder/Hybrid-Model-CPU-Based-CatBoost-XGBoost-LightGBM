<p align="center">
  <a href="https://www.kaggle.com">
    <img src="https://img.shields.io/badge/Kaggle-blue?logo=kaggle" alt="Kaggle" />
  </a>
  <a href="https://www.python.org/">
    <img src="https://img.shields.io/badge/Python-3.11-yellow?logo=python&logoColor=white" alt="Python" />
  </a>
  <a href="https://jupyter.org/">
    <img src="https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter" alt="Notebook" />
  </a>
<a href="https://colab.research.google.com/">
  <img src="https://img.shields.io/badge/Google%20Colab-Open%20Notebook-orange?logo=googlecolab&logoColor=white" alt="Google Colab" />
</a>
</p>

# 🔗 Hybrid Model (CPU-Based): CatBoost + XGBoost + LightGBM

## 👤 Author

| 👤 **Name** | 🔗 **Github-Profile** | 🔗 **Kaggle-Profile** |
|------------|----------------|----------------|
| Riddy Mazumder | [![GitHub](https://img.shields.io/badge/GitHub-RiddyMazumder-black?logo=github)](https://github.com/RiddyMazumder) | [![Kaggle Profile](https://img.shields.io/badge/Kaggle-RiddyMazumder-blue?logo=kaggle)](https://www.kaggle.com/riddymazumder) |
| Atahar08 | [![GitHub](https://img.shields.io/badge/GitHub-Atahar08-black?logo=github)](https://github.com/Atahar08) | [![Kaggle Profile](https://img.shields.io/badge/Kaggle-Atahar08-blue?logo=kaggle)](https://www.kaggle.com/Atahar08) |

This project uses a CPU-optimized hybrid ensemble model that combines the strengths of CatBoost, XGBoost, and LightGBM to achieve strong performance on medium-scale tabular datasets within Kaggle’s CPU constraints.

Instead of relying on a single algorithm, predictions from multiple gradient-boosting models are combined to improve generalization and stability.
# ⚙️ Why a CPU-Based Hybrid Model?

Kaggle notebooks often run on CPU-only environments, making GPU-heavy solutions impractical. This hybrid approach is designed to:

✅ Work efficiently on CPU

✅ Reduce overfitting through model diversity

✅ Capture different data patterns

✅ Improve leaderboard stability

🧩 Model Components
1️⃣ CatBoost (CPU)2️⃣ XGBoost (CPU)3️⃣ LightGBM (CPU)🔄 Ensemble Strategy

# Final Prediction Formula
 
````
 Final_Prediction/y_hat = (y_CatBoost + y_XGBoost + y_LightGBM) / 3
````
>This approach:
>
>Smooths individual model errors,
>Improves robustness on unseen data,
>Increases public and private leaderboard consistency.
# 🏆 Why This Hybrid Works Well on Kaggle
| Advantage                   | Benefit                               |
| --------------------------- | ------------------------------------- |
| Model Diversity             | Captures varied feature relationships |
| CPU Optimization            | Runs within Kaggle CPU limits         |
| Reduced Overfitting         | Ensemble effect                       |
| Minimal Feature Engineering | Especially with CatBoost              |
# 📊 Recommended Use Cases

Medium-scale tabular datasets

Mixed numerical + categorical features

Kaggle competitions with CPU restrictions

Regression and Classification tasks
# 🚀 Key Takeaway

A CPU-based hybrid ensemble of CatBoost, XGBoost, and LightGBM delivers near-GPU-level performance while remaining fully compatible with Kaggle’s CPU environment.
# 📖 References
| Resource               | Link                                                                                                                       |
| ---------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| Kaggle Competition     | [https://www.kaggle.com/competitions/playground-series-s5e12](https://www.kaggle.com/competitions/playground-series-s5e12) |
| CatBoost Documentation | [https://catboost.ai/docs/](https://catboost.ai/docs/)                                                                     |
| LightGBM Documentation | [https://lightgbm.readthedocs.io/](https://lightgbm.readthedocs.io/)                                                       |
| Seaborn Library        | [https://seaborn.pydata.org/](https://seaborn.pydata.org/)                                                                 |
## 📄 License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute this project for educational and personal purposes.

---

## 💬 Feedback & Contributions

If you have any questions, suggestions, or improvements:

* 🐞 Open an issue
* 📤 Submit a pull request

Contributions are always welcome! 😊

---

Happy analyzing and learning! 🚀
