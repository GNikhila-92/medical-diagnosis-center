# Medical Diagnosis Center (MDC)

**A ServiceNow-Based Diagnostic Management System**

## Overview

The Medical Diagnosis Center (MDC) is a ServiceNow application designed to streamline diagnostic center operations through centralized management of diagnostic tests, patient registration, appointment scheduling, and medical reports. It leverages ServiceNow Service Portal, custom tables, role-based access control, and Business Rules to organize workflows for patients and diagnostic center staff.

## Key Features

- **Diagnostic Test Management:** Maintain diagnostic test details, pricing, duration, and preparation instructions.
- **Patient Management:** Store and manage patient registration information.
- **Appointment Scheduling:** Support diagnostic test bookings and appointment status tracking.
- **Medical Report Management:** Maintain reports associated with diagnostic appointments.
- **Role-Based Access:** Separate functionality for administrators, patients, receptionists, and laboratory technicians.
- **Workflow Automation:** Use ServiceNow Business Rules to automate selected record-processing tasks.
- **Service Portal:** Provide dedicated pages for test browsing, bookings, appointments, reports, and administration.

## Technology Stack

| Component | Technology |
|---|---|
| Platform | ServiceNow |
| User Interface | Service Portal |
| Data Management | Custom ServiceNow Tables |
| Automation | Business Rules |
| Scripting | JavaScript / ServiceNow Server-Side Scripts |

## User Roles

- **MDC Admin:** Application and data administration.
- **MDC Patient:** Test booking and access to appointments and reports.
- **MDC Receptionist:** Patient registration and appointment management.
- **MDC Lab Technician:** Sample-processing and report-status updates.


## Future Enhancements

- Improve appointment time-zone consistency.
- Strengthen patient-specific access controls.
- Implement duplicate-report prevention.
- Generate and attach downloadable PDF reports.
- Introduce appointment and report notifications.
- Expand security, usability, and performance testing.

## Project Status

The application is under development and testing. Features and workflows should be considered complete only after verification in the ServiceNow instance.

## Disclaimer

This project is intended for academic and demonstration purposes. Sample medical findings are not clinically validated and must not be used for diagnosis or treatment.
