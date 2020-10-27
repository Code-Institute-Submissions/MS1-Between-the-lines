# Between the Lines

Between the lines is a website for readers.
The aim is to create an online space for them to meet other people sharing the same interests.
Through this website the customer can chose the kind of literature he is the most interested in.
Then, according to a preselected topic, the website suggests a book to read every month and organize an online meeting related this book.

# UX

This website is for people that want to share their interests and get the best of what they read. 

_External users goals_:
As a customer, I want to discover the different topics the meetings are organized around. 
As a customer, I want to meet people sharing the same interests as me, learn more about literature and get ideas of books to read.
As a customer, I want to chose what kind of topics interest me the most.
As a customer, I want to see what meetings are coming up next.
As a customer, I want to know how to contact Between the Lines' team to join a meeting.

_Site owners goals_:
As a site owner, I want to build a list of customers interested in joining a meeting.
As a site owner, I want to inform the customers about the meetings that are organized regarding every topics and which books are preselected.
As a site owner, I want to suggest and present different topics to target a large scope of readers.

# Wireframe

I used [Balsamic] (https://balsamiq.com/) to build my wireframe prior to the website coding.
The idea was to get an idea of what sections I would build and what design I would roughly create.

![Balsamic Wireframe Desktop](documentation/wireframe/milestoneverscomputer.pdf)

I firstly create my wireframe regarding the computer version. After my last meeting with my mentor, I learnt from my error and create another wireframes for phone/tablet versions:

![Balsamic Wireframe Phone](documentation/wireframe/milestoneversphone.pdf)

![Balsamic Wireframe Phone](documentation/wireframe/milestoneverstablette.pdf)

# Features 

For all features, I mainly used [Bootstrap] (https://getbootstrap.com/) codes. Here are the details :

_Navigation_ : I use the simple and clear navigation code suggests in Bootstrap. All sections are presented to ease the user
experience and direct to relevant links when clicked.

_Modals_ : To give more details to the user regarding every topics/meetings, I added modals in the Find your community page and the Meetings page.
Every time a user clicks on one topic in each page, a modal will appear to give more details to the customer. A section is included to 
direct the user to the Contact us page if he is interested in joining.

_Form_ : I use a simple form template provided by Bootstrap in the Contact us page.

_Future features_ : I would like to add a "Thank you" message after the customer fulfilled the contact page. 
Above all, instead of a contact form to fulfill I would like to permit the user to suscribe to Between the lines 
so as, with his personal log-in, he would become a real member of the community and would be able to subscribe directly to the meetings he is interest in.

# Technologies used:

* CSS 
* HTML
* Javascript to implement the Modal template from Boostrap
* ! [Bootstrap] (https://getbootstrap.com/)
* ! [Fontawesome] (https://fontawesome.com/)
* ! [Hover.css] (https://ianlunn.github.io/Hover/)
* ! [Googlefonts] (https://fonts.google.com/)

# Tools used

* ! [Bootstrap] (https://getbootstrap.com/)
* ! [W3C HTML Validator] (https://validator.w3.org/)
* ! [W3C CSS Validator]  (https://jigsaw.w3.org/css-validator/)

# Project set up

I started coding for a long while, making mistakes in the way I was commiting my files.
Thus, I always forgot to add the documentation through "git add ." before commiting.
When I finally realized my mistake after re-watching the relevant videos on Code institute lessons, I started this new repositary, trying not to make that mistake anymore.
This reason explains in this repository, most of the commits related to index.html, meeting.html and community.html are done with few times intervals.

I also realized at the end of my project that using pictures of books covers could lead to copyright issues. I then, replace all of them by icons instead.

# Tests

_W3C HTML Validator_ - I run my codes through the validator :

- index.html : no errors identified
- community.htlm : no errors identified
- meetings.html : no errors identified
- contact.html : no errors identified

_W3C CSS Validator_ 
- css.style : no errors identified

* As a customer, I want to navigate easily thought Between the Lines
- A navigation on the top right of the screen synthesis the main section of the website : About, Find your Community, Meetings and Contact us.
- The customer can click into one of the social network icons inside the footer of each pages. Clicking on one of the icon will load another page in the customer browser leading directly to each social network concerned.  
- Clicking on the title of the website "Between the lines" will bring back the user to the About page.

* As a customer, I want to be able to understand quickly the goals of the web
- Through the main page, the About page, as a customer I can quickly understand the aim of the website by reading the description.
- For the customer to get into further details and discover what topics, meetings and books are concerned, the About page also provide a link to the Find your community page

* As a customer, I want to be able to find a meeting that fits with my interests 
- The Find your community page suggests a panel of topics the user can be interested in. 
A small box for each topic provides the topic's name, the cover and references of the book selected for the month and the date of the next meeting related to each topic.
A button at the bottom of each box allows the user to get more details. By clicking on the button, a modal appears which gives:
1. a quick description of the topic 
2. a summary of the book selected for the month
3. a section directing the customer to the Contact us page to join the community or ask questions

* As a customer, I want to be quickly able to see what meetings are organized next 
- In the Meetings page the customer can see a timeline that quickly lists all the meetings to come. Books, date, and location of every meeting is displayed each time. 
- Again, for every meeting/book concerned, the customer can get more details by clicking on the "Learn more" button. 
If the customer clicks on the button, the modals described in the Find your community page will appear. 
If the customer wants to close the modal, he can easily rather click on both the cross at the top on the right, or in the close button at the bottom right of the modal, or - in desktop and tablet format - click outside of the modal. The customer will then come back to the Find your community page and be able to follow his navigation.

* As a customer, I want to be able to contact Between the lines to join a meeting or ask any questions
- A contact form appears in the Contact us page, allowing the customer to join the community after sending his name/surname/email and principal interests.
- The email has to be provided under the format "x@x.x" otherwise, it won't be accepted and submitted
- The customer can chose his principal interests between a list of topics the website covers. A radio button allows the user to easily select one or more interests.
- A submit button is at the end of the form. By clicking on it, the customer submits his information and the page is reloaded.

I especially tested twice the following to be sure features work properly : 
- Responsive versions of the website 
- Logo text in navigation bar to be sure it brings the customer back to the index.html page
- About, Community, Meetings and Contact links in navigation bar to make sure links work properly
- Social Media icons in Footer to be sure they were correct links and open in another page
- Contact Us link on Community page, modals and Meetings page to be sure the link works properly
- Find your community link on the About page to be sure the link works properly
- Every close features in the modals (cross on the bottom right, close button on the bottom right) to ensure they work properly

* Deployment

My website was deployed as bellow :

- From my GitHub account I went to my repository MS1 Between the lines
- I clicked on the settings icon 
- From the GitHub Pages section, I selected 'Master branch' in the dropdown
- My project is then deployed there : 

* Credit

_Content_
All texts were written by myself to fit with this website's goals.

_Images_
Hero image in About page comes from ![Pixabay](https://pixabay.com/fr/) 

After realizing at the end of my project, that using books covers' images could lead to copywrite issues, I eventually used icons from [Fontawesome](https://fontawesome.com/) to illustrate the Community page and modals related to every book's section.

_Acknowledgements_

Thank you to my mentor, Aaron, who gave me a lot of advices and support this project.

A big thank you to Michelle Clément - I inspired my redaction of this README.md document by reading ! [her own] (https://github.com/michellelclement/yoga-flow-ms1)

Eventually I  received help for my code by reading answers from questions on the websites:

! [W3schools.com] (https://www.w3schools.com/)
! [Stack Overflow] (https://stackoverflow.com/)