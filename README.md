# 🏨 Hotel Booking & Banking Analytics

## 📊 Project Overview

This project is a comprehensive **Hotel Booking, Revenue, Payment and Banking Analytics** solution designed to analyze hotel booking behavior, cancellation patterns, revenue indicators and payment transactions.

The project combines multiple technologies to demonstrate an end-to-end business analytics workflow:

- 🐍 Python
- ☕ Java
- 🗄️ SQL
- 📊 Microsoft Excel
- 🌐 HTML5
- 🎨 CSS3
- ⚡ JavaScript
- 📈 Data Visualization

The analysis is based on a **synthetic dataset of 3,000 hotel booking records** containing booking information, customer characteristics, hotel details, revenue metrics and a synthetic payment/transaction layer.

> **Important:** All data used in this project is synthetic and created for educational and portfolio purposes. It does not represent any real hotel, customer, bank, payment provider or financial transaction.

---

# 🎯 Project Objectives

The main objective of this project is to build a multi-technology analytics solution that combines **hospitality analytics with financial and payment analytics**.

The project focuses on:

1. Understanding hotel booking behavior
2. Identifying cancellation patterns
3. Analyzing customer segments
4. Studying booking lead time
5. Analyzing hotel performance
6. Examining average daily rates
7. Estimating booking value
8. Analyzing payment methods
9. Studying transaction values
10. Analyzing refunds
11. Monitoring payment statuses
12. Identifying synthetic payment-risk categories
13. Creating business-oriented insights
14. Presenting results through dashboards and reports

---

# 🏨 Hospitality Analytics

The hospitality component focuses on understanding how customers interact with hotels and how different booking characteristics relate to cancellations and revenue.

## Major Areas

### Hotel Type Analysis

The dataset contains:

- City Hotel
- Resort Hotel

The project compares booking volume, cancellation rates, average daily rates and estimated booking values between hotel categories.

---

### Lead Time Analysis

Lead time represents the number of days between the booking date and the expected arrival date.

Bookings are segmented into:

- 0–30 days
- 31–60 days
- 61–120 days
- 121–240 days
- 241–500 days

This helps examine whether booking behavior differs across advance-booking periods.

---

### Cancellation Analysis

The project analyzes:

- Cancelled bookings
- Non-cancelled bookings
- Overall cancellation rate
- Cancellation rate by hotel
- Cancellation rate by lead time
- Cancellation rate by deposit type
- Cancellation rate by market segment
- Cancellation rate by customer type
- Cancellation rate by arrival month

---

### Market Segment Analysis

Bookings are analyzed across different market segments:

- Online TA
- Offline TA/TO
- Direct
- Corporate
- Groups

This helps demonstrate customer acquisition and booking-channel analysis.

---

### Customer Type Analysis

The project analyzes customer categories such as:

- Transient
- Transient-Party
- Contract
- Group

The objective is to compare booking volume, cancellation behavior and estimated booking value.

---

# 💰 Revenue Analytics

The project also includes revenue-related variables.

Key metrics include:

- Average Daily Rate
- Estimated Booking Value
- Transaction Amount
- Refund Amount
- Net Transaction Value

These metrics allow operational booking data to be connected with financial analysis.

---

# 🏦 Banking & Payment Analytics

A synthetic banking/payment layer has been added to the project.

The payment component demonstrates how transaction data can be analyzed alongside operational booking data.

## Payment Methods

The dataset contains:

- Credit Card
- Debit Card
- Net Banking
- UPI
- Bank Transfer

---

## Payment Status

Transactions are categorized into:

- Paid
- Pending
- Refunded

---

## Transaction Analysis

The project analyzes:

- Total transaction value
- Average transaction value
- Transaction count
- Refund value
- Net transaction value
- Transaction value by payment method
- Refund value by payment method
- Payment status distribution

---

# ⚠️ Payment Risk Analysis

A synthetic payment-risk flag is included for demonstration purposes.

Example categories include:

- Normal
- Payment Pending
- Refund Review
- Cancellation Payment Review

These flags are intended to demonstrate how transaction monitoring workflows can be structured.

They **do not represent real banking risk models or actual financial institution policies**.

---

# 🛠️ Technology Stack

## 🐍 Python

Python is used for:

- Data analysis
- Data validation
- KPI generation
- Payment analysis
- Summary generation
- Data-quality checks

Main libraries:

```text
Pandas
NumPy
Matplotlib
OpenPyXL
