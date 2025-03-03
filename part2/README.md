# Project: HBnB - BL and API

## Objective:

Creating a Web Application version of an Airbnb 

## Description:

This HBnB simulates a more simplified version of an Airbnb, due for it being full-stack web application.

It also focuses on building s RESTful API with Flask, which adds a persistent data storage and structuring the app to be easy to scale and to maintain.

## Feature:

* Authentication and Management for users: Safe user sign-up, login and access management.

* RESTful API: Endpoint versions for smooth integration with frontend or external services.

* CRUD Operation: It can Create, Read, Update, and Delete functionalities for Places, Amenities, Users and Reviews.

* Facade Pattern: It simplifies the service layer interactions 

# Project Structure

```
hbnb/
├── app/
│   ├── __init__.py
│   ├── api/
│   │   ├── __init__.py
│   │   ├── v1/
│   │       ├── __init__.py
│   │       ├── users.py
│   │       ├── places.py
│   │       ├── reviews.py
│   │       ├── amenities.py
│   ├── models/
│   │   ├── __init__.py
│   │   ├── user.py
│   │   ├── place.py
│   │   ├── review.py
│   │   ├── amenity.py
│   ├── services/
│   │   ├── __init__.py
│   │   ├── facade.py
│   ├── persistence/
│       ├── __init__.py
│       ├── repository.py
├── run.py
├── config.py
├── requirements.txt
├── README.md
```

# Contributors:

* Julio J. Bonilla Chaparro
