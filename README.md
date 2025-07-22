# 🏥 Hospital Management System (GUI + MySQL)

A Hospital Management System GUI built using **Python's Tkinter** for the front-end and **MySQL** for the back-end database. This application helps store and manage patient details and their prescriptions in an efficient way.

## 📌 Features

- Add, update, delete patient records
- Prescription input and display
- Dynamic GUI with input validation
- Data stored and retrieved from MySQL
- Scrollable table with patient records
- Clear and exit functionalities

## 🛠️ Technologies Used

- Python (Tkinter)
- MySQL
- `mysql-connector-python` for DB integration

## CREATE DATABASE mydata;

USE mydata;

## CREATE TABLE hospital (
    Nameoftablets VARCHAR(255),
    Reference_Number VARCHAR(255) PRIMARY KEY,
    Dose VARCHAR(255),
    NumberofTablets VARCHAR(255),
    Lot VARCHAR(255),
    Issuedate VARCHAR(255),
    Expdate VARCHAR(255),
    DailyDose VARCHAR(255),
    StorageAdvice VARCHAR(255),
    nhsNumber VARCHAR(255),
    PatientName VARCHAR(255),
    DateOfBirth VARCHAR(255),
    PatientAddress VARCHAR(255)
);

## 📸 Screenshots

➤ GUI - Home Screen

![page_12_img_3](https://github.com/user-attachments/assets/30c734b9-c935-46b4-bb41-c47bd246df93)


![page_11_img_2](https://github.com/user-attachments/assets/672a77fc-3972-4c1a-817d-2b80eeba3963)


➤ Insert New Record

![page_11_img_1](https://github.com/user-attachments/assets/708e660a-0860-4619-95ee-6c75d8ec7780)


➤ Updated Record


![page_12_img_1](https://github.com/user-attachments/assets/14816e78-4e92-440a-8965-bc6b6951d6e3)


➤ Delete  Record


![page_12_img_2](https://github.com/user-attachments/assets/61d671fd-ce4a-4ccb-87e1-5a9f09e74caf)


➤  Clear Record

![page_12_img_3](https://github.com/user-attachments/assets/6e26c432-d4a0-43d5-a394-2c3083048721)


➤ Exit


![page_13_img_1](https://github.com/user-attachments/assets/ada43d28-c14a-45a5-a055-85f63aebe7f1)


➤ SQL Table View


![page_13_img_2](https://github.com/user-attachments/assets/23e01bb5-0fa3-4291-952b-db15c65e021b)




## 📚 References

Tkinter GUI Tutorials

MySQL Connector Docs
