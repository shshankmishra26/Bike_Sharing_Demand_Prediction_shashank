# Bike_Sharing_Demand_Prediction_shashank
<h1 align="center"> Bike-sharing-demand-prediction </h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

![Screenshot (219)](https://user-images.githubusercontent.com/85070726/161031482-d62503d2-3243-4a9c-9b8c-516f383a947d.png)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
 

---

## 🗃️ Dataset Description

### 📅 Day Dataset Columns
- `instant`: Unique identifier for each record  
- `dteday`: Date of the record  
- `season`: Season of the year (1 = spring, 2 = summer, 3 = fall, 4 = winter)  
- `yr`: Year (0 = 2011, 1 = 2012)  
- `mnth`: Month (1 to 12)  
- `holiday`: Binary flag (1 = holiday, 0 = no holiday)  
- `weekday`: Day of the week (0 = Sunday)  
- `workingday`: Binary flag (1 = working day, 0 = non-working day)  
- `weathersit`: Weather condition (1 = clear, 2 = mist, 3 = light rain/snow, 4 = heavy rain/snow)  
- `temp`: Normalized temperature  
- `atemp`: Normalized feeling temperature  
- `hum`: Normalized humidity  
- `windspeed`: Normalized wind speed  
- `casual`: Count of casual bike rentals  
- `registered`: Count of registered bike rentals  
- `cnt`: Total bike rentals (casual + registered)  

### ⏰ Hour Dataset Columns
- Same columns as the **Day Dataset** with the addition of:  
  - `hr`: Hour of the day (0 to 23)  

---

## 🛠️ Dependencies
Ensure you have the following dependencies installed:
- Python 3.7 or higher  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Jupyter Notebook  
- ipykernel  
- Streamlit  

---

## ⚙️ Installation and Setup

### 🛑 Clone the Repository
```bash
git clone https://github.com/Pratik.94229/Bike-sharing-demand-prediction.git
cd Bike-sharing-demand-prediction
