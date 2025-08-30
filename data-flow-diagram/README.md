# Data Flow Diagram (DFD) – ALX Airbnb Project Documentation

## 📌 Overview

This section of the **ALX Airbnb Project Documentation** focuses on the **Data Flow Diagram (DFD)**.  
The DFD illustrates **how data moves through the system**, highlighting the interactions between external entities, system processes, and data storage.

The DFD helps us visualize:

- How users interact with the platform
- What processes transform or handle data
- Where data is stored or retrieved
- How bookings, properties, and payments flow across the system

---

## 🎯 Objective

The objective of this task is to **design a Data Flow Diagram** that captures the backend data interactions for the Airbnb-like platform.  
Specifically, the diagram explains:

- **Inputs** (e.g., user registration details, booking requests, payment details)
- **Processes** (e.g., authentication, booking confirmation, payment validation)
- **Outputs** (e.g., confirmation messages, receipts, property availability updates)
- **Data stores** (e.g., User database, Property database, Booking records, Payment records)

---

## 🏗 Key Entities in the System

The DFD captures the flow of data between these major entities:

1. **User** 👤

   - Provides registration details, booking requests, and payment information.
   - Receives booking confirmations and notifications.

2. **Host** 🏠

   - Registers property details (e.g., location, availability, pricing).
   - Receives booking requests and confirmations.

3. **System Processes** ⚙️

   - **User Management** → Handles registration, login, and profile updates.
   - **Property Management** → Stores property details, availability, and updates.
   - **Booking Management** → Matches users with available properties and processes reservations.
   - **Payment Processing** → Validates and records transactions securely.

4. **Data Stores** 🗄
   - **User Database** → Stores account information and credentials.
   - **Property Database** → Contains property listings and availability.
   - **Booking Records** → Tracks reservations, cancellations, and history.
   - **Payment Records** → Logs transactions for financial accountability.

---

## 🔄 Data Flow Summary

- **User → System**:  
  Provides details for registration, login, booking, and payment.

- **System → Data Stores**:  
  Saves user accounts, property listings, booking history, and payment transactions.

- **Data Stores → System**:  
  Retrieves property availability, user credentials, and booking details when needed.

- **System → User/Host**:  
  Sends booking confirmations, receipts, property updates, and notifications.

---

## 📊 Diagram

The **Data Flow Diagram** was created using [Draw.io](https://draw.io).

- **File name**: `data-flow.png`
- **Location**: `data-flow-diagram/` directory of this repository

### Directory Structure:
