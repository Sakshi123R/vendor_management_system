# Description
The Vendor Management System, developed using Django, is a web application designed for streamlined vendor relationship management.

It encompasses functionalities for managing vendor profiles, tracking purchase orders, and evaluating vendor performance.

Users can create, update, and delete vendor profiles, monitor purchase orders, and assess vendor performance metrics such as on-time delivery rate, quality rating average, average response time, and fulfillment rate.

# Roadmap
- Start and Plan: Understand the project scope and set up the basic structure.

- Vendor Setup: Create a system to manage vendor information and test it.

- Purchase Order Management: Develop purchase order forms and check their functionality.

- Performance Evaluation: Add a scoring system for vendors and calculate scores dynamically.

- Historical Tracking: Include a history feature to track vendor performance over time.

- Testing Phase: Conduct thorough testing, find and fix bugs.

- Deployment: Put the system online for use.

- Maintenance: Keep an eye on the system, fix issues, and assist users.

# Features
- User and Admin can add or remove vendors
- User and Admin can delete vendors
- User and Admin can update vendors
- User can search for specific vendor through their name and address.
- Admin can give the perfect calculations for performance
- Easy to use
- API endpoints can be checked using Django ORM
- User can add vendor.
- User and admin can view order details.
- User and admin can delete order details
- User and admin can update order details
- User and admin can search for order through po_number and vendor name.
- API Reference
# Vendor Profile Management
- POST /api/vendors/: Create a new vendor.
-  GET /api/vendors/: List all vendors.
- GET /api/vendors/{vendor_id}/: Retrieve a specific vendor's details.
- PUT /api/vendors/{vendor_id}/: Update a vendor's details.
- DELETE /api/vendors/{vendor_id}/: Delete a vendor.
-  UPDATE /api/vendors/{vendor_id}/: Update a vendor.
# Purchase Order Tracking
 -  POST /api/purchase_orders/: Create a new order.
 - GET /api/purchase_orders/: List all orders.
 - GET /api/purchase_orders/{vendor_id}/: Retrieve a specific order's details.
 - PUT /api/purchase_orders/{vendor_id}/: Update a order's details.
 - DELETE /api/purchase_orders/{vendor_id}/: Delete a order.
 - UPDATE /api/purchase_orders/{vendor_id}/: Update a order.
# Tech Stack
Stack: Python, Django, dbsqlite3

Server: localhost:8000

# Installation
```http
  python -m venv venv

source venv/Scripts/activate

pip install django

pip install djangorestframework

pip install -r requirements.txt

python manage.py makemigrations 

python manage.py migrate

python manage.py createsuperuser 

python manage.py runserver

http://localhost:8000/vendors/  --for vendor list

http://localhost:8000/admin  --for admin
```

# Screenshots
# Vendor_list.html - One can create new vendor here.
<img width="1080" alt="image" src="https://github.com/Sakshi123R/vendor_management_system/assets/37693165/708c618e-e0de-4464-88f5-d83868941725">
# Displaying vendors profiles generated through faker library.
<img width="1080" alt="image" src="https://github.com/Sakshi123R/vendor_management_system/assets/37693165/2fea757b-f97a-42df-bfbe-91891c6a58e6">
# Updating contact details of Brooke Evans.
<img width="1080" alt="image" src="https://github.com/Sakshi123R/vendor_management_system/assets/37693165/a067ab9e-e2dc-47c2-8d7b-fd89179e12cd">
# Contact details updated
<img width="1080" alt="image" src="https://github.com/Sakshi123R/vendor_management_system/assets/37693165/fb2325a1-61e8-4cf4-b59b-b74c6bcae021">
# Create new order here.
<img width="1080" alt="image" src="https://github.com/Sakshi123R/vendor_management_system/assets/37693165/69073336-20a0-4ef1-82ce-dc6190638305">
# Deleting vendor Nathon Hansen
<img width="1080" alt="image" src="https://github.com/Sakshi123R/vendor_management_system/assets/37693165/d072bb94-b316-443f-8d5d-275ef75d3544">
# Deleted
<img width="1080" alt="image" src="https://github.com/Sakshi123R/vendor_management_system/assets/37693165/ad78abb4-66b7-44dc-946e-f4c625b1c77b">
# Searching records that exists having north
<img width="1080" alt="image" src="https://github.com/Sakshi123R/vendor_management_system/assets/37693165/b3465216-c352-4e32-9ee1-d3c7f9a79134">
# Fethched one record of a vendor.
<img width="1080" alt="image" src="https://github.com/Sakshi123R/vendor_management_system/assets/37693165/6cc17274-89a5-4f86-a618-08a96b1e16e4">
# Admin page diaplaying details of vendors.
<img width="1080" alt="image" src="https://github.com/Sakshi123R/vendor_management_system/assets/37693165/ff7629e2-36f6-47a0-9329-bdf90a2760d2">
# Admin page diaplaying details of purchase orders.
<img width="1080" alt="image" src="https://github.com/Sakshi123R/vendor_management_system/assets/37693165/b34e7cb4-6554-4852-bf70-7dcee3b50201">
# Displaying orders here.
<img width="1080" alt="image" src="https://github.com/Sakshi123R/vendor_management_system/assets/37693165/aa74d3ce-a324-4204-9af1-2ede700b617f">
# NOTE- We can also perform crud operations in this page as well.

# For more queries mail me- sakshirekhikandhari@gmail.com,
                            rekhisakshi8@gmail.com













