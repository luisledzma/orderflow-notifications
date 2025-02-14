# OrderFlow - Notification Service

## Description
The **Notification Service** is responsible for sending real-time notifications when there are order status changes. Notifications can be sent via **email, WebSockets, or push notifications**.

## Features
- **Real-time notifications** using **SignalR**
- **Asynchronous processing** via **RabbitMQ**
- **Support for multiple channels**: Email, WebSockets, Push Notifications
- **User preference management** for notification settings

## Technologies
- .NET 8 Web API
- SignalR for real-time messaging
- RabbitMQ for event-driven communication
- SMTP for email notifications

## Running the Service
1. Clone the repository:  
   ```sh
   git clone https://github.com/your-username/orderflow-notifications.git
   cd orderflow-notifications
