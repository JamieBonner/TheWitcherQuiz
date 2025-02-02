# The Ultimate Witcher Fan Quiz

<img src="assets\images\screens.png">


The Ultimate Witcher Fan Quiz is my PP2 project built for my Diploma in Full Stack Software Development with the Code Institute. I have forked the repo from my student Github to my personal one so I can make some improvements to the site.
The quiz is set to test the users on their knowledge of The Witcher universe. The quiz offers the user to put their knowledge against 10 questions based on the netflix series, the games and also the books.
Within the game it keeps track of the users score so they can test their knowledge against friends. The site has been designed mobile first but is playable and responsive on desktop also.<br>
View the live site <a href="https://jamiebonner.github.io/TheWitcherQuiz/">here.</a>


# Home Page 
* When the vistor first arrives to on the page they will see background image of Geralt and loads in the title from the the top and slowly fades in the information.
* Within the page contents it gives the user information about the site and explains what the quiz is about. <br>
* The page also shows the users previous go at the quiz if they have already done the  quiz before. <br>
* Whilst on the page it allows the user to start the game from this page. <br>


 ### The Witcher Quiz Page
* This page starts the quiz.
* Within the page you have a questions with four potential answers.<br>
* The page tracks the users correct answers.<br>
* The page has a next button which allows the user to go to the next question.<br>
<br>

# Completed Page
 * This gives the user information on about how well they have done in the quiz.<br>
 * Within the page it congratulates the user for completing the quiz.<br>
 * It informs the user of their score.<br>
 * Within the page it alows the user to restart the quiz or go back to the home page.<br>
 <br>
 



# Technologies Used 

* <a href="https://en.wikipedia.org/wiki/HTML5" target=" _blank">HTML 5</a>
* <a href="https://en.wikipedia.org/wiki/CSS" target=" _blank">CSS 3</a>
* <a href="https://en.wikipedia.org/wiki/JavaScript">JavaScipt</a>
* <a href="https://www.gitpod.io/" target=" _blank">Gitpod</a>
* <a href="https://github.com/" target=" _blank">GitHub</a>
* <a href="https://git-scm.com/" target=" _blank">Git</a>
* <a href="https://fonts.google.com/about" target=" _blank">Google Fonts</a>



# Testing 

### Mobie Devices Used For Testing:
* Iphone 13 pro Max 
* Ipad 8th Gen 


#### Desktop
* I tested that each page on the site works on:
 * Chrome
 * Firefox
 * Edge 


 ### Mobile
 * I tested that each page on the site works on :
  * Chrome
  * Firefox 
  * Safari

### Functions  

* I have confirmed that the website is responsive with different screen sizes. 
  * I tested this by using different mobile devices and using the devtools within the browser to re-create different screen sizes.

* I have confirmed that the previous score works but shows null instead of 0 if you havent played the quiz or score 0. 
   * I have tested this by completing the quiz, clicking the home button in completed.html which directs me and shows the previous score.

* I have confirmed that the start button works and takes the user to the-witcher-page.html.
  * I have tested this by clicking on the start button which takes me to the desired page and also clears the local storage data.

* I have confirmed the alert when user gets question correct or in correct.
    I have test this by getting a question correct or incorrect in witch the aler does show.

* I have confirmed that the next button works in the-witcher-page.html page.
   * I have tested this by clicking on the button which changed the question until it gets to the end of the questions that takes you to the completed.html page.

 * I have confirmed that the current score function works in the-witcher-page.html page.
    * I have tested this by getting an answer correct which changes the number to the current score.  

* I have confirmed that the home button works in the completed.html page.
    * I have tested this by clicking on the home button which takes me to the desired page.

* I have confirmed that the final score works but shows null instead of 0 if you score 0. 
   * I have tested this by completing the quiz and being directed the completed.html where its shows the final score.    

* I have confirmed that the restart button works in the completed.html page.
    * I have tested this by clicking on the restart button which takes me to the desired page and also clears the local storage data.
     


 
### Unfixed bugs 

* Shows null instead of 0 in previous score and final score.
    * The fix to this would be upon load create the local storage data.
    * I believe this would create the inputs needed to show a Value of 0.

### Fixed Bugs

* During validation test got a error saying: 
<br>
<img src="assets\images\error.png">
    * Resolved this by changing select buttons to a div.
    * Resolved this by creating a javascript on click function for start, home & restart that directs the user to the correct page

### Validator Testing 

* HTML 
 * No errors were returned when passing through the official W3C validator.
* CSS 
 * No errors were found when passing through the offficial (Jigsaw) validator.
* JavaScript
    * No errors were found when passing through jshint validator.
    * I found a few warnings stating about let in the testing " 'let' is available in ES6 (use 'esversion: 6') or Mozilla JS extensions (use moz)."
    * I found a warning stating that "i is undefined" & "You might be leaking a variable (i) here" though if you remove it the qestions will not work.

 ### Lighthouse Testing 

* I have confirmed that on each page, the colours and fonts of the site were chosen to be easy to read and accessible by running it through lighthouse in devtools.
 * index.html:
 <br>
    <img src="assets\images\index.png">

 * the-withcer-quiz.html:
 <br>
  <img src="assets\images\quiz.png">


* completed.html:
<br>
 <img src="assets\images\completed.png">



# Deployment 

* The Witcher Quiz was deployed using GitHub pages:
 * Within the repository, go to settings.
 * Scroll down to Pages.
 * Select the Main branch.
 * Click save.
 * Page will refresh once site is published. 
 * It will now show the live active site.
 
 The live link to The Ultiamte Witcher Quiz can be found at: https://jamiebonner.github.io/TheWitcherQuiz/
 

 # Credits

 ## Content:
* Love Math Project
* https://www.w3schools.com
* https://color.adobe.com/
* https://fonts.google.com
* https://rgbacolorpicker.com/
* https://developer.mozilla.org/en-US/

## Brian Designs youtube channel : 
* I used the initial structure of getting the question and itterating through each question which I changed in how it itterates through the questions.
* I used the structure of itterating through each answer but modfied the outcome to my own design.

## Stack OverFlow - Sohail :
* I used this bit of code to be able to incremnet the score inside of the local storage

All images that have been used are credited to their owners and the links to the images can found below. 

### index.html:
* https://wallpapersden.com/

### the-witcher-quiz.html:

* https://wallpapersden.com/

### explore.html:
* https://wallpaperflare.com/


