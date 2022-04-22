For the skill assessment, we will be testing out your ability to pick up someone else's code and take it to the next level. 
For the hypothetical situation, a FED has been working on a project but got pulled off so we need your help.

Here's what the FED has to say:

This is where we got to in the cut, but we are having problems and haven't been able to fully test. 
Can you help us resolve the following issues as well as help catch if we missed something?
The client is very particular about having fast page speed, good SEO, and wants interesting interactive pieces.
Support wise they also want to have this page look right in browsers that are over 5% of the browser stats for the US over the past couple of months
Below are the items we haven't been able to get to yet.

Font:
  - We set up the Allura and Alex Brush font family stacks in the CSS but we don't have the fonts included --Done
Site Logos:
  - We need to account for retina screens

Icons:
  - We haven't been able to add the icons to the setup yet
  - Hamburger menu, cart, and search icons haven't been added -- Added cart and search and replaced Hamburger at the footer with "see more" (for now)

Navigation:
  - We haven't setup functionality for the menu toggle to open up the bottom footer area in small screens --Footer is hidden when in mobile, just have to add functionality to see it when clicked

Slideshow:
  - We need another slide created from the PSD 
  - The styling isn't right yet for slide content as well
  - We also haven't been able to set up the slide functionality --Done

Footer:
  - We got a fair amount of responsive styles done for the site however the footer isn't quite there yet
  - Social media icons need to be setup so some html changes there to put them in is fine. --Done but need to resize them to make them look better
  - Expander accordion Javascript functionality hasn't been setup or styled
  - Footer bottom area: we unfortunately can't pull the html content out of its location
     - Can we style up the setup so it matches the desktop and mobile styles

Responsive:
  - For some reason the site isn't switching over to "mobile" styles in devices --Done
  - Also when you shrink down the browser some sort of content is causing a horizontal scrollbar in smaller screens
  - In between sizes for tablet portrait feel fairly empty, is there something we can style to make them look better


The client is very active in the project and wants a technical breakdown of what you did and how you resolved the missing items. 
So we need a writing assessment as well as the code above. 
They also want to know how the design UI/UX and FED code practices could be improved down the road, so please include that as well in your writing. 

First off, there were many new concepts that I had to research to find the right way to implement these features.
List of completed tasks
-Imported fonts
-Search and Cart Icons added at the top, Hamburger icon is at the bottom (I assume to expand footer in mobile view)
-Footer hidden when screen is in mobile view (does not have functionality to view footer)
-Automated slideshow added
-Social media icons added 
-Switches into mobile view, removed horizontal scroll when shrinked down


I started by importing the needed fonts using an import url statement stored inside the head of the HTML document.
Then I downloaded some the search and Hamburger images and added them in the appropriate places using image tags in the html.
I added html and css for a slideshow to hold images inside of the slideshow container, then added functionality to automate a slideshow in main.js to change pictures every 2 seconds.
After that I added some social media icons using some more image tags in the html.
Then I realized the reason the screen scrolled horizontally in mobile view was because the bottom background image on the page was too long. All I did was change the css to make the width of the bar smaller.

Adding the slideshow and responsive design were new concepts to me so it took some researching to make it work.
I wasn't sure exactly what was meant by accounting for retina screens so I never got to that issue.
Also adding functionality to change the css depending on screen size was new. Thats why I didn't accomplish viewing the Hamburger dropdown in the mobile view.

As far as making things better in the future, it would be better to modularize the code instead of having a huge HTML document. 
Ideally you should put related pieces of the page in folders and have subfolders for each piece.
Too much of the app was hard coded and it should be dynamically generated.