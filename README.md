# Real-Time Sales Tracking System (Mendix)

## Overview
This project is a real-time sales tracking system developed using the Mendix low-code platform. It addresses the business need of a company with a large salesforce visiting thousands of customers. Salespeople use a mobile app to instantly submit sales data, which is then displayed on a web dashboard for company monitoring.

## Features
- **Mobile App**: Salespeople submit sales (customer, product, quantity) via a Progressive Web App (PWA).
- **Web Dashboard**: Real-time view of sales activities, with filters and charts.
- **Scalability**: Supports thousands of customers and hundreds of daily sales.
- **Insights**: Tracks sold/unsold products and salesperson performance.

## Business Problem
Our company has multiple salespeople visiting customers to sell products. We needed a system to:
- Instantly capture sales data from mobile devices.
- Monitor activities and product performance on a web platform.
- Handle a large customer base efficiently.

## Solution
Built in Mendix, this system uses:
- **Entities**: Salesperson, Customer, Product, Sale.
- **Microflows**: For data validation and submission.
- **XPath**: For real-time data retrieval (e.g., `[Sale.Timestamp > $yesterday]`).
- **Deployment**: Hosted on Mendix Cloud.

## Setup Instructions
1. Clone this repository: `git clone https://github.com/yourusername/RealTimeSalesTrackingMendix.git`
2. Open in Mendix Studio Pro (v10.x recommended).
3. Deploy to Mendix Cloud or a local environment.

## Future Enhancements
- Offline mode for mobile app.
- Integration with CRM systems via REST APIs.
- Predictive analytics for sales trends.

## Contributors
- [Aaradhya Bali] - Developer

