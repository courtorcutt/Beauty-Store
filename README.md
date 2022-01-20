# Beauty-Store - Instructions to review backend is under the smoke test (video)
Django + React + Python + JavaScript + HTML/CSS

Administrator has ability to create “shipments” and assign inventory to the shipment. The inventory and orders placed are kept track of. 

https://beauty-store-project-django.herokuapp.com/

https://user-images.githubusercontent.com/72311187/141941610-a9c9ee49-decb-42f6-a422-7f5a3010eee1.mov

Instructions to review backend:

- download repository
- run python3 manage.py createsuperuser
- you will be asked for a username and password (this is setting up your administrator profile)
- then run python manage.py runserver
- then go to 127.0.0.1:8000/admin
- you will see the image below
<img width="558" alt="Screen Shot 2022-01-20 at 3 11 41 PM" src="https://user-images.githubusercontent.com/72311187/150366105-1cf68284-f500-4528-b614-ebbce967f100.png">
- log in with your super user account
<img width="663" alt="Screen Shot 2022-01-20 at 3 19 53 PM" src="https://user-images.githubusercontent.com/72311187/150367619-eb7c67a2-7dd2-4d03-8ca3-7c0967b5c76f.png">
- you can then add products
<img width="1057" alt="Screen Shot 2022-01-20 at 3 20 39 PM" src="https://user-images.githubusercontent.com/72311187/150367749-7b607710-98ed-4c53-9ffc-eec2cd4b17d1.png">
- create customers (below are tests)
<img width="1067" alt="Screen Shot 2022-01-20 at 3 21 23 PM" src="https://user-images.githubusercontent.com/72311187/150367877-f281429a-ca41-4efd-9c1f-78f3e586d2f8.png">
You can also create orders and review orders, etc.
<img width="299" alt="Screen Shot 2022-01-20 at 3 22 09 PM" src="https://user-images.githubusercontent.com/72311187/150368030-081b6c2c-49ec-42a9-8cf5-ddce545f6d8c.png">

The code for the models is visible below and in /store/models.py :
<img width="569" alt="Screen Shot 2022-01-20 at 3 23 03 PM" src="https://user-images.githubusercontent.com/72311187/150368181-b0355c7d-006c-497d-babf-d1e205b93b95.png">
