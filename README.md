# Class-232-joinstatment

inner join: combining all the data from both the tables using inner join
we are getting customer first and last name, on whcih day they ordered the product with the total amount using their id

select customers.first_name, customers.last_name,company_orders.date,company_orders.total_amount
from 
customers
inner join
company_orders
on
customers.id = company_orders.customer_id

we are getting the suppliers details and which products they are supplying to the customer by using inner join
select suppliers.company_name, suppliers.contact_name, suppliers.phone, company_products.name
from
suppliers
inner join
company_products
on
suppliers.id= company_products.supplier_id
