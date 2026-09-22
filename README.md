Pharmacy – Medicine Sale and Billing System

Overview

The Pharmacy – Medicine Sale and Billing System manages medicine details, customer information, prescriptions, medicine availability, sales, billing, and transaction status.

Objectives

Manage medicine and stock details.

Store customer and prescription information.

Check medicine availability before sale.

Verify prescriptions when required.

Generate bills for medicine sales.

Update medicine quantity after each sale.

Track completed and rejected transactions.


Main Entities

MEDICINE – Stores medicine details and available quantity.

CUSTOMER – Stores customer information.

PRESCRIPTION – Stores prescription and doctor details.

SALE/BILL – Stores sales and billing information.

RECORD_STATUS – Stores transaction status and remarks.


Database Relationships

One medicine can be included in many sales.

One customer can have many sales.

One customer can have many prescriptions.

A sale may require a prescription.

Each sale generates a transaction status record.


System Workflow

1. Enter and validate medicine details.


2. Enter customer details.


3. Enter prescription details.


4. Check medicine availability.


5. Verify the prescription if required.


6. Calculate the bill.


7. Update the available medicine quantity.


8. Store the sale and transaction status.


9. Display the bill and final transaction status.



Billing Logic

Medicine Available → Verify Prescription → Calculate Bill → Update Stock → Sale Completed

Medicine Not Available → Sale Rejected / Not Available

Project Documentation

This repository contains:

ER Diagram

Medicine Sale Flowchart

System Algorithm


Conclusion

The system provides an organized process for medicine sales, billing, stock management, prescription verification, and transaction tracking in a pharmacy.
