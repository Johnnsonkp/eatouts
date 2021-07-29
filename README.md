#### README

# T3A2 - EatOuts

A food ordering and payment application developed to automate the service and transaction process in the food and service industry.


<hr> 

### Links

[Trello Board](https://trello.com/b/H1F1HAl5/eatouts)


<hr> 

### Purpose
The purpose of eatouts is to automate the service and transaction process in the food and service industry. Customers using the app are able to book a table, make an order, rate and leave a review and make a payment. Business owners are able to keep tabs on available tables, update their menu, collect orders, check out store statistics and collect payments.

<hr> 

### Target Audience
The target audience for the application is my client Joe's cafe within the food and service industry. Another group of our target audience will be foodies.

<hr> 

### Features
1. Role based authentication - Users have access to different elements of the application based on their title (restaurant Owner/staff, customer).

2. Make orders - Customers are able to make multiple orders on the app.

3. Bookings - Customers are able to book a table.

4. Favourites and Reviews - Customers are able to leave reviews and add favourites.

5. Payment system - Customers are ale to make payments using stripe

6. Statistics and Analytics - Store Statistics and Analytics.

7. Blogs - Blogs posts relating to food and tech industry


<hr> 

### Application Architecture Diagram

![Application Architecture Diagram](/public/AAD.png?raw=true "Application Architecture Diagram")


<hr> 

### Dataflow Diagram

- Dataflow diagram Level 0: Overview of the whole system.
![Dataflow diagram Level 0](/public/eatouts-dataflow-level-0.png?raw=true "Dataflow diagram")

- Dataflow diagram Level 1: Resturant owner system.
![Dataflow diagram Level 1](/public/resturant-level-1.png?raw=true "Dataflow diagram")

- Dataflow diagram Level 1: Customers system.
![Dataflow diagram Level 1](/public/customer-lvl-1.png?raw=true "Dataflow diagram")

<hr> 

### User Stories

**__Business owners:__**
- Joe: As a business owner I would like to sign-up for an account that is able to link and connect to my restaurant
- Tina: As a business owner I would like to update my menu on the app
- Julie: As a business owner I would like customers to be able to leave a review and add favorites to their meals
- Tom: As a business owner I would like to access the app on my phone/mobile/tablet
- Jimmy: As a business owner I would like collect payments on the app
- Jake: As a business owner I would like to have my restaurants statistics
 
**__Customer:__**
- Tom: As a customer I would like to select a restaurant to order from
- Steve: As a customer I would like to select a table to be seated
- Ryan: As a customer I would like to order multiple meals 
- Greg: As a customer I would like to add meals to favourites and leave a review
- Dave: As a customer I would like to make a payment for myt order

<hr> 

### Wireframes

- All Users: Landing page
![Landing page](/public/wireframes/landing-page.png?raw=true "Wireframes")

- All Users: Which are you
![Which are you](/public/wireframes/which-are-you.png?raw=true "Wireframes")

- All Users: Register New Account
![Register New Account](public/wireframes/new-user.png?raw=true "Wireframes")

- Customer: Choose a restaurant 
![Choose a restaurant](public/wireframes/choose.png?raw=true "Wireframes")

- Customer: Menu 
![Menu](public/wireframes/customer-menu.png?raw=true "Wireframes")

- Restaurant Owner: Admin 
![Menu](public/wireframes/restaurant-admin.png?raw=true "Wireframes")

- Restaurant Owner: Admin/Order 
![Admin/Order](public/wireframes/restaurant-order.png?raw=true "Wireframes")

- Restaurant Owner: Admin/Tables 
![Admin/Tables](public/wireframes/restaurant-tables.png?raw=true "Wireframes")

- Restaurant Owner: Admin/Menu 
![Admin/Menu](public/wireframes/restaurant-menu.png?raw=true "Wireframes")

- Restaurant Owner: Admin/Reviews 
![Admin/Reviews](public/wireframes/restaurant-reviews.png?raw=true "Wireframes")

<hr> 

### Database Tables

- Database Tables
![Database Tables](public/wireframes/database-tables.png?raw=true "Wireframes")

<hr> 

### Tech Stack

Front-end: HTML, CSS, React
Backend: Rails, Postgresql
Deployment Platform: Heroku
​​Source Control: GitHub
Cloud Storage: Amazon S3
Planning and implementation: Trello board, Adobe XD, Diagram.io

**__Utilities__**

Balsamiq: A mockup tool for wireframing.
Trello: A web-based Kanban-style list-making application.

Business Tools:
Google Docs: A tool for documentation collaboration.



<hr> 

### User Stories

**__Business owners:__**

Joe: As a business owner I would like to sign-up for an account that is able to link and connect to my restaurant
Tina: As a business owner I would like to update my menu on the app
Julie: As a business owner I would like customers to be able to leave a review and add favorites to their meals
Tom: As a business owner I would like to access the app on my phone/mobile/tablet
Jimmy: As a business owner I would like collect payments on the app
Jake: As a business owner I would like to have my restaurants statistics
 
**__Customer:__**

Tom: As a customer I would like to select a restaurant to order from
Steve: As a customer I would like to select a table to be seated
Ryan: As a customer I would like to order multiple meals 
Greg: As a customer I would like to add meals to favourites and leave a review
Dave: As a customer I would like to make a payment for my order


<hr> 

### Screenshots of Trello board

- Part A - Documentation - Started project
![Trello Board](public/trello-board.png?raw=true "Trello Board")