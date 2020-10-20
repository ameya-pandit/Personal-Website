# Personal-Website #
This is the repository that holds the files I needed to develop my personal website. However, this is not always the most up to date one. That will be found in the ameya-pandit.github.io repository (https://github.com/ameya-pandit/ameya-pandit.github.io). This will be updated generally to the most recent, but sometimes if the changes are small they will be more accurately reflected in that repository.

# Summary #
I built this personal portfolio to showcase my talents, putting to use what I learned from my internship, and find a place online that was just for me where I could talk about my career (skills, experience, education) and serve as a jumping off point for my other social medias. I made this website using straight ReactJS, and without using any frameworks. Most of the JavaScript, then HTML, then CSS, with some SCSS for animations. It is hosted on GitHub (using GitHub pages), but I have a personal domain that allows me to customize the URL. It can be found it ameyapandit.me

# Technologies Used #
As aforementioned, I used straight ReactJS for this project. I did not use any libraries or frameworks - this means that although my website is functional on both desktop and mobile, I need to craft it to work as intended on mobile. The code is mostly written in JavaScript, HTML, and CSS. I use dependencies such as EmailJS (for the contact form), SVG (for some of the logos), fontsource (for the Raleway font used on the website), react-router-dom (to handle redirecting to specific pages on the website), among others - these can be found in the package.json file. 

# Files #
App.js - handles the routing of the React project. I use react-router-dom's BrowserRouter.

AboutMe.js & AboutMe.css - handles the content of the About Me page on the website.

Connect.js & Connect.css - handles the content of the Connect page on the website.

Education.js & Education.css - handles the content of the Education page on the website.

Experience.js & Experience.css - handles the content of the Experience page on the website.

Footer.js & Footer.css - handles the content of the Footer subsection on the bottom of the website (just a block of text).

Header.js & Header.css - handles the content of the Header subsection on the top of the website (present in every component and contains links to other pages).

Home.js & Home.css & otherCSSwork.scss - handles the content of the Home page on the website (some of the animations on this page are on otherCSSwork.css).

NotFoundPage.js - handles the content of the NotFoundPage on the website - whenever you encounter a 404 error, this page is displayed.

Portfolio.js & Portfolio.css - handles the content of the Portfolio page on the website.

Skills.js & Skills.css - handles the content of the Skills page on the website.
