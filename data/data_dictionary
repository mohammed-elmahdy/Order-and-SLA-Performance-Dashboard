# Data Dictionary

## orders
- order_id: unique identifier for each order
- order_time: timestamp when the order was placed
- city: city where the order was placed (Dubai, Abu Dhabi, Sharjah)
- vendor: vendor/store fulfilling the order
- rider_id: unique identifier for the delivery rider
- status: order status (Delivered, Delayed, Cancelled)
- cancel_reason: reason for cancellation (Customer, Vendor, Rider)
- delivery_time_min: total delivery duration in minutes
- expected_delivery_min: expected delivery duration in minutes
- prep_time_min: time taken by vendor to prepare the order
- pickup_time_min: time taken for rider to pick up the order

---

## calculated_columns
- delivery_delay_min: difference between actual and expected delivery time
- sla_breach: flag indicating if delivery exceeded expected time (1 = breach, 0 = on time)
- order_hour: hour extracted from order_time for time-based analysis
- delivery_time_band: categorizes delivery duration (0–20, 21–30, 31–40, 41+ mins)

---

## measures
- total_orders: total number of orders
- delivery_success_rate: percentage of successfully delivered orders
- sla_breach_pct: percentage of orders exceeding expected delivery time
- average_delivery_time: average delivery duration in minutes
- average_delivery_delay: average delay beyond expected delivery time
- average_prep_time: average vendor preparation time
- cancellation_pct: percentage of cancelled orders
- cancelled_orders: total number of cancelled orders
- delayed_orders: total number of delayed orders
