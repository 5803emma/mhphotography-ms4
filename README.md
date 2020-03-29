# Mark Hayes Photography
## Code Institute Milestone Project Four

[![Build Status](https://travis-ci.org/5803emma/mhphotography-ms4.svg?branch=master)](https://travis-ci.org/5803emma/mhphotography-ms4)

<h1 align="center"><img src="/testing/header.png" alt="Mark Hayes Sports Photography Header"></h1>

The deployed project can be found at: https://mhphotography-ms4.herokuapp.com/

### User Experience (UX)
#### Project Purpose

This project is a full stack web application.  The site provides an means to purchase photography services with a secure payment facility.  On the product page, the types of services available can be viewed and filtered; the desired service(s) can be added to the visitors shopping cart.  Users must register in order to complete their purchase(s).  The rationale behind this, is that the nature of the available services require a future interaction between the customer and the photographer (weddings, sporting events etc.), so user will likely understand the need to register their details in order to provide information about their event/project to the photographer.

There are six photography packages available for the user to purchase:
* Drone Photography
* Sports Photography
* Special Events
* Real Estate Photos
* Weddings Photography
* Commercial Photography

The target audience for this application is extremely vast, ranging from couples seeking a wedding photographer to business looking for commercial photography and media outlets that need sports photographs. 

The application uses a postgres database and it is set up with the Django framework.


#### Project Purpose

The goal of the application is to allow users to purchase photography services from the photographer.  Registered users can purchase these packages at a discounted rate.

**The target audiences are:**

* Construction businesses looking for aerial drone footage of projects.
* Media seeking photographs from sporting events for their newspapers/websites. 
* Sports clubs who need/want team photographs and photographs of their club in action on the pitch
* Parents who want a photographer for their childs communion, confirmation, milestone birthdays, graduations etc.
* Real Estate agents who need professional photographs of property they are looking to advertise and sell
* Couples who are getting married
* The hospitality industry who are looking for professional photos that they can use to generate engagements on their social media accounts

#### Business Goals

* Attract new customers
* Have a high performing website that displays the photographers services
* Have a variety of packages to suit all types of customers. 
* Provide and display excellent products that cause recommendations/referrals from previous cleints. 


### User Stories

#### The Photographer

* As a photographer, I want the user to be able to easily identify how much each package is. 
* As a photogrpaher I would like for the user to be able to search the site if they can't find what they're are looking for
* As a photographer, I would like for the user to be able to register with my page.
* As a photographer I want the user to be able to pay for the package online easily. 
* As a photographer I want the user to be able to access my social media feeds so that they can see other photographs that I have taken

#### The User 

* As a user I want to see what the photographer has to offer
* As a user I want to know the prices of the services clearly so I know how much it is before I decide to pay.
* As a user I want an easy way to contact the photographer if I have any queries
* As u user I want to be able to search the website/database for packages available 
* As a user I would like to have access to all data in order to experience what the application has to offer, regardless of device and browser type that I am using. 
* As a user I would like to be able to view the photographer's social media accounts to view their work


#### Design

The background image of a lake just after sunset is appealing and slightly dark. This image allows the cards displaying the packages to stand out and draw the user's eye to them.

##### Font
Using Google Fonts I selected the font Boola-Da throughout the application. 

##### Icons
I utilised Font-Awesome icons for my social links and also for my nav bar

#### Logo
The logo for Mark Hayes photography was designed by the photographer and a friend who is a graphic designer.  This is displayed in nav-bar to give the page a professional look. 

#### Colours
The colours of the site were used to complement and contrast with the background image, which is consistent across the apps.

### Wireframes
Project wireframes were created using MS Paint and can be found in the wireframes folder.



### Features
#### Current Features
- Feature 1 Navigation
    - The nav bar displays a logo for Mark Hayes Photography and links with font-awesome visual icons for the user to register, login and view their cart. 
    - Depending if the user is "logged in" or "logged out" the options displayed will change on the navbar . Should the user be "logged in" the navbar will display a "log out" option and a profile option. 
- Feature 2 Home Page
    - On the home page the user is greeted with images of the photography packages that are available for purchase and the price of each item.  If the user is logged in they will be able to access their user’s account page and also have the option to log out. 
    - Should the user be new they will have the option to register from the home page or subsequently, after adding item(s) to their cart, they will directed to the registration page before being able to purchase the package.
- Feature 3 Search Bar
    - The user has the option from all pages across the site to search for any package they wish to view. 
- Feature 4 Register
    - The data on the site is available to all users however if they wish to purchase a package they must reigster with the apllication first.
    - When a user registers their data is stored in the database and remembered for future log ins. 
    - If a user selects a username that has already been taken they will be prompted to select another unique username. 
- Feature 5 Log In
    - Provided the user has registered they can log in to the site and avail of all the features. 
    - If a user forgets their password they are provided with a link that will direct them to the relevant page where they can enter their email and receive a new password for their account. 
    - If a user logs out of the site they will receive a message to advise them of same. 
- Feature 6 Cart
    - If the user adds a photography package to their cart this will be displayed in their cart item. 
    - If a user wants to edit what they have added to their cart they can amend the quantity. 
    - A user can checkout their purchases by clicking on the cart however if the user is not registered they will be directed to the registration page first.
- Feature 7 Checkout
    - The user is provided with a form at checkout where they can fill in their billing details and credit card details. 
    - This feature is only available to people who have registered with the site.
    - When the user has paid they will receive a message to advise them that they have successfully paid. 
- Feature 8 Log Out
    - If a user wants to log out the option is in the navbar which is displayed across all pages.
    - When they log out they will receive a message to advise them that they have successfully logged out. 
    - Once the user chooses to log out, they will be taken back to the home page as a guest, with the default nav options available for a guest user (Home, Register, Log In, Cart).
    
#### Future Features
- Time was again an issue with this project and unfortunately, there are many more features I would like to include to enhance the appeal and useability of the app.
    - I intended to link a portfolio app where users can view previous work and filter the content by the packages they are interested in
        - Each image in the panel body cards would link to a gallery of previous relevant work/photos
    - I intended to have a landing page as the first thing the user sees.  On that page they will be given information about the service and invited to login to view the portfolio.
    - An availibility calendar would be essential for event and occasion photography.
    - I think a user review section would be a useful feature to new visitors to the site.
    - Registered users would have the function to access their own albums using a unique password.



### Technologies Used

- Amazon AWS Cloud 9
    - Integrated Development Environment
- HTML5
- CSS3
- Javascript/JQuery
- Bootstrap
- Font Awesome
- Python
- Django
- Postgres/SQLite3
    - Postgres was used for the database for the deployed project.
    - SQLite used in test environment
- Git & GitHub
    - Git used for version control
    - GitHub used as a remote repository
- Heroku
    - Used to deploy the project
- Stripe API
    - Used to process user payments 

### Testing

There is Continous Integration with automated testing for each app using Travis. By creating a .travis.yml file and also linking my GitHub repository to my Travis account I was able to achieve this. The Travis Markdown allowed me to see easily whether my code was passing or failing. Each time new code was pushed to Github it was Travis Tested. 
#

I used Chrome DevTools to check the responsiveness of my application.
#

I conducted manual testing as a user by;
 - I registered to the webiste
 - I added a package to my cart
 - I edited the quantity in the cart
 - I proceeded to checkout
 - I filled in the form at checkout, checked that the forms required fields were operating
 - After payment I received a message to advise me that payment was successful
 - I logged into stripe and the payment had gone through successfully. 
#
 - I went onto the application as a guest user(not registered)
 - I added a package to the cart
 - I attempted to go to checkout and I was directed to the log in page which had a link to the registration page if I did not have log in details. 
#
 - Searched for packages through the search box
 - Manually tested both the billing address form and the stripe APA form for required fields and for opertional functions.
 - Checked all links in navbar brought the user to the revelant page
 - Checked the social links directed the user to the correct sites.

### Issues when Testing

1. Due to the acquisition of Cloud 9 by AWS and a resulting change in the IDE, there were problems with the requirements.txt file.  The only fix seemed to be to manually go through each entry and delete the ones that were not required.

2. If the quantity of the cart is left blank and the user presses "Add" this returns an error: invalid literal for int() with base 10: ''
Similarly, in the adjust_cart view, if the quantity of the cart is 1 and no amendment is made, when the user presses "Amend" the same error is returned (see image below).
Unfortunately I noticed this error on deadline day and did not have time to fix it.

<h1 align="center"><img src="/testing/valueerror.png" alt="Value Error when Testing"></h1>

### Deployment

* Within the AWS Cloud 9 IDE I opened the terminal and using git I pushed to my <a href="https://github.com/5803emma/mhphotography-ms4">repository</a> on Github. 
* I then opened Heroku and created a new app, set config variables and deployed the application to the Heroku platform.
* In Heroku deployment method was set to Github with automatic deploys set from the master branch. 
* The app was then deployed and can be viewed at this link: "https://mhphotography-ms4.herokuapp.com/".

#### To clone the repository:
- Install Python and Git.  
- Set up an account with AWS and Stripe.
* Select the Repository from Github.
* Click on the green "Clone or Download" button
* Click on the "Clipboard Icon" to the right of the Git URL to copy the web URL.
* Open your IDE and navigate to the terminal window
* Change the directory to where you want to clone the repository to.
* Paste the copied Git URL into the desired destination and click "Ok".
* Set the following environment variables

```
# env.py

import os

os.environ.setdefault('SECRET_KEY', <key here>)
os.environ.setdefault('DEBUG', <True/False>)
os.environ.setdefault('STRIPE_PUBLISHABLE', <key here>)
os.environ.setdefault('STRIPE_SECRET', <key here>)
os.environ.setdefault('STRIPE_SUCCESS_URL', <URL here>)
os.environ.setdefault('STRIPE_CANCEL_URL', <URL here>)
os.environ.setdefault('AWS_ACCESS_KEY_ID', <key here>)
os.environ.setdefault('AWS_SECRET_ACCESS_KEY', <key here>)
```

* Add env.py to the .gitignore file
* Migrate models to create database tables
* Create superuser account to access the Django Admin Panel
* Run the server locally

## Credits

- I used the Full Stack Frameworks With Django module tutorial videos to compile the site.
- All photos are origial images from Mark Hayes Photography and Mark Hayes Sports Photography.

## Thanks

- Thanks to all the Code Institute staff, in particular Student Care for their patience and for being so accommodating.
- Thanks to my mentor and to the Slack community for being so knowledgeable, supportive and helpful.