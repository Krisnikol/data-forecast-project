# data-forecast-project
Data Forecast Project – Python + Excel data analysis and forecasting
# Time Series Sales Analysis with Python

This project focuses on analyzing historical sales data and building a simple time series forecast using Python.  
It demonstrates essential data analysis skills, including data cleaning, trend analysis, visualization, and forecasting.

---

## 📊 Objective
The goal of this project is to explore and analyze sales trends over time and build a predictive model to estimate future sales.  
This project simulates a real business case where forecasting helps improve planning and decision-making.

---

## 🧾 Dataset
- Format: Excel file (`.xlsx`)
- Content: Monthly sales data
- Source: Training dataset from own practice
- Data Size: Small – ideal for educational/business case study

---

## 🔧 Tools & Technologies
| Tool / Library      | Purpose                         |
|---------------------|----------------------------------|
| Python              | Programming language            |
| Pandas              | Data loading & cleaning         |
| NumPy               | Numerical computation           |
| Matplotlib / Plot   | Trend visualization             |
| Google Colab        | Code execution environment      |

---

## Project Steps
1. **Import data from Excel into Python**
2. **Clean and preprocess the dataset**
   - Handle missing values
   - Fix formatting issues
3. **Explore the data**
   - Calculate total and average sales
   - Identify trends and fluctuations
4. **Visualize sales trends over time**
5. **Build a simple forecasting model**
   - Using moving average / linear trend
6. **Interpret results**

---

## 📈 Visualization Example
Example: Trend line chart showing sales over time

```python
plt.plot(df['Date'], df['Sales'])
plt.title("Sales Trend Over Time")
plt.xlabel("Date")
plt.ylabel("Sales")
plt.show()

🔗 **Google Colab Notebook:**  
👉 [Click here to view analysis](https://colab.research.google.com/drive/18Cm7FyfO9r4rSbjSGrvQFVtlAMDTizeC?usp=sharing)



 

 
