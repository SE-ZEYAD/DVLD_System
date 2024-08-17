# Driving & Vehicle License Department (DVLD) System - Documentation

## Overview
The DVLD System is designed to manage and issue driving licenses, ensuring that drivers meet the necessary requirements to drive safely. The system will handle various services related to driving licenses, including issuance, renewal, replacement, and international license requests. This document outlines the key features, requirements, and functionalities of the system.

## Services Provided
### 1. Issuance of a New Driving License
• Description: Allows applicants to apply for a new driving license.

• Fee: $5 (Application Fee) + License Fee based on category.

• License Categories:

• Category 1: Small Motorcycles

• Minimum Age: 18 years

• License Fee: $15

• Validity: 5 years

• Category 2: Heavy Motorcycles

• Minimum Age: 21 years

• License Fee: $30

• Validity: 5 years

• Category 3: Regular Vehicles (Cars)

• Minimum Age: 18 years

• License Fee: $20

• Validity: 10 years

• Category 4: Commercial Vehicles (Taxi/Limousine)

• Minimum Age: 21 years

• License Fee: $200

• Validity: 10 years

• Category 5: Agricultural Vehicles (Tractors)

• Minimum Age: 21 years

• License Fee: $50

• Validity: 10 years

• Category 6: Small & Medium Buses

• Minimum Age: 21 years

• License Fee: $250

• Validity: 10 years

• Category 7: Trucks & Heavy Vehicles

• Minimum Age: 21 years

• License Fee: $300

• Validity: 10 years

## License Renewal
• Description: Allows the renewal of an existing driving license.
• Fee: $10 (Renewal Fee) + Vision Test Fee.
• Conditions: The expired license must be surrendered before renewal.

### 2. Replacement of Lost License
• Description: Issuance of a replacement for a lost license.
• Fee: $20 (Replacement Fee)
• Conditions: The system must confirm that the license is not under suspension.

### 3. Replacement of Damaged License
• Description: Issuance of a replacement for a damaged license.
• Fee: $20 (Replacement Fee)
• Conditions: The damaged license must be surrendered.

### 4. License Reinstatement
• Description: Reinstates a suspended license after payment of the necessary fines.
• Fee: $5 (Reinstatement Fee)
• Conditions: The suspended license must be surrendered for reactivation.

### 5. Issuance of International Driving License
• Description: Issuance of an international driving license.
• Fee: $20 (International License Fee)
• Conditions: Available only to holders of valid Category 3 licenses. No existing international license should be active; otherwise, the old license will be canceled.

### 6. Re-examination Service
• Description: Allows applicants to schedule a re-examination after failing a test.
• Fee: $5 (Re-examination Fee) + Test Fee based on category.
• Conditions: A new appointment must be scheduled manually after failure.

## Application Process
-- General Information:
• Application Number: Unique identifier for each application.
• Application Date: The date when the application is submitted.
• Applicant ID: Retrieved using the National ID; if not in the system, the applicant must be added first.
• Application Type: Based on the selected service.
• Application Status: New, Canceled, or Completed.
• Application Fees: Total amount paid for the service.
• License Category (if applicable): Must be specified for new licenses.
• Applicant Verification: Ensures the applicant has no previous application of the same type (not completed).

## Applicant Information:
• National ID
• Full Name
• Date of Birth
• Address
• Phone Number
• Email
• Nationality
• Personal Photo

## License Information:
• License Number
• Applicant’s National ID
• Applicant’s Name
• Date of Birth
• License Category
• Issue Date
• Expiration Date
• License Conditions (if any)
• License Status: New, Lost Replacement, Damaged Replacement, Renewal

## Test Requirements

### 1. Vision Test
• Description: Medical examination to verify the applicant's visual ability.
• Fee: $10 (Vision Test Fee)
• Conditions: Must pass to proceed; failure requires corrective measures (glasses or surgery) and rescheduling.

### 2. Theory Test
• Description: Written examination on traffic laws and road safety.
• Fee: $20 (Theory Test Fee)
• Conditions: Must pass to proceed; failure requires rescheduling with a new fee.

### 3. Practical Driving Test
• Description: Hands-on test to assess the applicant's driving skills.
• Fee: Based on license category.
• Conditions: Must pass to obtain the license; failure requires rescheduling with a new fee.

## System Management

### 1. User Management:
• Add User: Associate with a person in the system.
• Manage Roles & Permissions: Assign appropriate access rights.
• Audit Logs: Track system activity.

### 2. Reporting & Analytics:
• License Issuance Report: Track the number and types of licenses issued.
• Re-examination Statistics: Monitor re-examination requests and pass rates.
• Revenue Reports: Generate reports on the revenue collected from various services.
