![Logo](https://github.com/latleger/LHL-Project-Final/blob/main/images/image-1.png)


# Demand Forecasting and Inventory Optimization (Road Map)

## Introduction
[City Cyclery](http://citycyclery.ca/), a local bike shop in Windsor, Ontario, Canada, is dedicated to revolutionizing its operations through cutting-edge Demand Forecasting, Inventory Optimization, and Automation. In pursuit of excellence, City Cyclery has successfully developed a robust Demand Forecasting model and is now working diligently to fine-tune its accuracy and validation processes. This transformative initiative aims to ensure optimal stock levels while minimizing costs and enhancing customer satisfaction.<br>

![homepage](https://github.com/latleger/LHL-Project-Final/blob/main/images/home_page.png)<br>

**The model uses real data provided by City Cyclery.**

## Problem Statement
City Cyclery's business is highly seasonal, experiencing fluctuations in demand based on factors such as weather and seasonality. The challenge is to accurately predict customer demand and optimize inventory levels to meet this demand while minimizing carrying costs. We are also attempting to forecast quantities one week in advance. Reducing the purchasing from daily to once a week.


## Exploratory Data Analysis (EDA)
The ["EDA_Results"](https://github.com/latleger/LHL-Project-Final/tree/main/EDAs) folder contains detailed exploratory data analysis results. These insights are crucial for understanding historical sales patterns and seasonality affecting demand.

## Demand Forecasting Model Refinement

### Current Status
City Cyclery has achieved a significant milestone by developing a Demand Forecasting model leveraging advanced time series techniques. This model is designed to predict future demand by analyzing historical sales data and uncovering critical patterns and seasonality.

### Next Steps
- Fine-Tuning: Devote efforts to fine-tuning the Demand Forecasting model to enhance its accuracy and predictive capabilities.
- Validation Process: Rigorously validate the model's performance by comparing its predictions with actual sales data, ensuring reliable forecasts.

## Challenges and Results:
Upon employing [Prophet](https://github.com/latleger/LHL-Project-Final/tree/main/notebooks/SARIMA_model) and [SARIMA](https://github.com/latleger/LHL-Project-Final/tree/main/notebooks/prophet_model) time series models, the dataset indeed reveals a notable presence of seasonality as hypothesized for the business. Yet, owing to the inherent dataset randomness, the successful evaluation of the model has posed challenges. Nevertheless, I am optimistic that by considering additional factors such as weather patterns and local events, I can refine and enhance the outcomes in future iterations.

## Predictions and Model Evaluation:
![Results](https://github.com/latleger/LHL-Project-Final/blob/main/images/results.png)
Following thorough model assessments, our initial assumption leaned towards the SARIMA model for its potential in offering more pragmatic predictions, aligning with our evaluation findings. However, upon juxtaposing the forecasted quantities with actual sales in the subsequent week, the Prophet model emerged as the victor, demonstrating heightened accuracy and accounting for the shop's closure periods. To further validate these findings, additional prediction rounds are imperative.

## Raod Map
![Road Map](https://github.com/latleger/LHL-Project-Final/blob/main/images/roadmap.png)

## Inventory Management

### Importance of Effective Inventory Management
City Cyclery recognizes that maintaining an optimal inventory level is pivotal for meeting customer demand while minimizing excess stock and associated costs.

### Key Steps
1. Safety Stock and Reorder Point Optimization: Determine the appropriate safety stock levels and reorder points based on demand forecasts and lead times.
2. Order Quantity Management: Utilize the Economic Order Quantity (EOQ) model to calculate the optimal order quantities, striking a balance between cost efficiency and demand fulfillment.
3. Dynamic Adjustment: Implement a system for real-time adjustment of inventory levels based on changing demand patterns and unexpected events.

## API Integration and Automation

### API Creation and Email Integration
- API Development: Design and implement an API capable of receiving input data, such as current stock levels and sales forecasts, and generating comprehensive order details.
- Email Functionality: Integrate email functionality using a reliable email service API (e.g., SendGrid, Mailgun) to seamlessly dispatch order details to the purchasing team.

### Automation for Streamlined Operations
- Scheduled Forecasting: Configure scheduled tasks or cron jobs to execute the Demand Forecasting and order generation process on a weekly basis.
- Automated Order Generation: Establish an automated process triggered by the scheduled task, allowing the Demand Forecasting model to generate predictions and detailed order information based on the most recent data.
- Email Alerts: Enable the API to automatically send email notifications containing predicted order details to the purchasing team, expediting the order placement process.

## Monitoring and Alerts

### Performance Monitoring
- Develop a comprehensive monitoring system to track the performance of both the Demand Forecasting model and the automation process, ensuring smooth operation.

### Alert Mechanisms
- Implement proactive alert mechanisms to promptly notify relevant personnel in case of errors, anomalies, or unexpected behavior during forecasting, inventory management, or automation.

## Security Considerations
- API Security: Ensure secure and authenticated access to the API to prevent unauthorized usage and protect sensitive data.
- Email Security: Implement proper authentication and encryption for the email functionality to maintain data security.

## Deployment and Ongoing Maintenance

### Production Deployment
- Transition the automated system from development to a production environment, ensuring accessibility and reliability for the purchasing team.

### Continuous Maintenance
- Establish a routine maintenance schedule to update and refine the Demand Forecasting model, API, and automation components. This ongoing effort ensures accuracy, relevance, and operational excellence.

Stay tuned as City Cyclery continues its journey toward optimal inventory management, streamlined operations, and exceptional customer service. To learn more about City Cyclery and its offerings, please visit [City Cyclery](http://citycyclery.ca/). Get ready to embark on a new era of cycling convenience and satisfaction!
