## Customer Churn Analysis

**Overview of the Dataset**
-   The dataset consists of **7,043 customer records** from a telecom company.
-   It includes details like **customer demographics, services opted for, contract type, billing method, and churn status**.
-   The target variable is **`Churn`**, which is **"Yes" for churned customers and "No" for retained customers**.

**Key Findings from the Analysis**
#### **1️⃣ Churn Rate & General Trends**

📌 **Overall churn rate is around 26.5%**, meaning **1 in 4 customers** leave the company.  
📌 **Senior citizens churn more** than younger customers, likely due to **pricing or service needs**.

#### **2️⃣ Tenure vs. Churn**

📌 Customers with a **tenure of less than 3 months** have the **highest churn rate**.  
📌 Long-term customers (**tenure > 50 months**) rarely churn.

#### **3️⃣ Contract Type Impact**

📌 **Month-to-month contracts** have the **highest churn rate (~43%)**.  
📌 **Annual contracts** show much lower churn (~11%), indicating that **long-term commitment helps retention**.

#### **4️⃣ Payment Method & Churn**

📌 Customers using **Electronic Check** as a payment method churn **more than other methods**.  
📌 **Bank transfers and credit card users** have a **much lower churn rate**, likely due to auto-payments.

#### **5️⃣ Service Usage & Churn**

📌 Customers with **Fiber Optic Internet** are **more likely to churn** than DSL users, possibly due to **higher costs**.  
📌 Customers **without Tech Support or Online Security** tend to **churn at a higher rate**.


**Business Recommendations**

✅ **Encourage Long-Term Contracts**: Offer **discounts on annual plans** to reduce churn from **month-to-month** subscribers.

✅ **Improve Retention of New Customers**: Focus on **tenure < 3 months** by offering **welcome discounts** or **early engagement programs**.  

✅ **Introduce Auto-Payment Discounts**: Since **electronic check users churn the most**, **incentivizing credit card or bank transfer payments** can help.  

✅ **Targeted Offers for Fiber Optic Customers**: Since fiber users churn more, offering **better pricing, bundling with other services, or premium support** might help.  

✅ **Enhance Support Services**: Customers who **opt out of Tech Support & Security services** churn more—offering **free trials** or **discounted packages** can help retain them.
