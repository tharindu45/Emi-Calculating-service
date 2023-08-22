Project Microservices and API Gateway with Eureka Server
Welcome to the GitHub repository for our innovative project that combines a set of microservices and an API gateway, all orchestrated using Eureka Server. This project aims to streamline the process of loan management and eligibility assessment. Here's a breakdown of the key components:

1. EMI Calculating Service
The EMI Calculating Service allows users to efficiently calculate their Equated Monthly Installment (EMI) based on their loan details. By providing essential information such as the account number, loan amount, interest rate, loan tenure, and loan type, users can obtain an accurate EMI value.

2. Loan Validation Service
Our Loan Validation Service is designed to validate user-submitted loan requests. It meticulously examines the provided data to ensure its accuracy and completeness, helping to prevent errors and streamline the loan application process.

3. Interest Rate Service
The Interest Rate Service acts as a responsive source of information for current interest rates. Based on the user's specified loan type, this service returns the appropriate interest rate, providing users with up-to-date and accurate information.

4. Loan Eligibility Service
The Loan Eligibility Service plays a crucial role in determining whether a customer is eligible for a loan. By assessing various factors and criteria, this service helps users gauge their eligibility for obtaining a loan, contributing to informed decision-making.

5. Customer Notification Service
Our Customer Notification Service enhances user experience by delivering notifications tailored to their loan eligibility. If a customer falls within the range of eligibility, they receive valuable information about their EMI. Alternatively, if a customer is not eligible, they are provided with reasons explaining the outcome.

Technology Stack
This project leverages a cutting-edge technology stack to ensure efficiency, reliability, and seamless integration:

Spring Boot: A robust framework that simplifies the development of microservices by providing essential tools and features.
MySQL: A widely-used relational database management system, ensuring secure and structured data storage.
Spring Cloud Netflix Eureka: A service registry and discovery server that simplifies the coordination of microservices.
Selenide: A UI testing framework that facilitates automated testing of web applications.
Architecture Overview
The microservices and API gateway are orchestrated using Eureka Server, providing a centralized point of discovery and coordination. Each microservice plays a specific role in the loan management process, enhancing overall efficiency and user experience.

To understand the interactions and flow between these components, refer to the accompanying diagram that illustrates the communication pathways and highlights the assigned port numbers.


![Hackerthon Architecture Diagram drawio](https://github.com/tharindu45/Emi-Calculating-service/assets/60268092/f4a5076b-9bca-4c9d-b78b-db42af522cce)
