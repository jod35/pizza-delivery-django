## PIZZA DELIVERY API



## ROUTES TO IMPLEMENT
| METHOD | ROUTE | FUNCTIONALITY |ACCESS|
| ------- | ----- | ------------- | ------------- |
| *POST* | ```/auth/signup/``` | _Register new user_| _All users_|
| *POST* | ```/auth/jwt/create/``` | _Login user_|_All users_|
| *POST* | ```/auth/jwt/refresh/``` | _Refresh the access token_|_All users_|
| *POST* | ```/auth/jwt/verify/``` | _Verify the validity of a token_|_All users_|
| *POST* | ```/orders/``` | _Place an order_|_All users_|
| *POST* | ```/orders/``` | _Get all orders_|_All users_|
| *GET* | ```/orders/{order_id}/``` | _Retrieve an order_|_Superuser_|
| *PUT* | ```/orders/{order_id}/``` | _Update an order_|_All users_|
| *PUT* | ```/orders/update-status/{order_id}/``` | _Update order status_|_Superuser_|
| *DELETE* | ```/orders/delete/{order_id}/``` | _Delete/Remove an order_ |_All users_|
| *GET* | ```/orders/user/{user_id}/orders/``` | _Get user's orders_|_All users_|
| *GET* | ```/orders/user/{user_id}/order/{order_id}/``` | _Get user's specific order_|
| *GET* | ```/docs/``` | _View API documentation_|_All users_|
