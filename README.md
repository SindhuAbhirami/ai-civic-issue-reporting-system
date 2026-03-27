# AI Civic Issue Reporting System

## Overview

This project focuses on solving common urban problems like potholes, garbage accumulation, fallen trees, and damaged public infrastructure.

In most existing systems, users have to manually describe the issue and select categories, which is time-consuming and sometimes inaccurate. This project simplifies the process by allowing users to upload an image, and the system automatically detects the issue and generates a description.

The goal is to make civic issue reporting faster, easier, and more accessible.



## Problem Statement

Traditional complaint systems require manual input from users, which leads to:

* Incorrect issue categorization
* Incomplete descriptions
* Low user engagement

This project addresses these problems using AI-based automation.



## Solution

The system uses a trained YOLOv8 model to detect the type of issue from an image.
After detection, a language model generates a simple description of the problem.

The issue is then stored and can be managed through a dashboard by authorities.



## Features

* Image-based issue detection
* Supports multiple issue types (potholes, garbage, trees, etc.)
* Automatic description generation
* Role-based system (User and Admin)
* Issue tracking system



## Tech Stack

* Frontend: React
* Backend: Spring Boot
* AI Model: YOLOv8
* Database: PostgreSQL
* Authentication: JWT



## How it works

1. User uploads an image of a civic issue
2. The YOLOv8 model processes the image
3. The system identifies the issue type
4. A basic description is generated automatically
5. The issue is stored in the database
6. Authorities can view and update the status



## Project Structure (High-Level)

* AI Service → Handles model prediction
* Backend API → Manages data and authentication
* Frontend → User interface for reporting and tracking



## Sample Output


![4](https://github.com/user-attachments/assets/158c5ee7-16a7-4d6e-bf79-99542407fe94)
![7](https://github.com/user-attachments/assets/a123c88a-4c0f-4848-8c2a-453550021661)
![5](https://github.com/user-attachments/assets/736db70f-bd79-4bb5-ab26-eb4815c05afc)
![6](https://github.com/user-attachments/assets/a8e4b4eb-c4f2-4cf9-9530-638359b69628)
![9](https://github.com/user-attachments/assets/6c685d65-1761-44ed-9f6c-cfb8aa0be8de)
![8](https://github.com/user-attachments/assets/3ac3507d-49ba-42ca-ac3b-7a37761c37ea)
![10](https://github.com/user-attachments/assets/2f63eae8-1736-40f9-a117-ebded0c3e1ef)
![3](https://github.com/user-attachments/assets/06989f76-a0a8-4e7a-a1f0-771ae73984d5)
![1](https://github.com/user-attachments/assets/5eec0a57-64f7-409b-a80e-30ddaff5cb63)
![12](https://github.com/user-attachments/assets/e15f417d-388f-415a-b0f9-71dd718fc7ac)
![11](https://github.com/user-attachments/assets/8e09b202-f72a-44a4-a73f-bc99116ea0f8)
![13](https://github.com/user-attachments/assets/4c470cfa-0a4f-49d3-aeb7-a3b59ad037ee)


## Future Scope

* Mobile application support
* Real-time notifications
* Integration with government systems
* Multi-language support



## Note

Full source code is kept private due to academic submission guidelines.
This repository is intended to present the idea, workflow, and implementation approach.



## Author

Sindhu Abhirami
