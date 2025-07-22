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

## USE mydata;

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
