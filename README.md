# Healthcare-Management-system
## 📁 Case Study 1: Hospital Patient Management System

### 🔍 Problem Statement
A hospital wants to build a system to efficiently manage:
- Patient records
- Doctor appointments
- Treatment history
- Hospital performance metrics

### ✅ Solution
A relational database system is implemented to:
- Store Electronic Health Records (EHR)
- Analyze patient demographics, diagnoses, treatment outcomes, and more
- Run SQL queries for operational insights

### 🗃️ Database Schema

#### Patients Table
- `patient_id` (Primary Key)
- `patient_name`
- `date_of_birth`
- `gender`
- `address`
- `phone_number`

#### Doctors Table
- `doctor_id` (Primary Key)
- `doctor_name`
- `specialization`
- `department`

#### MedicalRecords Table
- `record_id` (Primary Key)
- `patient_id` (Foreign Key)
- `admission_date`
- `discharge_date`
- `diagnosis`
- `treatment`
- `doctor_id`

### 📊 SQL Queries

#### 🟢 Basic
- Retrieve patient names and genders
- Count total patients
- Find oldest patient
- List all diagnoses

#### 🟡 Medium
- Average patient age
- Patients with hypertension or diabetes
- Doctors treating patients in Jan 2023

#### 🔴 Advanced
- Readmission rates within 30 days
- Median hospital stay duration
- Top doctors treating specific conditions

#### 📌 Final Insights
- Gender distribution
- Common diagnoses
- Top doctors by patient volume

📁 **Dataset Link:** [Click to Access](https://drive.google.com/drive/folders/1roRp4cadioql1mDqZvzUVyy-YTvnADxy?usp=sharing)
