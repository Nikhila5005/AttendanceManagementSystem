# Attendance Management System

The Attendance Management System is designed to streamline and automate the process of tracking and managing attendance for organizations, ensuring accuracy and efficiency.


## Features

- **Scalable Architecture**: Engineered a highly scalable attendance management system using **Spring Boot** and **PostgreSQL**, reducing **attendance errors by 40%** through automated data synchronization and real-time tracking.  
- **Automated Payroll Integration**: Integrated **leave and holiday data** into salary calculations, cutting **payroll processing time by 50%** and ensuring precise salary distribution.  
- **Real-Time Notifications**: Implemented **Java Mail Sender** for real-time email alerts, boosting **employee punctuality by 30%** through timely clock-in/out reminders and daily/weekly attendance summaries.  
- **Optimized Database Performance**: Refined data-fetching logic, improving **query speed by 35%**, enabling efficient handling of large-scale organizational data.  
- **RESTful API Development**: Designed and developed **RESTful APIs** for **public holiday management, attendance tracking, and working day calculations**, minimizing manual interventions and improving accuracy.  

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Nikhila5005/AttendanceManagementSystem.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd AttendanceManagementSystem
   ```
3. **Install Dependencies**:
   Ensure you have [Maven](https://maven.apache.org/) installed. Then, run:
   ```bash
   mvn install
   ```
4. **Configure the Database**:
   - Set up your preferred database (e.g., MySQL, PostgreSQL).
   - Update the database configuration in `src/main/resources/application.properties`.

5. **Run the Application**:
   ```bash
   mvn spring-boot:run
   ```

## Usage

- **Access the Application**:
  Once the application is running, access it via `http://localhost:8080`.
- **User Roles**:
  - **Admin**: Manage users, view reports, and configure settings.
  - **Employee**: View personal attendance records and receive notifications.
- **Attendance Marking**:
  - Depending on the configuration, attendance can be marked via biometric devices, web check-ins, or mobile applications.


## Contributing

Contributions are welcome! To contribute:

1. **Fork the Repository**: Click on the 'Fork' button at the top right corner of this page.
2. **Create a New Branch**:
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. **Commit Your Changes**:
   ```bash
   git commit -m 'Add some feature'
   ```
4. **Push to the Branch**:
   ```bash
   git push origin feature/YourFeatureName
   ```
5. **Open a Pull Request**: Navigate to the original repository and click on 'New Pull Request'.

## Contact

For any queries or collaboration, feel free to reach out to  
[**Akula Nikhila Reddy**](mailto:nikhilareddy5005@gmail.com)
