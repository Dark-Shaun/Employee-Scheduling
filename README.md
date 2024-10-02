# **In-House Scheduling App for Medical Product Showcases**

## **Overview**
The **In-House Scheduling App** is an internal tool developed and maintained by **Renuka Pharma** to facilitate seamless coordination of product showcase calls with doctors. The app is designed to optimize scheduling, reduce wait times, and ensure efficient communication between Renuka Pharma’s representatives and doctors. Built with a robust architecture, this system ensures secure, reliable, and scalable operations tailored to meet Renuka Pharma’s unique business needs.

## **Project Purpose**
The main objective of this application is to simplify the process of arranging product showcase appointments with doctors based on their availability. This allows Renuka Pharma’s sales and medical teams to schedule product demos, consultations, and feedback sessions efficiently, without overlaps or delays.

## **Features**
### **1. Secure Authentication & Authorization**
The app ensures that all data is secure through **JWT-based authentication**. Only authorized personnel from Renuka Pharma have access to the system, with role-based permissions to control access to sensitive data and features.

### **2. Intelligent Scheduling Algorithm**
The core of this application is an intelligent algorithm that analyzes doctor availability, existing appointments, and time constraints to provide optimal scheduling solutions. This ensures that doctors can book their appointments without conflicts and minimal downtime.

### **3. Responsive Frontend**
The user interface is built using **React.js**, providing a seamless experience across devices, including desktops, tablets, and smartphones. The use of **Redux** for state management ensures a smooth and responsive UI, while **styled-components** maintains a consistent design and user experience.

### **4. Robust Backend**
The backend, developed in **Node.js** using **Express**, is responsible for managing appointments, user data, and schedules. **PostgreSQL** is used as the relational database to store user and appointment information, providing fast query execution and reliable data integrity.

### **5. Calendar Integration**
The app integrates with **Google Calendar API** and **Microsoft Graph API** to sync appointments with doctors' calendars automatically. This allows both doctors and Renuka Pharma representatives to manage their schedules efficiently and stay updated with upcoming meetings.

### **6. Containerized Deployment**
To ensure scalability and portability, the entire system is containerized using **Docker**. **Kubernetes** orchestrates these containers, making it easy to deploy and maintain the system on Renuka Pharma’s on-premise servers and private cloud infrastructure.

### **7. Automated CI/CD Pipelines**
With **GitLab CI/CD** pipelines, the application undergoes continuous integration and deployment. Every new feature, bug fix, or update is automatically tested and deployed, ensuring that the application remains up-to-date and error-free.

### **8. Enhanced Security**
The app uses **HTTPS** to encrypt all communications between the client and the server, ensuring the confidentiality of sensitive information. Additionally, data is encrypted at rest, and network security is enforced through **VPNs** and **firewalls** for added protection.

## **Technologies Used**
- **Frontend**: React.js, Redux, styled-components
- **Backend**: Node.js, Express
- **Database**: PostgreSQL
- **Authentication**: JWT (JSON Web Tokens)
- **Calendar Integration**: Google Calendar API, Microsoft Graph API
- **Containerization**: Docker, Kubernetes
- **CI/CD**: GitLab CI/CD
- **Security**: HTTPS, data encryption, VPNs, firewalls

## **How the System Works**
### **1. User Authentication**
Users must log in through a secure login portal where **JWT-based authentication** ensures only authorized personnel gain access. Users are assigned roles (e.g., administrator, scheduler, representative), and permissions are managed accordingly.

### **2. Scheduling Process**
Once logged in, users can view available time slots for doctors and their existing appointments. The intelligent scheduling algorithm matches doctor availability with the desired showcase times, ensuring no overlap or conflicts. The system provides suggestions for optimal meeting times.

### **3. Calendar Sync**
After confirming a meeting, the system syncs the event with the doctor’s calendar using the **Google Calendar API** or **Microsoft Graph API**. This eliminates the need for manual entry and ensures both parties are always aware of their schedules.

### **4. Management Dashboard**
The app features an admin dashboard for Renuka Pharma’s managers to monitor appointments, view performance analytics, and ensure all showcase schedules are running smoothly. They can track meeting success rates, feedback, and appointment history for future reference.

### **5. Scalability and Deployment**
The application is deployed in a containerized environment using **Docker**. This enables Renuka Pharma’s IT team to scale the system horizontally by adding more containers as demand increases. The **Kubernetes** orchestration ensures that the system remains stable and responsive, even during high-traffic periods.

## **Next Iteration**
In future updates, the system will include advanced features to track which medicines are being discussed or requested by doctors during these showcases. This will provide valuable insights to Renuka Pharma’s marketing and sales teams, helping to refine their product offerings and inventory.

## **Maintained by Renuka Pharma**
This project is a critical internal system maintained by Renuka Pharma’s dedicated in-house IT and development team. As it plays a pivotal role in coordinating key product showcase operations, continuous updates and maintenance are provided to ensure reliability and security.

For more information on this project, contact the IT department at Renuka Pharma.
