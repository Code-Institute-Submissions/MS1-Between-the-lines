# Between the Lines

Between the lines is a website for readers.
The aim is to create an online space for them to meet other people sharing the same interests.
Through this website the customer can chose the kind of literature he is the most interested in.
Then, according to a preselected topic, the website suggests a book to read every month and organize an online meeting related this book.


# UX

This website is for people that want to share their interests and get the best of what they read. 
Every meeting will be organized for 45 minutes with a mentor in charge of asking the first questions and leading the debate.

External users goals:
As a customer, I want to discover the different topics the meetings are organized around. 
As a customer, I want to meet people sharing the same interests as me, learn more about literature and get ideas of books to read.
As a customer, I want to chose what kind of topics interest me the most.
As a customer, I want to see what meetings are coming up next.
As a customer, I want to know how to contact Between the Lines' team to join a meeting.

Site owners goals:
As a site owner, I want to build a list of customers interested in joining a meeting.
As a site owner, I want to inform the customers about the meetings that are organized regarding every topics and which books are preselected.
As a site owner, I want to suggest and present different topics to target a large scope of readers.

# Wireframe

I used Balsamic to build my wireframe prior to the website coding.
The idea was to get an idea of what sections I would build and what design I would roughly create.

![Balsamic Wireframe](documentation/wireframe/Milestone1.pdf)

# Features 

For all features, I mainly used Bootstrap codes. Here are the details :

Navigation : I use the simple and clear navigation code suggests in Bootstrap. All sections are presented to ease the user
experience and direct to relevant links when clicked.

Modals : To give more details to the user regarding every topics/meetings, I added modals in the Find your community page and the Meetings page.
Every time a user clicks on one topic in each page, a modal will appear to give more details to the customer. A section is included to 
direct the user to the Contact us page if he is interested in joining.

Future features : I would like to add a "Thank you" message after the customer fulfilled the contact page. 
Above all, instead of a contact form to fulfill I would like to permit the user to suscribe to Between the lines 
so as, with his personal log-in, he would become a real member of the community and would be able to subscribe directly to the meetings he is interest in.

Form : I use a simple form template provided by Bootstrap in the Contact us page.

# Technologies used:

* CSS
* HTML
* Javascript to implement the Modal template from Boostrap
* Bootstrap
* Font Icons
* Hover.css

# Tools used

* Balsamic
* W3C HTML Validator 
* W3C CSS Validator 

# Project set up

I started coding for a long while, making mistakes in the way I was commiting my files.
Thus, I always forgot to add the documentation through "git add ." before commiting.
When I finally realized my mistake after re-watching the relevant videos on Code institute lessons, I started this new repositary, trying not to make that mistake anymore.
This reason explains in this repository, most of the commits related to index.html, meeting.html and community.html are done with few times intervals.

# Tests

W3C Test html/css

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
If the customer wants to close the modal, he can easily rather click on both of the two crosses at the bottom and at the top on the right, or, in desktop and tablet format, click outside of the modal. The customer will then come back to the Find your community page and be able to follow his navigation.

* As a customer, I want to be able to contact Between the lines to join a meeting or ask any questions
- A contact form appears in the Contact us page, allowing the customer to join the community after sending his name/surname/email and principal interests.
- The email has to be provided under the format "x@x.x" otherwise, it won't be accepted and submitted
- The customer can chose his principal interests between a list of topics the website covers. A radio button allows the user to easily select one or more interests.
- A submit button is at the end of the form. By clicking on it, the customer submits his information and the page is reloaded.

// Full test documentation

* Deployment