# E-commerce Data Analysis Project

## Introduction, motivation, goals.


## Few words about our data

<h3> olist_customers_datase.csv </h3> - table with unique customers and their data

customer_id — our customers idendification (id number)

customer_unique_id —  unique identity number (like a real ID number)

customer_zip_code_prefix —  postal code of our customer

customer_city —  city to deliver

customer_state —  state to deliver


<h3> olist_orders_dataset.csv </h3> —  order table

order_id —  unique order number (check number)

customer_id —  cutomers identification number

order_status —  order status (statuses will be shown later)

order_purchase_timestamp —  when order created

order_approved_at —  time when order is approved

order_delivered_carrier_date —  when order transfered to delivery company

order_delivered_customer_date —  when delievred

order_estimated_delivery_date —  estimated time of our delivery


<h3> olist_order_items_dataset.csv </h3> —  items in orders

order_id —  unique order number (check number)

order_item_id —  item's id number inside one order

product_id —  item's id (analoque: barcode of item)

seller_id — item's manufacturer's id

shipping_limit_date —  maximum delivery date by the seller to transfer the order to the logistics partner

price —  price for one piece of item

freight_value —  weight of item


Unique order statuses in olist_orders_dataset table:

created
approved
invoiced
processing
shipped
delivered
unavailable
canceled
(I guess this status names speaks for themselves)
