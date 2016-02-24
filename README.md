# Project1
This is a website for a fictitious hair salon called Make It Pink. This was made for a class assignment. The instructions are below. 
Your fist assignment is due Tuesday, February 23 (that's not next Tuesday, but the Tuesday after! - you have nothing due this week besides the JavaScript pretest, but I recommend starting this early!).

Create a one page website with the following properties:

Either a nav bar using the jQuery-One-Page-Nav (Links to an external site.) plugin and/or a nav bar with submenus
Nav bar should be responsive, switching to a menu icon on smaller screens
Distinct layout for mobile and desktop browsers - use at least one breakpoint. You can accomplish this with media queries and/or a grid framework. (Example of a distinct layout would be two columns turning into one)
Makes use of at least one other JavaScript plugin. Some examples (feel free to choose one not on this list):
Stellar.js (parallax effect) http://markdalgleish.com/projects/stellar.js/
Fancybox (lightbox) http://fancyapps.com/fancybox/ (Links to an external site.)
bxSlider (responsive image/content slider) http://bxslider.com/
Site deployed via Github Pages (we will practice this in class on Thursday)

**I was unable to get either parallax or fancybox to work, so I used CSS Animations instead to make the picture grow larger upon hover. Furthermore, lines 109-112 had to be commented out because onePageNav is not a function, even though I linked to my js file where I have it defined. If these lines had not been commented out, the media queries wouldn't work properly; clicking the hamburger menu would not have displayed the navbar. Also, clicking on the media link in the navbar does not take you to the media section. Instead, the submenu is displayed.**
