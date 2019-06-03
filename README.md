# Neighbourhood

## 2 June 2019

### By **John Victor Njoroge Karanja**:sunglasses

## Description

Mtaa is a web application that allows you to be in the loop about everything happening in your neighborhood. From contact information of different handyman to meeting announcements or even alerts. Mtaa is an inspiration to make living neighborhoods safe,convenient to live in and to make it easier to trade skills. Mtaa creates a community where one can find specific police and hospital contacts in specific neighborhoods that are available on the platform. Mtaa members get to even post what they feel is valuable to share to others.

### User Stories

1. A user can sign in to the application and start using it.
2. A user can view posted posts in their neighborhoods and their details.
3. A user can rate/ review other users' projects
4. A user can Create Posts that will be visible to everyone in their neighborhoods.
5. A user can view projects overall score.
6. A user can View their profile page with a general name and their neighborhoods.
7. A user can view a list of different businesses in my neighborhood.
8. A user can find Contact Information for the health department and Police authorities in their neighborhood.

## Technologies Used

1. Python 3.6
2. HTML and CSS
3. Django
4. Postgres
5. Heroku for deployment

## Behaviour Driven Development(BDD)

| Behaviour                                                                                                                   | Input                                                                  | Output                                                                                         |
|-----------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| The program navigates to the authentication page                                                                            | Load the application                                                   | Navigate to the login/register page                                                            |
| Navigate to the Registration Page                                                                                           | Click on Register link                                                 | A registration form is displayed                                                               |
| If registration is successful navigate to login page                                                                        | Click on Login Link                                                    | Application navigates to the homepage where posts are displayed                                |
| A post creation form is displayed with the empty fields. After saving the user is redirected to homepage to view the posts. | Click on add a new neighbourhood                          | A form with post picture,name,description is displayed.                                        |
| Application navigates to the business creation form . After saving user is redirected to all businesses page.               | Click on create business button                                        | A form with business name,email and hood name is displayed.A submit button is also displayed.  |
| All user details including the name, posts and businesses created by the user are displayed                                 | User clicks on the Profile link                                        | A User profile with all info pertaining the user is displayed.                                 |
| An Edit Form is displayed to update user info.                                                                              | Use clicks the edit profile button, makes changes and submits the form | A user edit form with update fields is shown to the user to enable them update necessary info. |
|User is logged out of the application |User clicks on the Logout dropdown |User logged out and redirected to the register/login page.|

## Application link

click [here](https://me-hood.herokuapp.com/)

## Set up and Installation

To access this application on your command line, you need to clone it.
`git clone https://github.com/twyfordsparks/neighbourhood.git`

### Prerequisites

A user will require git, Django, postgresql and python3.6+ installed in their machine.
To install these two, you can use the following commands

    #git
$ sudo apt install git-all
    #python3.6
    $ sudo apt-get install python3.6.
    #django
$ pip install django==1.11
    #postgres
$ sudo apt-get install postgresql postgresql-contrib libpq-dev

## Known Bugs

There are no issues or bugs encountered yet while coming up with the programme but incase of anything,feel free to contact the devoloper through johnvictor0002@gmail.com.

## Support and contact details

Incase you want to use the programme and you dont know where to start or what to do,feel free to contact the developer and be sure to receive help as much as you would need.You can do so through johnvictor0002@gmail.com.

## License

*MIT LISENCE.Feel free to use the code in anyway to improve it.
Copyright (c) 2019 John Victor Njoroge Karanja
