# House Price Prediction in King County, USA: A Regression Modeling Approach." 🏡📊
Exploring the heartbeat of King County's real estate! 🏡 Dive into the sales prices of homes sold between May 2014 - May 2015 with this dataset – a treasure trove of 21,614 rows and 21 variables. Access the dataset here https://www.kaggle.com/datasets/harlfoxem/housesalesprediction/data and let the data adventures begin!

Let's decipher the story behind each home sale in King County! 🏠💡 This dataset offers a glimpse into the dynamic real estate market, with a rich set of features capturing the essence of each property:

* `id`: Unique ID for each home sold
* `date`: Date of the home sale
* `price`: Sale price of each home
* `bedrooms`: Number of bedrooms
* `bathrooms`: Number of bathrooms (accounts for partial bathrooms)
* `sqft_living`: Square footage of the interior living space
* `sqft_lot`: Square footage of the land space
* `floors`: Number of floors
* `waterfront`: Dummy variable for waterfront view
* `view`: Property view index (0 to 4)
* `condition`: Property condition index (1 to 5)
* `grade`: Property grade index (1 to 13)
* `sqft_above`: Square footage above ground level
* `sqft_basement`: Square footage below ground level
* `yr_built`: Year the house was built
* `yr_renovated`: Year of the last renovation
* `zipcode`: House's zipcode
* `lat`: Latitude
* `long`: Longitude
* `sqft_living15`: Square footage of interior living space for the nearest 15 neighbors
* `sqft_lot15`: Square footage of land lots for the nearest 15 neighbors

In the dynamic landscape of business, embracing a customer-centric paradigm is no longer a choice but a strategic imperative for enhanced profitability. My journey involves transcending the conventional product-centric approach, delving into the intricate realm of factors shaping house prices in King County, USA.
This ambitious project serves a dual purpose: firstly, to construct a robust predictive model for house prices, and secondly, to unearth the underlying influences that impact the real estate market. With 21,614 rows and 21 variables, the dataset becomes the canvas for decoding the nuanced patterns.

# Objective: 
Uncover the intricate factors steering house prices, delivering invaluable insights to buyers, sellers, and stakeholders alike.

# Goals: 
Predict housing prices in King County, USA, leveraging the dataset variables. From this exploration, identify key factors shaping prices and provide strategic recommendations for model optimization and continuous improvement.

# Method and Libraries
I embarked on Exploratory Data Analysis (EDA) to unearth the depth of the dataset, unveiling patterns, and extracting valuable insights. Subsequently, I delved into modeling using Linear Regression, Random Forest, and Decision Tree, emphasizing a comparative analysis of their performances.
Moving forward, hyperparameter tuning took center stage to attain an optimal model. Model performance underwent evaluation through cross-validation, revealing the distribution of performance metrics. The standout model then took the spotlight, making predictions on the provided test data.

In this intricate dance of data, SHAP values played a pivotal role, providing nuanced explanations for model predictions. These values served as a guiding light, offering insights into feature contributions and enhancing the interpretability of the complex models.

This project relies on fundamental packages such as `numpy`, `pandas`, `matplotlib`, `seaborn`, and `sklearn`, serving as steadfast companions throughout this journey. They provide a robust foundation for in-depth data exploration and accurate modeling.

# Result
After meticulous exploration, model training, and hyperparameter tuning, the Random Forest model emerged as the top performer, surpassing both Linear Regression and Decision Tree models. The initial metrics showcase its robust predictive power:

    Base Random Forest Model:
        MSE: 16,658,919,793.42
        MAE: 69,439.09
        RMSE: 129,069.43
        R2: 0.8779

Even after hyperparameter tuning, the Random Forest model maintained its strong performance:

    Tuned Random Forest Model:
        MSE: 17,586,082,278.07
        MAE: 69,474.10
        RMSE: 129,345.47
        R2: 0.8774

Despite marginal shifts in MSE and RMSE, the consistently high R2 underscores the model's unwavering predictive capabilities. 🌐📊
