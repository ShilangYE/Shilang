## The backend

Use django as backend framework.

The functionalities:
- REST API, returns json via `/api/users` and `/api/orders` routes.
- CRUD operations on User objects (username : String (unique), password : String, admin: Boolean).
- CRUD operations on Order objects (name : String, price : Float, user : User).

## The frontend

Develop a web interface that uses the api developed.

The functionalities:
- Implement a user screen with a user table.
- Implement an order screen with an order table.
- Sidebar with links to the two screens.
