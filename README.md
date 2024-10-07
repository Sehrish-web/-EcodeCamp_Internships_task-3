

# **Customer Satisfaction Analysis Dashboard**

### Overview
This repository contains a **Customer Satisfaction Analysis Dashboard** built using **Power BI**. It is designed to evaluate and monitor key performance indicators (KPIs) related to customer satisfaction and call center performance. The dashboard visualizes data, such as customer feedback, agent performance, and the speed at which customer queries are resolved.

---

## **Table of Contents**
- [Features](#features)
- [Dataset](#dataset)
- [Setup Instructions](#setup-instructions)
- [How to Use the Dashboard](#how-to-use-the-dashboard)
- [Contributing](#contributing)
- [License](#license)

---

## **Features**
- **Total Customers**: Displays the number of customers who contacted the call center.
- **Answered and Resolved Calls**: Visual representation of answered vs resolved calls.
- **Agent Performance**: Insights into agent-specific metrics, such as the number of calls answered, average customer satisfaction, and average speed of answer.
- **Customer Satisfaction Score**: A gauge that displays the overall customer satisfaction score on a scale of 1 to 5.
- **Average Speed of Answer**: A bar chart showing the average time taken by agents to respond to customer calls.
- **Filters**: Interactive filters for viewing data by agent, topic, and date range.

---

## **Dataset**
The dashboard uses two main datasets:

1. **`customer_data.csv`**: 
   - **customer_id**: Unique identifier for each customer.
   - **call_start_time**: Timestamp of when the call started.
   - **resolved_status**: Indicates if the call was resolved (Yes/No).
   - **satisfaction_score**: Customer's rating of their satisfaction (scale from 1 to 5).
   
2. **`agent_performance.csv`**: 
   - **agent_name**: Name of the call center agent.
   - **number_of_calls**: Total calls handled by the agent.
   - **avg_satisfaction_score**: Agent's average satisfaction score from customers.
   - **avg_answer_speed**: Average time in seconds to answer a call.

---

## **Setup Instructions**

## **How to Use the Dashboard**

- **Agent Filter**: Select a specific agent to see their performance in answering calls and satisfying customers.
- **Topic Filter**: Filter calls by the topic of customer queries.
- **Date Range Filter**: Adjust the date range to explore performance over specific time periods.
- **KPIs**:
  - **Average Satisfaction**: Indicates overall satisfaction on a scale of 1-5.
  - **Top Agent**: Highlights the top-performing agent based on satisfaction and resolved calls.
  - **Average Speed of Answer**: Displays the average time taken by agents to answer calls.

---

## **Contributing**
If you'd like to contribute to improving this repository, feel free to fork the project and submit a pull request with your changes. Contributions are welcome!

### Steps to Contribute:
1. Fork this repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes and commit them.
4. Submit a pull request.

---

## **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## **Contact**
- **Author**: Sehrish Saqlain  
- For any questions or suggestions, feel free to reach out via GitHub or open an issue.
