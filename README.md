Introduction
Welcome to Bennett-e-dorm, a comprehensive Hostel Administration System designed in C++. This project provides a user-friendly interface for students and administrators to manage hostel-related tasks efficiently. The system utilizes advanced technologies to greet users according to the time of the day and offers distinct functionalities for students and administrators.

Features
Common Features
Greetings: Upon running the application, users will be greeted with a welcome message tailored to the time of the day (morning, afternoon, or evening).

Menu Options:

Student
Administrator
Exit
Student Zone
Registration:

Enroll No. (College ID)
Name
Mobile No.
Password
Confirm Password
The system ensures password confirmation and valid mobile number entry. User details are saved in registered.txt.

Login:

Enroll No.
Password
Successful login leads to the Student Zone.

Room Allotment:

Name
Enroll No.
Gender
Preferred State
Students are allotted rooms based on gender and preferred state. Room details are saved in roomallocation.txt. If a room is full, the information is moved to finalroomallocation.txt.

Raise a Complaint:

Enroll No.
Name
Brief Complaint
Complaints are saved in complaint.txt, and a confirmation message is provided.

Return to Main Menu

Exit

Administrator Zone
Login:

Admin ID
Password
Successful login leads to the Administrator Zone.

Show Allotted Students:
Displays information from finalroomallocation.txt about students and their allotted rooms.

Show All Complaints:
Displays complaints from complaint.txt.

Return to Main Menu

Exit

Implementation Details
The project uses data structures such as Binary Search Tree and Vector for efficient storage and retrieval.
There are eight .cpp files, including main.cpp, where all components merge seamlessly.
Information is stored in eight .txt files, ensuring organized data management.
Conclusion
Thank you for choosing Bennett-e-dorm! Whether you are a student looking for hassle-free hostel management or an administrator seeking streamlined oversight, this system is designed to meet your needs effectively. Your feedback is valuable, and we hope you have a pleasant experience using Bennett-e-dorm.
