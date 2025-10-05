# Laptop Price Prediction

This project predicts laptop prices using machine learning techniques based on various features such as brand, specifications, and hardware details. The workflow includes data preprocessing, feature engineering, model training, and evaluation.

## Dataset

The dataset (`laptop_price.csv`) contains information about laptops, including:

- **Company**: Brand of the laptop
- **Product**: Model name
- **TypeName**: Type (Ultrabook, Notebook, etc.)
- **Inches**: Screen size
- **ScreenResolution**: Display resolution
- **Cpu**: Processor details
- **Ram**: RAM size
- **Memory**: Storage details
- **Gpu**: Graphics card
- **OpSys**: Operating system
- **Weight**: Laptop weight
- **Price_euros**: Price in Euros

## Methodology

1. **Data Cleaning**: Removed unnecessary columns and handled outliers using z-score.
2. **Feature Engineering**: Applied one-hot encoding to categorical features.
3. **Model Training**: Used Linear Regression with a pipeline for preprocessing and training.
4. **Evaluation**: Assessed model performance using R² score, MAE, RMSE, and cross-validation.
5. **Visualization**: Plotted predicted vs actual prices for visual inspection.

## Results

- **R² Score**: Indicates the proportion of variance explained by the model.
- **MAE**: Mean Absolute Error between predicted and actual prices.
- **RMSE**: Root Mean Squared Error for prediction accuracy.
- **Cross-validation**: Ensures model generalization.


## How to Run

1. Open `Laptop_Price_Prediction.ipynb` in Jupyter Notebook or VS Code.
2. Run all cells to execute the workflow and generate results.
3. The plot will be saved as `predicted_vs_actual.png`.

## Requirements

- Python
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

Install dependencies using:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Author

Sarvesh
