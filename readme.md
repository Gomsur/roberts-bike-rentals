# Robert's Bike Rentals

Welcome to Robert's Bike Rental. We have bikes of all sizes and accessories for you and your loved ones. Explore the local neighborhood in style & comfort on our bikes.

![Robert's Bike Rental](http://104.248.100.154/static/img/bike-shop-concept-with-bicycles.jpg)

Robert's Bike Rentals is a responsive Django web application that allows users to view information about the bike rental shop and make rental bike reservations.

Robert's Bike Rentals is hosted in the Digital Ocean Cloud for public use.

Click the link below to access Robert's Bike Rentals and the bike collection.

[Access Robert's Rental Bikes](http://104.248.100.154/)

## Table Of Contents

- [Robert's Bike Rentals](#robert-s-bike-rentals)
  * [Robert's Bike Rentals Tech Stack](#robert-s-bike-rentals-tech-stack)
  * [Robert's Bike Rentals Features & Goals](#robert-s-bike-rentals-features---goals)
    + [Bike Rental Guest Goals](#bike-rental-guest-goals)
    + [Bike Rental Customer Goals](#bike-rental-customer-goals)
    + [Bike Rental Employee Goals](#bike-rental-employee-goals)
    + [Bike Rental Site Administrator Goals](#bike-rental-site-administrator-goals)
  * [Robert's Bike Rentals User Stories](#robert-s-bike-rentals-user-stories)
    + [Bike Rental Guest User Stories](#bike-rental-guest-user-stories)
    + [Bike Rental Customer User Stories](#bike-rental-customer-user-stories)
    + [Bike Rental Employee User Stories](#bike-rental-employee-user-stories)
    + [Bike Rental Site Administrator User Stories](#bike-rental-site-administrator-user-stories)
  * [User Interface Design](#user-interface-design)
    + [Theming And Colors](#theming-and-colors)
    + [Wire Frames](#wire-frames)
    + [Standard Mobile Page Wireframe](#standard-mobile-page-wireframe)
    + [Standard Desktop Page Wireframe](#standard-desktop-page-wireframe)
  * [Robert's Rental Bike Store Pages](#robert-s-rental-bike-store-pages)
    + [Home Page](#home-page)
    + [About Page](#about-page)
    + [Accessories Page](#accessories-page)
    + [Login Page](#login-page)
    + [Register Page](#register-page)
    + [Reserve Bikes Page](#reserve-bikes-page)
    + [Manage Bikes Page](#manage-bikes-page)
  * [Security For Robert's Bike Rentals](#security-for-robert-s-bike-rentals)
    + [Super Admin Users](#super-admin-users)
    + [Standard Authenticated Users](#standard-authenticated-users)
  * [Agile Project Management](#agile-project-management)
  * [Known Bugs](#known-bugs)
    + [New Accounts Can Not View Bikes To Rent](#new-accounts-can-not-view-bikes-to-rent)
  * [Robert's Rental Bikes Deployment](#robert-s-rental-bikes-deployment)
    + [Ubuntu Linux Server](#ubuntu-linux-server)
    + [Deploy Postgres Database](#deploy-postgres-database)
    + [Deploying Robert's Rental Bike](#deploying-robert-s-rental-bike)
    + [Preview Robert's Rental Bikes](#preview-robert-s-rental-bikes)
  * [Credits](#credits)
  * [Quick Start Installation](#quick-start-installation)

## Robert's Bike Rentals Tech Stack

robert's rental bikes is built with the following technologies.

* `hosting` { digital-ocean ubuntu }

    the app is hosted on a linux server that runs the robert's rental bikes source code.

* `database` { postgres pgadmin4 }

    the app uses a postgres database. pgadmin is used to monitor and manage the postgres database.

* `backend` { django4 } 

    the app backend is django mvc.

* `interface` { html bootstrap bootswatch liquid }

    the app user interface is built html pages customized with liquid templating to render backend content.

## Robert's Bike Rentals Features & Goals

![Robert's Bike Rental Home](/docs/screenshots/home.png)

### Bike Rental Guest Goals

Features for end users of the robert's rental bikes django application:

    [`store info`] Guests can see bike rental store information

    [`store info`] Guests can see rental bike accessories

    [`accounts`] Guests can register a new account to reserve rental bikes

    [`accounts`] Guests can login in to existing account to reserve rental bikes

### Bike Rental Customer Goals

    [`bike rental`] Authenticated customers can view reservation status of all bikes

    [`bike rental`] Authenticated customers can reserve a rental bike

    [`bike rental`] Authenticated customers can cancel their reserved bike reservations

### Bike Rental Employee Goals

Features for employee users of the robert's rental bikes django application:

    [`crud`] Can manage rental bikes in the system

    [`crud`] Can manage bike reservations in the system

### Bike Rental Site Administrator Goals

Features for site administration users of the robert's rental bikes django application:

    [`cloud`] Can manage the resources in the digital ocean cloud

    [`linux`] Can manage the system processes on the linux server

    [`manage.py`] Can manage the store employee users in the django system

## Robert's Bike Rentals User Stories

### Bike Rental Guest User Stories

    As a bike rental guest i can see information about the bike rental store so that i can make an informed decision about rental bikes

    As a bike rental guest i can see rental bike accessories so that i can know my options for accessories for my rental bike

    As a bike rental guest i can create a new account with robert's bike rentals so that i can manage bike rentals

    As a bike rental guest i can log in an existing account on robert's bike rentals so that i can reserve a rental bike

### Bike Rental Customer User Stories

    As a bike rental customer i can view the reservation status of all bikes so that i can select a rental bike available for purchase

    As a bike rental customer i can reserve an available rental bike so that i can use this rental bike as a later time

    As a bike rental customer i can cancel a previously made rental bike reservation so that i can return a rental bike i do not need

### Bike Rental Employee User Stories

    As a bike rental employee i can manage the rental bikes in the systems so that i modify rental bikes as needed

    As a bike rental employee i can manage the bike reservations in the system so that i can get see which bikes are rented

    As a bike rental employee i can return a customer's rental bike so that assist our customer with bike reservations

### Bike Rental Site Administrator User Stories

    As a bike rental site administrator i can manage the digital ocean cloud resources so that servers can be turned on and off

    As a bike rental site administrator i can manage the linux server processes so that databases and applications can be turned on and off

    As a bike rental site administrator i can manage the superadmins in the django application so that store employees can be created

## User Interface Design

Robert's Rental Bikes uses standard html pages with liquid template.

below are details about the interface, it's design, and considerations.

### Theming And Colors

Colors for Robert's rental bikes were chosen from options on bootswatch.

Bootswatch provides the color theming used across the application.

Robert's rental bikes uses the `lumen` theme set.

The lumem theme can be found and downloaded here:

```
https://bootswatch.com/lumen/
```

### Wire Frames

Initial mockups of the robert's rental bikes application be found below.

the initial design focused on a simple menu, vivid imagery, and multiple calls to actions.

Wireframes for different views can be seen here:

### Standard Mobile Page Wireframe 

![Mobile Wireframe](/docs/wireframes/wireframe-mobile.png)

### Standard Desktop Page Wireframe

![Desktop Wireframes Bike Rental Home](/docs/wireframes/wireframe-desktop.png)

## Robert's Rental Bike Store Pages

### Home Page

the home page is the initial landing page for robert's rental bikes. the home provides text about robert's rental bikes and what we offer.

![home page](/docs/screenshots/home.png)

### About Page

the about page provides detail about robert's rental bikes. the about page has a call to action for the user to reserve a bike.

![about page](/docs/screenshots/about.png)

### Accessories Page

the accessories page lists a static collection of accessories for the robert's bike rental users. the accessories page has a call to action for the user to reserve a bike.

![accessories page](/docs/screenshots/accessories.png)

### Login Page

the login page is a standard login form. the user provides their username and password. the login page provides a call action to sign up for a new account.

![login page](/docs/screenshots/login.png)

### Register Page

the register page is a standard register form. the user provides their username and password. the register page provides a call action to log in with an existing account.

![register page](/docs/screenshots/register.png)

### Reserve Bikes Page

the reserve page allows the user to see each of the bikes in the store and it's rentail availability. the reserve page allows the user to reserve a bike listed as available. the reserve page allows the users to cancel a currently reserved bike owned by them.

![reserve page](/docs/screenshots/reserve.png)

### Manage Bikes Page

the manage bikes page allows a super user to see each of the bikes in the store and it's rentail availability. the manage bikes page allows a super user to return a rental reservation made by a customer.

![manage page](/docs/screenshots/manage.png)

## Security For Robert's Bike Rentals

Robert's Bike Rentals has a few simple security rules.

### Super Admin Users

    [`superadmins`] only superadmins can manage bikes and accounts

    [`superadmins`] only superadmins may return other user's rentals

### Standard Authenticated Users

    [`authenticated`] only authenticated users can reserve a bike

    [`authenticated`] only authenticated users can their own rentals

    [`authenticated`] authenticated user sessions are invalidated after two minutes of inactivity and the user must re-authenticate

## Agile Project Management

Robert's rental bikes has an agile project tracking board with each of the user stories and their current progress.

Click the link below to view the agile board.

[Agile Project Management](/docs/agile.md)

## Known Bugs

the following are bugs currently known within the robert's rental bikes application.

### New Accounts Can Not View Bikes To Rent

	on the first login for a new user, there are no bikes available to view or reserve.

	Solution #1: The new user has to log out and then log back in. Then the bikes are available to view and manage.

	Solution #2: The new user needs to manually click on the 'reserve bike` link.

## Robert's Rental Bikes Deployment

Robert's Rental Bikes is hosted on an ubuntu linux server in the `Digital Ocean` cloud.

### Ubuntu Linux Server

The Ubuntu Linux Server has the following specs:

    ip address / 104.248.100.154

    os / ubuntu linux 22.04

    ram / 2 GiB

    cpu / 1 vCPU

    disk / 50 GiB

### Deploy Postgres Database

A postgress database is used for backend storage.

The postgress database uses docker compose to run:

```yaml
version: "3"

services:

    roberts-bike-rentals-postgres:

        container_name: roberts-bike-rentals-postgres
        
        image: postgres:14.1-alpine

        restart: always

        user: root

        environment:

            - POSTGRES_USER=robertsbikerentals

            - POSTGRES_DB=robertsbikerentals

            - POSTGRES_PASSWORD=roberts!bike!rentals

        ports:

            - "5432:5432"

        volumes: 

            - ./volume/postres:/var/lib/postgresql/data
 
    roberts-bike-rentals-pgadmin4:

        container_name: roberts-bike-rentals-pgadmin4

        user: root

        image: dpage/pgadmin4
        
        restart: always

        ports:
        
            - "5480:80"
            
        environment:
        
            PGADMIN_DEFAULT_EMAIL: robert@robertsbikerentals.com
            
            PGADMIN_DEFAULT_PASSWORD: roberts!bike!rentals

        volumes:
        
            - ./volume/pgadmin4:/var/lib/pgadmin            
```

running the docker-compose script to start the database.

```bash
docker-compose up -d
```

see the running docker containers on the linux server.

```bash
docker ps
```

### Deploying Robert's Rental Bike

The robert's rental bikes application is executed by pulling the robert's rental bikes source code from GitHub and executing the `quick-start.sh` script using the linux terminal.

get the code from github.

```bash
git clone https://github.com/Gomsur/roberts-bike-rentals.git
```

enter the repo directory.

```bash
cd roberts-bike-rentals
```

```bash
sudo nohup ./quick-start.sh &
```

nohup runs the application in the background after disconnecting from the terminal. if you don't put nohup, then the app closes when you disconnect.

### Preview Robert's Rental Bikes

![Robert's Bike Rental Home](/docs/screenshots/home.png)

Robert's Bike Rentals is deployed and available for usage.

Click the link below to access Robert's Bike Rentals.

[Access Robert's Rental Bikes](http://104.248.100.154/)

## Credits

The Robert's rental bike application was build w/ help from the following resources across the internet.

| website | how the site helped |
|---------|---------------------|
|[Bootswatch](https://bootswatch.com/)|bootstrap compatible prebuild color theming and css|
|[Digital Ocean](https://www.digitalocean.com/community/tutorials)|cloud server hosting and tutorials|
|[Internet Tutorials](/docs/tutorials.md)|various tutorials from the internet with how-to help and information|
|[Stock Imagery](/docs/attribution.md)|free stock imagery from the internet, with attribution.|
|[TOC Generator](https://ecotrust-canada.github.io/markdown-toc/)|github wiki toc generator.|

## Quick Start Installation

You can run Robert's Rental Bikes at home.

Follow the instructions below on an Ubuntu Linux server.

[Quick Start Guide](/docs/quick-start.md)
