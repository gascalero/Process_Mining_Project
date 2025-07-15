This project explored **process mining** techniques, using the Celonis platform, to help **WoodCorp Inc.**, a fictional German wood manufacturing company, improve how they handle orders and deliveries. WoodCorp, which makes pellets and crates, often struggled to meet promised delivery dates, which hurt their reputation. Our main goal was to understand their **Order-to-Cash (O2C) process** better and find ways to make it more efficient. This project was designed to build a strong case for WoodCorp to consider investing in the Celonis platform.

Here's how we approached it and what we found:

### **Our Approach**
We analyzed real event data from WoodCorp’s system, specifically two main datasets:
*   The **Activity Table (event log)**: This showed the sequence of events for each sales order, including when each activity happened. This helped us visualize the actual process flow.
*   The **Case Table**: This contained details about each order, like delivery dates, product types, factories, customer markets, and order values. This was used to measure performance and understand different parts of the business.

We used several key features within the Celonis platform:
*   **Process Explorer**: To visually map out the process steps as they actually happened and spot where things weren't working well.
*   **Conformance Checker**: To compare the actual process against the "Happy Path" (the ideal way the process should run) and highlight any differences or problems.
*   **OLAP Tables**: For looking at data from different angles, like by product type, factory, or customer.
*   **Action Flows**: To demonstrate how the system could automatically send alerts or notifications, such as for late deliveries.

### **What We Discovered (Key Findings)**
Our analysis revealed some significant issues within WoodCorp's O2C process:
*   **A big problem with missed deadlines**: **Over 40% of orders were outside acceptable tolerance limits**, meaning frequent delays or major inefficiencies.
*   **Many orders didn't follow the plan**: About **6,800 cases didn't follow the ideal process**. These issues were often due to **changes in quantity (4,641 cases), price (3,903 cases), or delivery date (3,701 cases)**.
    *   Out of these problematic cases, **55% didn't meet the expected product delivery tolerance**, and **12% were delivered after the promised date**.
*   **Problems were concentrated**: **Almost all (98.8%) of the issues came from just three factories: Aachen, Essen, and Crefeld**.
    *   **Aachen** was the biggest factory for deliveries, but also had the **widest range of tolerance issues**.
*   **'Crates' were a major concern**: The **'Crates' product type was involved in 57% of problematic cases**, even though it only made up 39% of all orders. This product consistently showed higher volumes and more tolerance problems.
*   **Specific customer segments and activities caused issues**:
    *   The **Construction market segment** contributed to **16% of non-conformances**.
    *   Frequent **changes to order quantity, price, and delivery dates** were major reasons for deviations, often leading to financial losses and delays.
    *   Certain customers (like Kirchner, Fritz, Wiegand, Jurgens, Steinbach, Meibner, and Adam KG) were linked to a large number of these problems.
*   **Financial impact**: These process issues could lead to a **potential financial loss of up to €2.8 million** if customers returned excess goods.
*   **Late deliveries were common**: **12% of problematic cases resulted in late deliveries**, with an average delay of **9 days**.
*   **Process AI confirmed findings**: An additional analysis using Artificial Intelligence validated our findings, showing that **only 13% of all cases actually followed the ideal "happy path"**.

### **Our Solutions & Proposed Value**
We developed interactive dashboards and showed how automated actions could bring value to WoodCorp:
*   **Dashboards**: Provided clear overviews of sales orders and delivery performance, showing key numbers, market trends, and performance by country.
*   **Process Overview & Happy Path**: We mapped out the complete O2C process, highlighting the most common and ideal sequence of steps for all orders.
*   **Automated Action Flows**: We designed two examples to show how automation could help:
    *   One automatically sends a **summary report for sales orders that have already been invoiced** to the right teams.
    *   Another acts as a **"High Risk Order Alert"**, notifying teams about orders that are likely to cause problems (e.g., from the problematic factories, 'Crates' product type, Construction market, or orders with changes to quantity, price, or delivery date).

These solutions aim to **improve coordination, ensure orders can be tracked, automate routine reports, allow for early intervention in unstable orders, and ultimately reduce risks and customer complaints** for WoodCorp. This project successfully demonstrated how **process mining can help optimize real-world processes, identify key deviations, and provide useful insights for better performance**.

### **Next Steps**
While our analysis was comprehensive, it was based on past data, which might not capture every real-time factor. For the future, we suggest:
*   A more detailed look into the root causes of problems at the **Aachen, Essen, and Crefeld plants**.
*   Further analysis of the "Change production start date" activity, which affects 88% of cases, to understand its impact on delivery times.
*   Including more data, like customer feedback or supplier performance, to get a full picture.
*   A thorough cost-benefit analysis of implementing automated action flows on a larger scale.
