![Alt text](https://github.com/latleger/LHL-Project-Final/blob/main/images/image-1.png)


# Demand Forecasting and Inventory Optimization (Road Map)

## Introduction
[City Cyclery](http://citycyclery.ca/), a local bike shop in Windsor, Ontario, Canada, is dedicated to revolutionizing its operations through cutting-edge Demand Forecasting, Inventory Optimization, and Automation. In pursuit of excellence, City Cyclery has successfully developed a robust Demand Forecasting model and is now working diligently to fine-tune its accuracy and validation processes. This transformative initiative aims to ensure optimal stock levels while minimizing costs and enhancing customer satisfaction.

**The model uses real data provided by City Cyclery.**

## Problem Statement
City Cyclery's business is highly seasonal, experiencing fluctuations in demand based on factors such as weather and seasonality. The challenge is to accurately predict customer demand and optimize inventory levels to meet this demand while minimizing carrying costs.

## Exploratory Data Analysis (EDA)
The "EDA_Results" folder contains detailed exploratory data analysis results. These insights are crucial for understanding historical sales patterns and seasonality affecting demand.

## Demand Forecasting Model Refinement

### Current Status
City Cyclery has achieved a significant milestone by developing a Demand Forecasting model leveraging advanced time series techniques. This model is designed to predict future demand by analyzing historical sales data and uncovering critical patterns and seasonality.

### Next Steps
- Fine-Tuning: Devote efforts to fine-tuning the Demand Forecasting model to enhance its accuracy and predictive capabilities.
- Validation Process: Rigorously validate the model's performance by comparing its predictions with actual sales data, ensuring reliable forecasts.

## Challenges
After using Prophet and SARIMA time series models, the dataset does correlate the hypothieze significant seaonsality of the business. Since there is seasonality and randomness within this dataset, at this point, it has been difficult to evaluate the model successfully. However, I believe, if I look at other factors, such as the weather, neighborhood events, etc., I should be able to fine-tune the results in the future.

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
