
# 🏥 Digital Patient Card (DPC)

A **Java-based mini project** that allows patients to manage their health profiles and enables doctors to verify the data and add prescriptions. It also generates a printable PDF health card.

## 👥 Team Members

- Aebel Antosh  
- G S Balamurali  
- Johan Abraham  
- Rohan K Joseph  

## 🎯 Objectives

- Secure login system for both **Patients** and **Doctors**
- Patients can:
  - Register and manage personal profiles
  - Add health information (e.g., allergies, diseases)
  - Download a printable health card in PDF format
- Doctors can:
  - Search patients by ID
  - Verify patient-entered data
  - Add prescriptions to patient records

## 🛠️ Tech Stack

- **Language**: Java (Core)
- **Database**: File-based or JDBC (depending on implementation)
- **PDF Generation**: [iText Library](https://itextpdf.com/en)

## 📁 Project Structure

```plaintext
src/
├── Main.java
├── User.java
├── Patient.java
├── Doctor.java
├── HealthDetail.java
├── Prescription.java
├── PDFGenerator.java
└── DBHandler.java
