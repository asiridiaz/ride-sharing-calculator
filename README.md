# Ride Sharing Calculator - Microservice

## Overview

This project involved the development of a ride-sharing calculator for a leading ride-hailing service in Sri Lanka. The calculator was designed to process ride-sharing transactions, calculate discounts, and manage commissions for drivers and discounts for passengers. The solution was implemented as a PHP script, leveraging MySQL for database interactions and integrating with external services for notifications and transaction processing.

## Technical Details

### Core Functionality

- **Database Interaction**: The script interacts with a MySQL database to fetch ride-sharing transaction data, calculate discounts, and manage commissions. It utilizes prepared SQL statements to ensure secure and efficient database operations.
- **Transaction Processing**: The calculator processes transactions based on predefined criteria, such as trip status, booking method, and taxi model. It calculates discounts and commissions based on the duration of the ride and the driver's commission rate.
- **Notification System**: The script includes functionality to send push notifications to passengers, informing them of their discounts. This is achieved through integration with an external notification service.
- **Logging and Monitoring**: The script logs detailed information about each transaction, including discount calculations, commission rebates, and notification outcomes. This data is crucial for monitoring the system's performance and troubleshooting issues.

### Implementation Highlights

- **Dynamic SQL Queries**: The script dynamically constructs SQL queries based on the current ride-sharing service types and discount thresholds. This approach allows for flexibility and scalability as the service evolves.
- **Error Handling**: Robust error handling mechanisms are in place to manage database connection failures and SQL query errors. This ensures the reliability of the system and provides clear feedback in case of issues.
- **Performance Optimization**: The script is optimized for performance, with a maximum execution to accommodate large datasets. This ensures that the ride-sharing calculator can process transactions efficiently, even under heavy load.

### Integration with External Services

- **Chat Group Notifications**: The script integrates with Slack/GoogleChat/Teams chat groups to send real-time updates on ride-sharing transactions. This feature enhances communication and transparency within the organization.
- **External Notification Service**: The calculator uses an external service to send push notifications to passengers. This integration ensures timely and accurate communication about discounts and commissions.

## Conclusion

The Ride Sharing Calculator is a comprehensive solution that streamlines the management of ride-sharing transactions, discounts, and commissions. By leveraging PHP, MySQL, and external services, the calculator provides a robust and scalable system that meets the needs of a leading ride-hailing service in Sri Lanka. This project showcases my ability to develop complex, data-driven applications and integrate them with external systems to enhance operational efficiency and customer satisfaction.
