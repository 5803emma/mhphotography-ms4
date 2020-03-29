# Mark Hayes Photography
## Code Institute Milestone Project Four

[![Build Status](https://travis-ci.org/5803emma/mhphotography-ms4.svg?branch=master)](https://travis-ci.org/5803emma/mhphotography-ms4)

The deployed project can be found at: https://mhphotography-ms4.herokuapp.com/

### User Experience (UX)
#### Project Introduction

Mark Hayes Photography is an online platform that hosts a portfolio of Mark's previous work.

The user will be able to view the photographs and peruse the albums however if they wish to purchase the photographer's services they must register with the site in order to complete the purchase. 

There are six portfolios available for the user to purchase:
* Drone Photography
* Sports Photography
* Special Events
* Real Estate Photos
* Weddings Photography
* Commercial Photography

The target audience for this application is extremely vast, ranging from couples seeking a wedding photographer to business looking for commercial photography and media outlets that need sports photographs. 

The application uses a postgres database and it is set up with the Django framework.


#### Project Goal

The goal of the application is to display the variety and quality of Mark's work to attract new clientele. 

**The target audiences are:**

* Construction businesses looking for aerial footage of real estate.
* Media seeking photographs from sporting events for their newspapers/websites. 
* Sports clubs who need team photographs 
* Parents who want a photographer for their childs communion, confirmation, milestone birthdays, graduations etc.
* Real Estate agents who need professional photographs of property they are looking to advertise and sell
* Couples who are getting married
* The hospitality industry who are looking for professional photos that they can advertise on their social media accounts

#### Business Goals

* Attract new customers
* Have a high performing website that displays the best of the photographers portfolio
* Have a large variety of packages to suit a vast amount of customers. 
* Provide and display excellents products that cause recommendations/referrals from previous cleints. 


### User Stories

#### The Photographer

* As a photographer, I want to display all of my work to entice people to hire me. 
* As a Photographer, I want to display the variety of skills that I have in different areas
* As a photogrpaher, I would like my clients to able to see the quality of all my previous works
* As a Photographer, I want the customer to be able to find my contact details easily in order to avail of my services. 
* As a photographer, I want the user to be able to easily identify how much each package is. 
* As a photogrpaher I would like for the user to be able to search the site if they can't find what they're are looking for
* As a photographer, I would like for the user to be able to register with my page.
* As a photographer I want the user to be able to pay for the package online easily. 
* As a photographer I want the user to be able to access my social medias so that they can see other photographs that I have taken that may not be displayed in one of the protfolios on the website

#### The User 

* As a user I want to see what the photographer has to offer
* As a user I want to know the prices of the services clearly so I know how much it is before I decide to pay.
* As a user I want an easy way to contact the photographer if I have any queries
* As a user I want to see previous work done by the photographer. 
* As u user I want to be able to search the website/database for packages available 
* As a user I would like to have access to all data in order to experience what the application has to offer, regardles sof device and browser type that I am using. 
* As a user I would like to be able to view the photographer's social media accounts to view works that may not be available on the website and read reviews of the photographer's work


#### Design

As this is a photography application I wanted the photographer's work to be prevelant in the design. Keeping this in mind I used a background image of a lake just after sunset, so the image is slightly dark. This image allows the cards displaying the packages to stand out and draw the user's eye to them.

##### Font
Using Google Fonts I selected the font Boola-Da throughout the application. 

##### Icons
I utilised font-awesome icons for my social links and also for my nav bar

#### Logo
I designed a logo for Mark Hayes photogrpahy and I have displayed this in my nav-bar, I feel this gives the page a professional look. 

#### Colours
As the background image is slightly darker I decided to make my navbar and footer a bright blue colour in order for them to stand out to the user. Using font #fff the text stands out and makes it easy for the user to see where they can navigate to from whatever page they are on. 

### Wireframes




### Features
#### Current Features
- Feature 1 Navigation
    - The nav bar displays a logo for Mark Hayes Photography and links with social icons for the user to register, login and view cart. 
    - Depending if the user is "logged in" or "logged out" the options displayed will change on the navbar . Should the user be "logged in" the navbar will display a "log out" option and a profile option. 
- Feature 2 Home Page
    - On the home page the user is greeted with images of the packages that is available to them and the prIf the user is logged in they will be able to access their user’s account page and also have the option to log out. 
    - Should the user be new they will have the option to register fromn the home page or subsequently after adding items to their cart they will directed to the registration page before being able to purchase the package.
- Feature 3 Search Bar
    - The user has the option from all pages across the site to search for any package they wish to view. 
- Feature 4 Register
    - The data on the site is available to all users however if they wish to purchase a package they must reigster with the apllication first.
    - When a user registers their data is stored in the database and remembered for future log ins. 
    - If a user selects a username that has already been taken they will be prompted to select another unique username. 
- Feature 5 Log In
    - Provided the user has registered they can log in to the site and avail of all the features. 
    - If a user forget's their password they are provided with a link that will direct them to the relevant page where they can enter their emailand receive a new password for their account. 
    - If a user logs out of the site they will receive a message to advise them of same. 
- Feature 6 Cart
    - If the user adds a package to their cart this will be displayed in their cart item. 
    - If a user wants to edit what they have added to their cart they can amend the quantity. 
    - A user can checkout their purchases by clicking on the cart however if the user is not registered they will be directed to the registration page first.
- Feature 7 Checkout
    - The user is provided with a form at checkout where they can fill in their billing details and credit card details. 
    - This feature is only available to people who have registered to Mark Hayes Photography
    - When the user has paid they will receive a message to advise them that they have successfully paid. 
- Feature 8 Log Out
    - If a user wants to log out the option is in the navbar which is displayed across all pages.
    - When they log out they will receive a message to advise them that they have successfully logged out. 
    - Once the user chooses to log out, they will be taken back to the home page as a guest, with the default nav options available for a guest user (Home, Reviews, Register, Log In, Merchandise, Cart).
    
#### Future Features



### Technologies Used

- Amazon AWS Cloud 9
    - Amazon AWS Cloud 9 
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

I set up Continous Integration which automated testing for every app using Travis. By creating a .travis.yml file and also linking my GitHub repository to my Travis account I was able to achieve this. The Travis Markdown allowed me to see easily whether my code was passing or failing. Each time new code was pushed to Gothub it was Travis Tested. 
#

I used Chrome DevTools to check the responsiveness of my application. I checked that the media queries were operating on all screens from Samsung S5 to Desktop without any issues. 
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
 

### Deployment

* Within Cloud 9 IDE I opened the terminal and using git I pushed to my <a href="https://github.com/5803emma/mhphotography-ms4">repository</a> on Github. 
* I then created a new app on Heroku and deployed the application to same.
* In Heroku deployment method was set to Github with automatic deploys set from the master branch.
* The app was then deployed via this link: "https://mhphotography-ms4.herokuapp.com/".

#### To clone the repository:
* Select the Repository from Github.
* Click on the "Clone or download" green button
* Click on the "clipboard icon" to the right of the Git URL to copy the web URL.
* Open your IDE and navigate to terminal window
* Change the directory to where you want to clone the repository to.
* Paste the Git URL copied from above and click "Ok".
