# NEEKU SHAMEKHI'S PORTFOLIO WEBSITE

## Description

This is a portfolio website created for my first Milestone Project for the Code Institute's Full Stack Developer course. It is built using the knowledge gained from the HTML, CSS and User Centric Design modules of the course.

The purpose of this website is to provide information on who I am and what services I can deliver by providing my CV, and letting people to contact me.

I have tried to keep it simple. The website is split into 3 main pages:

- Home: An Introduction to me with links to my social media profiles.
- About: Information on who I am and what I do.
- Contact: A form to contact me for recruiting or any other purposes.
- There is also a link to a downloadable version of my CV.

## User Experience (UX)

![Responsive Design Image](https://github.com/neeku/MS1Project-Portfolio/blob/master/assets/images/responsivedesign.png)

This site is a personal portfolio for myself.

The page layout is responsive, with a mobile-first design in mind.

Background images are my own photographs captured out in the nature at different locations.

## User Stories

#### Potential visitor 

As a potential visitor to the website one may want to know:
- Who I am and what I do
- My social media profiles that show my professional skills and hobbies
- Further educational and professional background that can be accessed from my downloadable CV
- Contact me via the contact form

## Structure

 The website has a left side vertical menu bar for larger displays which switches to a horizontal top navigation bar in smaller displays where the menu item names are hidden and only the relevant icons are displayed.

 The home page consists of my name and my occupation, along with a collection of social media icons that are linked to my profiles in various platforms. The purpose of this page to fulfill the user story:

 > My social media profiles that show my professional skills and hobbies

 About page contains a short bio. To increase the text readability over the background image, especially when the device sizes change, I have dded a white opaq background so that it creates a contrast and makes the text more readable. The purpose of this page is to fulfill the user story:

> Who I am and what I do

 Contact page contains a contact form that allows the users to contact me through the website. The purpose of this page is to fulfill the user story:

 > Contact me via the contact form

 Resume provides a link to my CV opening in a new tab. The purpose of this page is to fulfill the user story: 

 > Further educational and professional background that can be accessed from my downloadable CV


For further enhancement of the website and to make it distinguishable when there are many open tabs, a favicon with my initials is added. **???????**

## Design

### Color Scheme

The main colors used are two shades of gray, ![#45505b](https://via.placeholder.com/15/45505b/000000?text=+) and ![#728394](https://via.placeholder.com/15/728394/000000?text=+) that are nuetral and easy on the eye.

### Typography

The main font used on the website is Montserrat, which is a Google Font.

### Imagery 

I have used a selection of background images for each page from my personal photography archive. The photos have been captured in various parts of Iran, and Ireland, my two home countries.


## Wireframes
Access wireframes from [here](https://github.com/neeku/MS1Project-Portfolio/blob/master/assets/wireframe/MS1-Portfolio.pdf)



## Features

- Responsive Design
- Social media links to allow users to connect with me on different platforms and find out about my specific hobbies and interests
- Contact form that allows users to contact me with any questions, messages or comments that they may have.
- A direct link to my CV that opens in a new page to optimize the user experience

## Technologies

#### Languages Used

- HTML
- CSS

#### Frameworks Used

- Bootstrap

#### Tools Used

- [Am I Responsive](http://ami.responsivedesign.is/): for testing as described below
- [Balsamiq](https://balsamiq.com/): to create wireframes
- [fontawesome](https://fontawesome.com/icons?d=gallery): for social media and menu icons
- [Google Fonts](https://fonts.google.com/?selection.family=Lexend+Tera#standard-styles): for the text displayed on the site
- [Gitpod](https://www.gitpod.io/): for creating the website
- [Codeply](https://www.codeply.com/go/Rgq96HykJ2/sidebar-that-changes-to-navbar): for a sidebar that changes to navbar in smaller displays
- [GitHub](https://github.com/): for hosting the site and to store the source code for the Website and [Git Pages](https://pages.github.com/) is used for the deployment of the live site.
- [Git](https://git-scm.com/): used as version control software to commit and push code to the GitHub repository where the source code is stored.
- [Google Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools): for inspecting page elements and help debug issues with the site layout and test different CSS styles.
- [Favicon](https://favicon.io/): for making the site favicon 

## Testing

Testing is an essential part of the MS1 Project, like every other project.

Testing must be done on at least three web browsers, and all screen sizes.

No elements should overlap another container div. All elements should remain on the screen at all sizes above 300px. 

All nav links should direct to the correct pages as per their names. The Home page is the exception, this one will redirect to index.html. 

All links to external websites must open in a new browser.

Testing of form validation will also be required to ensure the correct inputs are taken and that all fields are required. 

Validation of inclusion for all features included in the Structure of the Website / Wireframes must be performed.

This site was tested using various resources such as:

- [Am I Responsive](http://ami.responsivedesign.is/) was used to test the site on various screen sizes to ensure the information could be viewed correctly
- [HTML Validator](https://validator.w3.org/) used to validate HTML
- [CSS Validator](https://jigsaw.w3.org/css-validator/) used to validate CSS
- [Pingdom](https://tools.pingdom.com/#5ca554057c800000) used to test speed of website


## Deployment
My portfolio website has been deployed to [my github page](https://github.com/neeku/MS1Project-Portfolio)

### Project Creation
The project was started by navigating to the [template](https://github.com/Code-Institute-Org/gitpod-full-template) and clicking 'Use this template'. Under Repository name I input MS1Project-Portfolio and checked the Include all branches checkbox. I then navigated to the new [repository](https://neeku.github.io/MS1Project-Portfolio). I then clicked the Code drop down and selected HTTPS and copied the link to the clipboard.

Opening a bash terminal in Visual studio code I then typed git clone [link from clipboard](https://neeku.github.io/MS1Project-Portfolio.git) followed by open folder and navigating to the newly created local repository. The following commands were used throughout the project:

* git add filename - This command was used to add fils to the staging area before commiting.
* git commit -m *commit message explaining the updates* - This command was used to to commit changes to the local repository.
* git push - This command is used to push all commited changes to the GitHub repository. 

### Using Github Pages
1. Navigate to the GitHub [Repository:](https://neeku.github.io/MS1Project-Portfolio)
1. Click the 'Settings' Tab.
1. Scroll Down to the Git Hub Pages Heading.
1. Select 'Master Branch' as the source.
1. Click the Save button.
1. Click on the link to go to the live deployed page.

### Run Locally
1. Navigate to the GitHub [Repository:](https://neeku.github.io/MS1Project-Portfolio)
1. Click the Code drop down menu.
1. Either Download the ZIP file, unpackage locally and open with IDE (This route ends here) OR Copy Git URL from the HTTPS dialogue box.
1. Open your developement editor of choice and open a terminal window in a directory of your choice.
1. Use the 'git clone' command in terminal followed by the copied git URL.
1. A clone of the project will be created locally on your machine.

## Acknowledgements

I'd like to thank Spencer Barriball, my awesome mentor, for his genuine support throughout this project, and all the wonderful people in Student Care department of Code Institute for being patient with me while I've been struggling to navigate my path in the recent months.
