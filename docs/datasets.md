# Dataset Documentation

This document provides dataset-level documentation for all datasets currently available in **DataForge**.

Each dataset follows a predefined schema and returns a clean `pandas.DataFrame` suitable for analytics, visualization, and testing workflows.

---

## 1️⃣ Retail Sales Dataset

### Description
Simulates ecommerce and retail transaction data commonly used in sales analysis, pricing strategy, and customer segmentation.

### Key Use Cases
- Revenue and profit analysis
- Product performance tracking
- Time-based sales trends
- Store and region comparison

### Key Columns
- Order & Customer: `order_date`, `first_name`, `last_name`, `gender`, `email`
- Product: `product_category`, `product`, `brand`, `unit_price`, `quantity`
- Financials: `sales_amount`, `cost_amount`
- Store & Location: `store_name`, `city`, `state`, `country`

---

## 2️⃣ Employee Dataset

### Description
Represents workforce and HR data for organizational analytics and planning.

### Key Use Cases
- Headcount analysis
- Attrition tracking
- Salary benchmarking
- Workforce diversity metrics

### Key Columns
- Employee Info: `employee_id`, `first_name`, `last_name`, `gender`
- Employment: `department`, `job_title`, `employment_type`
- Dates: `start_date`, `exit_date`, `date_of_birth`
- Compensation: `salary`
- Location: `city`, `state`, `country`

---

## 3️⃣ Job Market Dataset

### Description
Synthetic job postings dataset designed for talent analytics and job market insights.

### Key Use Cases
- Skill demand analysis
- Salary range comparison
- Job recommendation systems
- Market trend analysis

### Key Columns
- Job Details: `job_title`, `role`, `experience`, `work_type`
- Compensation: `salary_range`
- Skills & Requirements: `skills`, `qualifications`
- Location: `location`, `country`, `region`
- Company: `company_name`, `company_profile`

---

## 4️⃣ Courier Logistics Dataset

### Description
Simulates shipment and delivery lifecycle data used in logistics and supply chain analytics.

### Key Use Cases
- SLA monitoring
- Route and delivery analysis
- Cost and tariff evaluation
- Operational performance tracking

### Key Columns
- Shipment: `consignment_no`, `booking_code`, `mode`
- Sender & Receiver: `origin`, `destination`, `sender_city`, `receiver_city`
- Weights: `actual_wt`, `volumetric_wt`, `chargeable_wt`
- Charges: `tariff`, `vas_charges`, `total_amount`
- Dates: `booking_date`, `receive_date`

---

## 5️⃣ Healthcare Visits Dataset

### Description
Represents patient visit records used for healthcare operations and analytics simulations.

### Key Use Cases
- Patient flow analysis
- Department workload tracking
- Billing and insurance analysis
- Hospital performance metrics

### Key Columns
- Patient & Visit: `patient_id`, `visit_id`, `visit_date`
- Clinical: `department`, `diagnosis`, `treatment`
- Financial: `billing_amount`, `insurance_provider`
- Status: `visit_status`

---

> ℹ️ All datasets return a `pandas.DataFrame` and maintain consistent schemas across generations.
