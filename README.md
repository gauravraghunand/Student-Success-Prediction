# **Student Success Prediction**

A regression-based model to predict student success based on academic and behavioral data.

---

## **Objectives**
- Identify critical factors influencing student success.  
- Develop a regression-based model to classify students as "successful" or "unsuccessful."  
- Predict outcomes for new or unseen students.  

**Key Result**: The model achieved an accuracy of **82%**, demonstrating strong predictive performance.

---

## **Methodology**
- **Data Cleaning**: Handled missing values and standardized numeric columns.  
- **Categorical Encoding**: Used ordinal and one-hot encoding for variables.  
- **Regression Model**: Built in Excel, focusing on statistically significant predictors.  
- **Prediction**: Used raw data as inputs, automatically standardized in the model.  

---

## **Usage Instructions**

### **Step 1: Running the Model**
1. **Open the Excel File**:  
   - Locate and open the project Excel file **“StudentPerformanceFactors.xlsx.”**  

2. **Add a New Student Record**:  
   - Add a new row to the sheet and input the raw data for the following variables:  
     - `Hours Studied`  
     - `Attendance (%)`  
     - `Sleep Hours`  
     - `Tutoring Sessions`  
     - Other relevant features (e.g., Parental Involvement, Motivation Level).  

3. **Standardize the Raw Data**:  
   - The standardized columns will automatically calculate values based on the **mean** and **standard deviation** of the original dataset.  

   **Important**:  
   - Ensure the formulas are copied into the new row by dragging the previous cell’s edge downward/upward (fill handle).  
   - This will apply the standardization formula to the new input values.  

---

### **Step 2: Interpreting Results**
- The regression model will predict the **exam score** for the new student in a separate column.  
- Use the following threshold to classify results:  
  - **Scores ≥ 70** → Successful (1)  
  - **Scores < 70** → Unsuccessful (0)  

---

## **Files in This Repository**
- **Student Success Prediction.pdf**: Full project report with detailed methodology and analysis.  
- **StudentPerformanceFactors.xlsx**: Excel file with the regression model and predictions.  
