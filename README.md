# Flight Sales Analytics Dashboard (Metabase)

Built an end-to-end analytics solution for a real-world OTA flight booking dataset using PostgreSQL + Metabase.

---
Dashboard Video Link:
https://drive.google.com/file/d/123Qs0tqXatrgdi85BWoHRv8zlvMlY6Fd/view?usp=sharing

## Dataset
Industry-level OTA (Online Travel Agency) transaction data was used for analysis, including:
- Booking and transaction details (`booking_id`, `booking_status`, `category`)
- Customer and traveller information (`sell_region`, `number_of_traveller`)
- Travel timeline analysis (`booking_date`, `departure_date`, `return_date`)
- Airline and route performance (`airline`, `route`, `route_type`, `segment`)
- Location analytics (`departure_location`, `destination_location`)
- Revenue and pricing metrics (`base_fare`, `tax`, `customer_payable`, `net_revenue`)
- Profitability analysis (`markup_percentage`, `markup_amount`, `commission_amount`)
- Payment tracking (`payment_gateway`, `payment_status`, `received_amount`)
- Currency and GMV analysis (`currency_code`, `total_gmv_usd`)
- Supplier and operational insights (`supplier_name`, `gds`, `pcc`, `flight_type`)

---

## Project Work
- Connected and integrated dataset with PostgreSQL and Metabase
- Developed 20+ business-driven SQL insights
- Designed 2 interactive analytical dashboards

---

## Dashboard Coverage
- Profitability by airline & route  
- Airline revenue share  
- Booking trends (airline & route-wise)  
- Monthly revenue trends  
- Booking status distribution and more

---

## Dashboard Insights
- Total revenue reached **4.5M**, with **98.6% revenue in SGD**, showing strong dependence on one currency market.
- Payment performance is strong with **98.75% fully paid bookings** and very low partial payments.
- Total bookings recorded: **14,536**.
- A few routes generate the majority of bookings, indicating highly concentrated customer demand.
- Airline **BS** leads in both **bookings and profit**, making it the top-performing airline partner.
- Airlines with low bookings and profit may require pricing or route optimization.
- Revenue increased significantly from **late 2024 onward**, showing strong business growth momentum.
- Top routes maintain the highest margins and profitability, while lower-performing routes contribute minimal profit.

---

## Outcome
Delivered a structured BI solution to understand revenue drivers, risks, and business performance.
