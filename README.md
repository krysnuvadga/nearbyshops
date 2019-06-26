# NearByShops
Django and GeoDjango  location-based web application that lists the shops closest to a user’s location.

## Goal
- Use Django to build a simple web application from scratch

- Use the GeoDjango sub-framework to implement geolocation features in your Django application

- Use a spatial database (PostgreSQL and PostGIS) to get benefits from the spatial features and easily implement location-aware web apps

## Tools
1. The Python programming language
2. The Django web framework
3. The PostgreSQL database for persisting data
4. The PostGIS extension for supporting spatial features in the PostgreSQL database
5. pip for installing dependencies
6. The venv module for managing a virtual environment
7. Docker for installing PostgreSQL and PostGIS

## Dependencies
 GEOS, GDAL, and PROJ.4
 
 ## Project Setup
 #### Setting up a Spatial Database With PostgreSQL and PostGIS
 Quickly create a PostgreSQL and PostGIS database using the kartoza postgis docker image, using the command:
 `docker run --name=postgis -d -e POSTGRES_USER=user001 -e POSTGRES_PASS=123456789 -e POSTGRES_DBNAME=gis -p 5430:5430 kartoza/postgis:9.6-2.4`
#### Creating and Activate a Virtual Environment
`python3 -m venv env`
`source env/bin/activate`
#### Installing Django
`pip install django`
#### Clone the source code
`git clone https://github.com/username/nearbyshops.git`
