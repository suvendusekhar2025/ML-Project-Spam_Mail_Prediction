Spam mail prediction
Here's a well-structured description of your project:  

---

### **Spam Mail Prediction Using Machine Learning**  

#### **Project Overview**  
This project focuses on predicting whether an email is spam or ham using a machine learning approach. A dataset containing **5,572 emails** with **two columns** (message text and category) in CSV format was used. The model is trained to classify emails based on their textual content, providing an automated way to filter spam emails.  

#### **Technologies & Dependencies Used**  
- **Libraries:** NumPy, Pandas, Scikit-Learn  
- **Machine Learning Model:** Logistic Regression  
- **Preprocessing Techniques:** Label Encoding, TF-IDF Vectorization  
- **Model Evaluation Metrics:** Accuracy Score  

#### **Data Preprocessing & Feature Engineering**  
1. **Label Encoding:** The categorical values in the dataset were converted into numerical values, where:
   - 0: represents **ham (legitimate email)**
   - 1: represents **spam (unwanted email)**  

2. **Text Vectorization:**  
   - The email text data was transformed into numerical features using **TF-IDF Vectorization** (Term Frequency-Inverse Document Frequency).  
   - This converts the text into a format that the Logistic Regression model can process effectively.  

#### **Model Selection & Training**  
- The dataset was split into **training and testing sets** using the (train_test_split) function from Scikit-Learn.  
- A **Logistic Regression model** was trained to classify emails as spam or ham.  
- The **accuracy score** achieved:  
  - **Training Data:** **96.7%**  
  - **Test Data:** **96.59%**  

#### **Conclusion**  
The Logistic Regression model performed efficiently with an accuracy of over **96%** on both training and test data. The use of **TF-IDF Vectorization** helped in extracting meaningful features from the text, and **Label Encoding** ensured proper numerical representation of categorical data. This project successfully demonstrates how machine learning can be used to automate email spam detection with high accuracy.  

---

