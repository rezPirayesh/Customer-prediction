Customer Behavior Prediction
   Predicts customer purchases using a PyTorch neural network on Kaggle’s Online Retail dataset.

   ## Overview
   - **Goal**: Predict if a customer will purchase based on spending and frequency.
   - **Tools**: PyTorch, Google Colab (GPU), Pandas, Scikit-learn.
   - **Dataset**: Kaggle’s Online Retail (~541k rows, ~4,339 customers after cleaning).
   - **Accuracy**: 81.74% (balanced with ~18.7% non-purchasers).

   ## Steps
   1. Load and clean dataset (~541k rows to ~4,339 customers).
   2. Create features (TotalSpent, PurchaseFrequency, TotalItems).
   3. Add synthetic non-purchasers (~1,000) to balance dataset (~81.3% Purchased=1).
   4. Train neural network (3-layer: 3→16→8→1, ReLU, Sigmoid).
   5. Evaluate accuracy (81.74% on test set).

   ## Usage
   - Clone the repo: `git clone https://github.com/yourusername/Customer-Prediction.git`.
   - Open `Customer_Prediction_PyTorch.ipynb` in Google Colab.
   - Upload `data.csv` from [Kaggle’s Online Retail dataset](https://www.kaggle.com/datasets/carrie1/ecommerce-data).
   - Run cells sequentially.

   ## Results
   - Achieved 81.74% test accuracy after balancing dataset.
   - Future work: Explore class weights, feature engineering, or visualizations (e.g., feature importance).

   ## Author
   Mohamadreza Pirayesh, AI & Data Science Enthusiast
   - GitHub: [rezPirayesh](https://github.com/rezPirayesh)
   - Email: rez4dev@gmail.com
            

