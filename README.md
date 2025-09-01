Smart IPDR Analysis Tool for Law Enforcement Investigations 🚓🔍
Project Overview
This project is an intelligent system designed to extract and identify B-party (recipient) Public IP addresses and mobile numbers from Internet Protocol Detail Records (IPDR) logs. By accurately mapping interactions between A-party (initiator) and B-party users, the tool supports law enforcement, telecom investigations, and security analysis. It provides clear insights into communication patterns, enabling faster identification of suspects, networks, and suspicious activities within large and complex digital communication data. 📊📞

This solution ensures high accuracy, supports diverse IPDR formats, and streamlines investigative workflows through advanced parsing, filtering, and analysis. ⚙️💡

Key Features
Multi-format IPDR Parsing 🗂️: Supports various IPDR log formats (CSV, TXT, JSON) from multiple telecom operators, ensuring wide applicability.

A-Party and B-Party Mapping 🔗: Precisely extracts and links initiator and recipient numbers and IP addresses for detailed communication mapping.

Data Filtering and Normalization 🧹: Filters out irrelevant records and normalizes data from diverse providers for consistent analysis.

Suspicious Activity Detection 🚨: Employs machine learning using a Random Forest algorithm to detect unusual communication patterns such as frequent late-night calls or short-duration interactions.

Interactive Communication Visualizations 📈: Utilizes Recharts to present connection graphs and statistical charts depicting communication patterns intuitively.

Map API Integration 🗺️: Geographically visualizes IP or mobile number locations to enhance investigation accuracy.

Robust Search and Query System 🔍: Enables investigators to search by numbers, Public IP, date ranges, and communication types quickly and efficiently.

User-Friendly Dashboard 🖥️: Built with React for a responsive, accessible, and easy-to-navigate interface summarizing key data insights and red flags.

Secure Authentication and Data Handling 🔐: Uses Clerk for secure login authentication and MongoDB for scalable, reliable data management.

Compliance and Security 🛡️: Ensures protection of sensitive communication data adhering to privacy laws and best practices.

Technology Stack
Component	Technology
Frontend	React ⚛️
Backend & Database	MongoDB 🍃
Authentication	Clerk 🔐
Data Visualization	Recharts 📊
Machine Learning Model	Random Forest 🌲
Mapping	Map API 🗺️
Log Parsing & Processing	Custom Parser Engine ⚙️
Installation & Setup
Clone the repository:

bash
git clone <repository-url>
cd <project-folder>
Install frontend dependencies:

bash
cd frontend
npm install
Install backend dependencies:

bash
cd ../backend
npm install
Set up environment variables for:

MongoDB connection URI

Clerk authentication keys

Map API keys

Start the development servers:

Backend: npm start

Frontend: npm start

Usage
Upload IPDR log files in supported formats to the system. 📂

The parser engine processes and extracts A-party and B-party communication details. 🛠️

Use the dashboard to view communication mappings, charts, and suspicious activity alerts. 📊🔔

Search communication records by number, IP, date, or other filters. 🔎

Use the map view to visualize geolocations tied to communication. 🗺️

Investigators can quickly identify and track suspicious communication patterns flagged by the ML model. 👁️‍🗨️

Machine Learning Suspicious Activity Detection
The system integrates a Random Forest model trained to detect abnormalities based on call frequency, time of day, call duration, and other features. 🌲🤖

Alerts are generated automatically to highlight potential suspicious patterns for further investigation. 🚨

Security & Privacy
All sensitive data is secured with strong authentication via Clerk. 🔐

Data stored in MongoDB is protected and access-controlled. 🛡️

The system is designed to comply with relevant data privacy regulations. 📜

Contributing
Contributions are welcome! Please open issues or pull requests to improve feature sets, performance, or documentation. 🤝

License
[Specify project license] 📄
