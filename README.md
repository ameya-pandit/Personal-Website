
# Summary #
I built this personal portfolio to showcase my talents, putting to use what I learned from my internship, and find a place online that was just for me where I could talk about my career (skills, experience, education) and serve as a jumping off point for my other social medias. I made this website using straight ReactJS, and without using any frameworks. Most of the code is in JavaScript, then HTML, then CSS, with some SCSS for animations. It is hosted on GitHub (using GitHub pages), but I have a personal domain that allows me to customize the URL. It can be found it ameyapandit.me. 

Adding the content for my website was not as difficult as understanding and using CSS to display it. I am still learning to make this website compatible with mobile, hence the best user experience for my website is on Desktop browser. If I were to use frameworks, this would be handled for me, but I wanted to learn on my own. Building this site and encountering problems along the way has allowed me to become a better Front-End developer, which is experience I am grateful for. 

# Technologies Used #
As aforementioned, I used straight ReactJS for this project. I did not use any libraries or frameworks - this means that although my website is functional on both desktop and mobile, I need to craft it to work as intended on mobile. The code is mostly written in JavaScript, HTML, and CSS. I use dependencies such as EmailJS (for the contact form), SVG (for some of the logos), fontsource (for the Raleway font used on the website), react-router-dom (to handle redirecting to specific pages on the website), among others - these can be found in the package.json file. These dependencies help customize the project and put it together so that it looks and works like how I want it to. 

# Files #
These are the main files I used in building the website. In essence, each file is it's own page, sans the App, Header, and Footer files. The structure of most of these files is the same - each file just having a render function - but for the Contact page, where I use the state driven architecture of React to accomplish the form functionality where people can contact me.

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
