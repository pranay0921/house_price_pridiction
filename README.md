#  Housing Price Predictor

A web-based machine learning application to predict house prices in
India based on user-provided inputs such as median income, house age,
number of rooms, and region. The model is trained on a mock Indian
housing dataset and outputs prices in INR.

## 🛠 Features

-   Simplified input form (Median Income, House Age, Rooms, Region)
-   Automatic defaults for missing fields
-   Outputs house price in INR
-   REST API endpoint for prediction
-   Uses Flask + scikit-learn

## ⚡ Installation & Setup

    pip install -r requirements.txt
    python model.py
    python app.py

Visit: http://127.0.0.1:5000/

## 📝 API Example

### Request:

``` json
{
  "MedInc": 8,
  "HouseAge": 10,
  "AveRooms": 5,
  "Region": "South"
}
```

### Response:

``` json
{
  "Predicted_House_Value_INR": 420000
}
```

## 📝 Example Inputs & Outputs

  Income (Lakh)   Age   Rooms   Region   Output (INR)
  --------------- ----- ------- -------- --------------
  8               10    5       South    4,20,000
  15              5     6       West     9,50,000
  4               20    3       North    2,10,000


