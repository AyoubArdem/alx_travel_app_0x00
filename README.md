# ALX Travel App 0x00

This project defines database models, serializers, and a seeder command for sample data.

##  Features

- Listing model
- Booking model
- Review model
- Serializers for Listing & Booking
- Seed command to populate database



##  Installation

bash
git clone <your_repo_url>
cd alx_travel_app_0x00
pip install -r requirements.txt
`



##  Apply Migrations

bash
python manage.py makemigrations
python manage.py migrate



##  Seed the Database

bash
python manage.py seed


This will create 10 sample listings with a host user.



##  Generated Models

* Listing
* Booking
* Review



## Serializers

* ListingSerializer
* BookingSerializer


##  Test API

Run server:

bash
python manage.py runserver




