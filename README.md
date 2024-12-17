# Driving & Vehicle License Department (DVLD) System - Documentation

## Overview
The DVLD System is designed to manage and issue driving licenses, ensuring that drivers meet the necessary requirements to drive safely. The system will handle various services related to driving licenses, including issuance, renewal, replacement, and international license requests. This document outlines the key features, requirements, and functionalities of the system.

## Services Provided
### 1. Issuance of a New Driving License
- [x] Description: Allows applicants to apply for a new driving license.

- [x] Fee: $5 (Application Fee) + License Fee based on category.

- [x] License Categories:

- [x] Category 1: Small Motorcycles

- [x] Minimum Age: 18 years

- [x] License Fee: $15

- [x] Validity: 5 years

- [x] Category 2: Heavy Motorcycles

- [x] Minimum Age: 21 years

- [x] License Fee: $30

- [x] Validity: 5 years

- [x] Category 3: Regular Vehicles (Cars)

- [x] Minimum Age: 18 years

- [x] License Fee: $20

- [x] Validity: 10 years

- [x] Category 4: Commercial Vehicles (Taxi/Limousine)

- [x] Minimum Age: 21 years

- [x] License Fee: $200

- [x] Validity: 10 years

- [x] Category 5: Agricultural Vehicles (Tractors)

- [x] Minimum Age: 21 years

- [x] License Fee: $50

- [x] Validity: 10 years

- [x] Category 6: Small & Medium Buses

- [x] Minimum Age: 21 years

- [x] License Fee: $250

- [x] Validity: 10 years

- [x] Category 7: Trucks & Heavy Vehicles

- [x] Minimum Age: 21 years

- [x] License Fee: $300

- [x] Validity: 10 years

## License Renewal
- [x] Description: Allows the renewal of an existing driving license.
- [x] Fee: $10 (Renewal Fee) + Vision Test Fee.
- [x] Conditions: The expired license must be surrendered before renewal.

### 2. Replacement of Lost License
- [x] Description: Issuance of a replacement for a lost license.
- [x] Fee: $20 (Replacement Fee)
- [x] Conditions: The system must confirm that the license is not under suspension.

### 3. Replacement of Damaged License
- [x] Description: Issuance of a replacement for a damaged license.
- [x] Fee: $20 (Replacement Fee)
- [x] Conditions: The damaged license must be surrendered.

### 4. License Reinstatement
- [x] Description: Reinstates a suspended license after payment of the necessary fines.
- [x] Fee: $5 (Reinstatement Fee)
- [x] Conditions: The suspended license must be surrendered for reactivation.

### 5. Issuance of International Driving License
- [x] Description: Issuance of an international driving license.
- [x] Fee: $20 (International License Fee)
- [x] Conditions: Available only to holders of valid Category 3 licenses. No existing international license should be active; otherwise, the old license will be canceled.

### 6. Re-examination Service
- [x] Description: Allows applicants to schedule a re-examination after failing a test.
- [x] Fee: $5 (Re-examination Fee) + Test Fee based on category.
- [x] Conditions: A new appointment must be scheduled manually after failure.

> [!NOTE]
> Application Process:

- [x] Application Number: Unique identifier for each application.
- [x] Application Date: The date when the application is submitted.
- [x] Applicant ID: Retrieved using the National ID; if not in the system, the applicant must be added first.
- [x] Application Type: Based on the selected service.
- [x] Application Status: New, Canceled, or Completed.
- [x] Application Fees: Total amount paid for the service.
- [x] License Category (if applicable): Must be specified for new licenses.
- [x] Applicant Verification: Ensures the applicant has no previous application of the same type (not completed).

## Applicant Information:
` National ID `
` Full Name `
` Date of Birth ` 
` Address `
` Phone Number `
` Email `
` Nationality `
` Personal Photo `

## License Information:
` License Number `
` Applicant’s National ID `
` Applicant’s Name `
` Date of Birth `
` License Category `
` Issue Date `
` Expiration Date `
` License Conditions (if any) `
` License Status: ` ` New ` ` Lost Replacement ` ` Damaged Replacement ` ` Renewal ` 

> [!NOTE]
> Test Requirements:

### 1. Vision Test
- [x] Description: Medical examination to verify the applicant's visual ability.
- [x] Fee: $10 (Vision Test Fee)
- [x] Conditions: Must pass to proceed; failure requires corrective measures (glasses or surgery) and rescheduling.

### 2. Theory Test
- [x] Description: Written examination on traffic laws and road safety.
- [x] Fee: $20 (Theory Test Fee)
- [x] Conditions: Must pass to proceed; failure requires rescheduling with a new fee.

### 3. Practical Driving Test
- [x] Description: Hands-on test to assess the applicant's driving skills.
- [x] Fee: Based on license category.
- [x] Conditions: Must pass to obtain the license; failure requires rescheduling with a new fee.

## System Management

### 1. User Management:
- [x] Add User: Associate with a person in the system.
- [x] Manage Roles & Permissions: Assign appropriate access rights.
- [x] Audit Logs: Track system activity.

### 2. Reporting & Analytics:
- [x] License Issuance Report: Track the number and types of licenses issued.
- [x] Re-examination Statistics: Monitor re-examination requests and pass rates.
- [x] Revenue Reports: Generate reports on the revenue collected from various services.
