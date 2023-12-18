# Used Cars Database

## Table

###  **Vehicles:**
   - `ID`: INT, PRIMARY-KEY, AUTOINCREMENT
   - `model`: VARCHAR(255), NOTNULL
   - `year_of_production`: YEAR, NOTNULL
   - `kilometers_driven`: INT, NOTNULL
   - `price`: DECIMAL, NOTNULL
   - `vehicle_selling_status`: VARCHAR(255), NOTNULL
   - `name_seller`: VARCHAR(255), NULL
   - `number_seller`: VARCHAR(255), NULL
   - `car_photo`: VARCHAR(255), NULL
   - `insertion_date`: DATETIME, NOTNULL
   - `car_image`: VARCHAR(255), NULL
   - `car_location`: VARCHAR(255), NULL
   - `maintenance_history`: TEXT, NULL
   - `sales_history`: TEXT, NULL
   - `sales_notes`: TEXT, NULL
   - `vehicle_rating`: VARCHAR(255), NULL
   - `fuel_type`: VARCHAR(255), NOTNULL
   - `engine_information`: TEXT, NULL
   - `vehicle_condition`: VARCHAR(255), NULL
   - `payment_preferences`: TEXT, NULL
   - `technical_details`: TEXT, NULL
