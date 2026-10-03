# WhatNext Vision Motors - Salesforce CRM Project

## Overview
WhatNext Vision Motors is a Salesforce CRM implementation designed to revolutionize the customer experience and operational efficiency for an automotive company. The project modernizes the vehicle ordering process by automating dealer assignment, validating stock availability, and streamlining test drive scheduling.

## Key Features
* **Data Modeling:** Custom objects to track `Vehicle`, `Dealer`, `Customer`, `Order`, `Test Drive`, and `Service Request`.
* **Stock Validation (Apex Trigger):** An Apex trigger that prevents order placement if a vehicle is out of stock.
* **Auto-Assign Dealer (Flow):** A Record-Triggered Flow that automatically assigns the nearest dealer to a customer based on their location.
* **Test Drive Reminder (Flow):** A Scheduled Flow that automatically sends email reminders to customers a day before their scheduled test drive.
* **Bulk Order Confirmation (Batch Apex):** A scheduled batch job that runs nightly to automatically update the status of pending orders to 'Confirmed' if stock becomes available.

## Technologies Used
* **Salesforce Platform:** Lightning Experience, Object Manager, Schema Builder
* **Automation:** Record-Triggered Flows, Scheduled Paths
* **Apex Code:** Triggers, Trigger Handlers, Batch Apex, Schedulable Apex
* **SOQL:** Data retrieval and stock mapping

## Project Structure
* `force-app/`: Contains all the Salesforce metadata (Objects, Flows, Classes, Triggers) in SFDX format.
* `document/`: Contains the project documentation, phase-wise templates, and reports.
* `screenshots/`: Contains visual evidence of the Salesforce setup, flow builders, and testing.

## Author
Completed as part of the Salesforce Developer Project.
