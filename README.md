<p align="center">
  <p align="center">
      <img src="https://github.com/ruchi-115/ZEB/blob/main/static_in_env/img/logo1.png" alt="ZEB" height="72">
  </p>
  <p align="center">
    ZEB - DJANGO ECOMMERCE WEBSITE
  </p>
</p>

## Quick demo

[![alt text](https://github.com/ruchi-115/ZEB/blob/main/readme_zebgif.gif "Logo")]

---
## Distinctiveness and Complexity (Features):
- ZEB is a full stack e-commerce web application with bootstrap, html, css and js on the frontend and django on the backend.
- Sqlite is used as Database.
- The Items from Order to Delivery Tracked.
- Paypal Payment Gateway Integrated.
- Login and Signup system integrated using django-allauth module.
- Slug field used to store and generate valid URLs for your web pages.
- Items Tracks covered:
    1. Item added to cart
    2. Adding a billing address (Failed checkout)
    3. Payment (Preprocessing, processing, packaging etc.)
    4. Being delivered
    5. Received 

## Project Summary
The website displays products. Users can add and remove products to/from their cart while also specifying the quantity of each item. They can then enter their address and choose Paypal to handle the payment processing.

---

## Running this project

To get this project up and running you should start by having Python installed on your computer. It's advised you create a virtual environment to store your projects dependencies separately. You can install virtualenv with

```
pip install virtualenv
```

Clone or download this repository and open it in your editor of choice. In a terminal (mac/linux) or windows terminal, run the following command in the base directory of this project

```
virtualenv env
```

That will create a new folder `env` in your project directory. Next activate it with this command on mac/linux:

```
source env/bin/active
```

Then install the project dependencies with (Note: Dont forget to add your paypal testing client_id for payment to work)

```
pip install -r requirements.txt
```

Now you can run the project with this command

```
python manage.py runserver
```

