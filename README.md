# 🚚 Food Delivery Time Analysis

## Project Overview
This data analysis project investigates the factors causing high variations in food delivery times. The goal was to identify key patterns and provide actionable insights to improve operational efficiency and customer satisfaction.

## 📊 Business Problem
- High variation in delivery times leading to customer dissatisfaction
- Difficulty in identifying critical factors affecting delivery performance
- Operational inefficiencies in delivery management

## 🎯 Objectives
- Analyze patterns and factors influencing food delivery times
- Identify critical time periods requiring special attention
- Evaluate impact of external factors (weather, traffic)
- Assess vehicle efficiency across different conditions
- Understand how distance and courier experience affect delivery performance

## 📁 Dataset Information
The dataset contains delivery information with the following key features:
- `Order_ID`, `Distance_km`, `Weather`, `Traffic_Level`
- `Time_of_Day`, `Vehicle_Type`, `Preparation_Time_min`
- `Courier_Experience_yrs`, `Delivery_Time_min` (target variable)

## 🔧 Data Processing
- **Data Cleaning**: Handled missing values using mode for categorical and median for numerical columns
- **Feature Engineering**: Created new columns including:
  - Experience level groups (Beginner, Intermediate, Expert)
  - Distance groups (0-5km, 6-10km, 11-15km, 16-20km)
  - Delivery time categories (slow, medium, fast)
  - Speed calculations and on-time rates

## 📈 Key Insights

### 🕒 Critical Time Periods
- **Morning** has the highest order volume (338 orders)
- 77% of orders concentrated in Morning-Evening periods
- **Recommendation**: Allocate 40% resources to morning, 30% evening, 20% afternoon, 10% night

### 🌦️ External Factors Impact
- **Weather**: Snowy and foggy conditions reduce speed by 15%
- **Traffic**: High traffic levels affect 30% of deliveries, reducing speed by 17%
- **Recommendation**: Implement dynamic ETA based on weather/traffic predictions

### 🚗 Vehicle Efficiency
- All vehicles show identical average speed (0.17 km/min)
- **Specialization recommended**:
  - Bike: 0-5km distances
  - Scooter: 6-15km distances  
  - Car: 16-20km distances

### 📏 Distance Impact
- Strong positive correlation between distance and delivery time
- Delivery time increases consistently with distance

### 👨‍💼 Courier Experience
- Minimal speed gap between Beginner (0.16 km/min) and Expert (0.17 km/min)
- Unbalanced order distribution: Experts handle 62% vs Intermediate 18%
- **Recommendation**: Rebalance allocation and implement mentorship programs

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Data Visualization
- Statistical Analysis
- Streamlit for interactive dashboard

## 📋 Recommendations Implemented
1. **Operational Cost Adjustment**: Real-time ETA prediction system
2. **Fleet Optimization**: Vehicle specialization by distance zones
3. **HR Development**: Balanced order allocation and accelerated training

## 📞 Contact
**Lamzahhera Berinpalla**
- LinkedIn: [Lamzahhera Berinpalla(https://www.linkedin.com/in/lamzahheraberinpalla/)]
- Email: lamzahheraberin@gmail.com
