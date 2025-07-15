This project used **process mining with the Celonis platform** to help **WoodCorp Inc.**, a fictional German wood manufacturer, improve its **Order-to-Cash (O2C) process**. WoodCorp faced challenges in **meeting promised delivery dates** and needed to understand its O2C process better. The goal was to build a business case for WoodCorp to consider investing in Celonis.

### **Our Approach**
We analyzed real data from WoodCorp's ERP system, including activity sequences (event logs) and order details. We used Celonis features like:
*   **Process Explorer** to visualize actual process flows.
*   **Conformance Checker** to compare actual processes to the ideal "Happy Path".
*   **OLAP Tables** for multi-dimensional analysis.
*   **Action Flows** to demonstrate automation.

### **Key Findings**
Our analysis revealed significant issues in WoodCorp's O2C process:
*   A major concern was that **40.59% of orders were outside tolerance limits**, indicating frequent delays and inefficiencies.
*   Approximately **6,800 orders did not follow the ideal process**. These issues were often due to **changes in quantity, price, or delivery dates**.
    *   **55% of these problematic cases didn't meet product delivery tolerance**, and **12% were delivered late**.
*   **Almost all (98.8%) of these problems originated from just three factories: Aachen, Essen, and Crefeld**.
*   The **'Crates' product type was involved in 57% of problematic cases**, despite being only 39% of total orders.
*   The **potential financial impact from customers returning out-of-tolerance goods could be up to €2.8 million**.
*   A **Process AI analysis** further confirmed that **only 13% of all cases followed the ideal "happy path"**.

### **Solutions & Proposed Value**
We developed dashboards and automated actions to provide tangible business value:
*   **Dashboards** offered comprehensive views of sales orders and delivery performance.
*   Two **Action Flows** were designed to showcase automation:
    *   One automatically sends **summary reports for invoiced sales orders**.
    *   Another acts as a **"High Risk Order Alert"**, notifying teams about orders from problematic factories, 'Crates' product type, Construction market, or those with quantity, price, or delivery date changes.

These solutions aim to **improve coordination, ensure traceability, automate reporting, encourage early intervention for unstable orders, and reduce operational risk and customer complaints** for WoodCorp Inc..

### **Conclusion**
This project effectively showed the power of process mining in **optimizing real-world processes** and **generating actionable insights** for WoodCorp. While the analysis was based on historical data, it highlighted clear areas for improvement and laid the groundwork for future, more detailed investigations into root causes and the impact of specific activities like "Change production start date".
### **Next Steps**
While our analysis was comprehensive, it was based on past data, which might not capture every real-time factor. For the future, we suggest:
*   A more detailed look into the root causes of problems at the **Aachen, Essen, and Crefeld plants**.
*   Further analysis of the "Change production start date" activity, which affects 88% of cases, to understand its impact on delivery times.
*   Including more data, like customer feedback or supplier performance, to get a full picture.
*   A thorough cost-benefit analysis of implementing automated action flows on a larger scale.
