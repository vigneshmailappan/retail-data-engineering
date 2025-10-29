# retail-data-engineering
This repository demonstrates a full-stack data engineering workflow for a hybrid retail business (ecommerce + physical stores), focusing on mock data generation, data transformation, and cloud-native orchestration using Azure services.

Generating mock data for below tables using pyspark, Will data quality noises which we are going to clean later in the project

| **stores**        | **inventory**       | **employees**       | **products**        | **products_updates** | **customers**        |
|--------------------|----------------------|----------------------|----------------------|-----------------------|-----------------------|
| store_id           | store_id            | employee_id          | product_id           | brand                 | customer_id           |
| store_name         | product_id          | employee_name        | product_name         | category              | full_name             |
| region             | on_hand             | store_id             | brand                | created_at            | email                 |
| city               | unit_cost           | role                 | category             | currency              | phone                 |
| is_active          | snapshot_ts         | monthly_salary       | unit_cost            | event_type            | birth_date            |
| last_updated       |                     | is_active            | list_price           | is_active             | country_code          |
| created_at         |                     | last_updated         | currency             | last_updated          | preferred_currency    |
| ingestion_date     |                     | hire_date            | is_active            | list_price            | is_active             |
|                    |                     | termination_date     | last_updated         | product_id            | last_updated          |
|                    |                     | ingestion_date       | created_at           | product_name          | created_at            |
|                    |                     |                      | ingestion_date       | unit_cost             | ingestion_date        |
