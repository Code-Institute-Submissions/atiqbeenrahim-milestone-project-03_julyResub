# Milestone Project 03: Backend Development
## Recipe Island - Cooking Recipe Website

[View the live project here.](https://milestone-project-03.herokuapp.com/)

This is the Backend Development project for Full Stack Software Developement course. I decided to make Cooking Recipe website because it has more scope to use database system using mongodb and Python codes. It is designed to be responsive and accessible on a range of devices, making it easy to navigate for potential visitors and customers.

<h2 align="center"><img src="https://i.ibb.co/pKLbbLx/mp3.png"></h2>

## User Experience (UX)

-   ### User stories

    -   #### First Time Visitor Goals

        1. I want to easily understand the main purpose of the site and learn more about service.
        2. I want to be able to easily navigate throughout the site to find content and use search functionality.
        3. I want to look for the log in, register, information and details of the recipe. I also want to locate company's social media links to see it's followings on social media to determine how trusted and known this company is.
        4. I want to create account and add my own recipe which should be flexible with create, read, update and delete (CRUD) functionality.

    -   #### Returning Visitor Goals

        1. I want to see other user's recipe.
        2. I want to log in and add more recipes.
        3. I want to find suitable recipe for me using search functionality.

    -   #### Frequent User Goals

        1. I want to check to see if there is any newly added recipe is posted by other users.

-   ### Design
    -   #### Colour Scheme
        -   The 3 main colours used are grey darken-4, white-text and light-green accent-3 (#212121, #fff and #76ff03).
    -   #### Typography
        -   The Texturina font is the main font used throughout the whole website with Serif as the fallback font in case for any reason the font isn't being imported into the site correctly. Texturina is a clean font and stylish used frequently in programming, so it is both attractive and appropriate.

    -   #### Imagery
        -   Imagery is important. In the Hero section, I use video clip to be striking and catch the user's attention. It also has a modern, energetic aesthetic. It will help me to promote my brand image and increase the trust of the customers.

*   ### Wireframes

    -   Large screen Wireframe & Mobile Wireframe- [View](https://viewer.diagrams.net/?highlight=0000ff&edit=_blank&layers=1&nav=1&page-id=2r570p7k_jzz1PyAyrj-&title=recipe%20island.drawio#Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fatiqbeenrahim%2Fmilestone-project-03%2Fmaster%2Fstatic%2Frecipe%2520island.drawio)

## Features

-   Responsive on all device sizes

-   Interactive elements

## Database Schema

- There are three collections in the database:
    1. users
    2. recipes
    3. categories
    <h2 align="center"><img src="https://i.ibb.co/dcN4wPR/Data-Schema.png"></h2>
    
    <h3>The image above was the data model that I came up with for the project.</h3>
    - The following image is from my database how it storing data to 'recipes' collection which is related to 'users' and 'categories' collection:
    <h2 align="center"><img src="https://i.ibb.co/4wk9yW9/recipes-collection.png"></h2>
    

## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
-   [JavaScript](https://en.wikipedia.org/wiki/JavaScript)
-   [Python](https://www.python.org/)

### Frameworks, Libraries & Programs Used

1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Texturina' font into the style.css file which is used on all pages throughout the project.
1. [JQuery:](https://fontawesome.com/)
    - JQuery was used for interactive sections.
1. [flask:](https://flask.palletsprojects.com/en/2.0.x/)
    - This is used for tools, libraries and technologies that allow you to build a web application.
1. [Materialize](https://materializecss.com/)
    - This is used for modern responsive front-end framework based on Material Design.
1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
1. [MongoDB](https://www.mongodb.com/)
    - This is used for database collections and manupulation.
1. [Heroku](https://www.heroku.com)
    - Heroku is used for deploy, manage, and scale modern apps
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
1. [draw.io:](http://draw.io/)
    - draw.io was used to create the wireframes during the design process.
1. [QuickDBD:](https://www.quickdatabasediagrams.com/)
    - QuickDBD was used to create the Data Schema.


## Testing

The W3C Markup Validator, W3C CSS Validator and JavaScript validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

-   [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)
-   [JavaScript Validator](https://jshint.com/)
-   [Python Validator](http://pep8online.com/)

### Testing User Stories from User Experience (UX) Section

-   #### First Time Visitor Goals

    1. I want to easily create, read, update, delete recipe and log in and register my account.

        1. Upon entering the site, users are automatically greeted with a clean and easily readable navigation bar to go to the page of their choice. Underneath there is a Hero section with greetings and recipe qoutes with dialogues for promotion of the website.
        2. The main points are made immediately with the Hero section.
        3. The user has to click the navigation buttons, which will lead to the desired place, to use functionality of the website.

    2. I want to be able to easily be able to navigate throughout the site to find content.

        1. The site has been designed to be fluid and never to entrap the user. At the top of each page there is a clean navigation bar, each link describes what the page they will end up at clearly.
        2. On the page home, navigation bar is sticky so it's always helpful to navigate around also user dosen't get lost in the pages.

    3. I want to look for the recipes and details by using search option easily. I also want to locate their social media links to see their following on social media to determine how trusted and known they are.
        1. Once the new visitor has logged in, they will notice the profile page and from their user can navigate around for recipes.
        2. The user can also scroll to the bottom of any page on the site to locate social media links in the footer.

-   #### Returning Visitor Goals

    1. I want to find the new updates regarding his recipes.

        1. These are clearly shown in recipe section and also search option to find desired recipe.
        2. They will be directed to a page with navbar or can scroll down.

    2. I want to find the best way to get in contact with the company with any questions I may have.
        - The footer contains links to the websites's Github, Facebook, Twitter and Instagram page and it will open up in separate tab.


### Further Testing

-   The Website was tested on Google Chrome, Firefox, Internet Explorer, Microsoft Edge and Safari browsers.
-   The website was viewed on a variety of devices such as Desktop, Laptop, iPhone7, iPhone 8 & iPhoneX.
-   A large amount of testing was done to ensure that all pages were linking correctly.
-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.


## Deployment

### Requirements to Deploy
-   Python 3
-   Github Account
-   Heroku Account
-   MongoDB Account

#### Heroku Deployment

-   Before creating Heroku App, we need this following files in the project:

    1. requirments.txt (pip3 freeze --local > requirments.txt)
    2. Procfile (python run.py > Procfile)

-   Creating the APP:

    1. Navigate to Heroku website [here](https://www.heroku.com/)
    2. Log In/Register
    3. Select "create a new app"
    4. Give the name of the App and select closest Region
    5. Finally click on "create app" for deployment process.

#### Connecting Github Repository with the Heroku APP:

1. Go to deploy tab in Heroku and select connect to git hub
2. You Have to be signed in to the Git hub account during the process
3. In the github connect section of Heroku find your repository name and select that repo
4. Then select connect.

#### Then Set the evironment variable in Heroku app.
1. Click the Settings tab and click the Reveal Config Vars button and add the following:

| Key | Value |
| :-: | :---: |
| IP  | 0.0.0.0 |
| PORT | 5000 |
| MONGO_DBNAME | Your MONGO_DBNAME |
| MONGO_URI | Your MONGO_URI |
| SECRET_KEY| Your SECRET_KEY |

- MONGO_DBNAME - This is the name of the database you are trying to connect to within MongoDB.
- MONGO_URI - This can be found on the MongoDB website by following these steps:
    - In the clusters tab click connect on the associated cluster.
    - Click connect > Connect your application
    - Copy the string and substitute the password (from Database access not your MongoDB site password) and    
    "myFirstDatabase" to your DB name.
    - SECRET_KEY - This is a custom string set up to secure the application and to keep client-side sessions secure.

#### Enable automatic deployment 
1. Click the Deploy tab again.
2. Under Automatic deploys section, choose the branch you want to deploy from and then click the "Enable Automatic Deploys" button.
3. Click the "Deploy Branch" button underneath to deploy the app the Heroku servers.

#### Creating a local clone
* NOTE: This project will not run locally with database connections unless you create an env.py file to hold the variables for IP, PORT, MONGO_DBNAME, MONGO_URI and SECRET_KEY. The information used to run this project are private and have not been pushed to the GitHub repository for this reason.
Once you have done the above you can follow these steps to create a local copy on your computer:
1. Navigate to the GitHub Repository for the project.
2. Click the Code drop down button.
3. Either unpackage locally or download as a ZIP file.
4. Open with your preferred IDE or copy Git URL from the HTTPS field.

* If you chose to copy the Git URL then follow these additional steps:
1. Open a terminal window on your computer (or in your preferred IDE) in a directory of your choice.
2. In the terminal window type git clone https://github.com/atiqbeenrahim/milestone-project-03.git and press enter to confirm.
3. This will create a local clone of the project in your chosen directory.
4. For the project to function fully you must install the required dependencies from "requirements.txt"
5. To do this, type pip3 install requirements.txt
6. To run the app in your local IDE type python3 app.py

#### Fork Project
To contribute to this website you can Fork it by following the procedure below:
* Go to the repository page.
* Click the Fork button on the top right of the page.
* This creates a copy in your personal repository.
* When you're finished making changes, return to original repository and press "New Pull Request" to request your changes be merged into the original project.

## Credits

### Code

-   [W3_Schools](https://www.w3schools.com/): Got different kinds of solutions from this website throughout the project mainly in HTML, CSS styling and JavaScript.

-   [Webformatter](https://webformatter.com/html): formatted all the codes through web formatter website.


### Content

-   All content was written by the developer.

-   Psychological properties of colours text in the README.md was found [here](http://www.colour-affects.co.uk/psychological-properties-of-colours)

### Media

-   All Images and Video taken from pixabay.com.

### Acknowledgements

-   My Mentor for continuous helpful feedback.

-   Tutor support at Code Institute for their support.
