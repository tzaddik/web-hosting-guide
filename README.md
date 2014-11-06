# JavaScript Assessment

##1 - Form validation script

* Location: beatmap.js / contact.htm
* Function: submitIt() called from the contact form on the contact.htm, the function makes sure all fields are filled, that each field other than email satisfies field length requirements
* Extra Feature: A countdown feature is used on the Comments field. The script jquery.simplyCountable.js is called in beatmap.js and executed upon the loading of the document.

##2 - Show a confirm box with all the submitted data, asking to user to confirm their data

* Location: beatmap.js
* Function: After the form is validated in the submitIt() function, this script shows a confirm window with all the entered data in the form. Saying yes will submit the form, saying no will cancel the submit and retain all the entered data.

##10 - Create an image gallery that allows the user to move through a selection of 'recommended' artists

* Location: beatmap.js / index.htm
* Function: slideshowArtist() is called by clicking on the buttons underneath the slideshow on index.htm. Each button corresponds to a certain picture.

##11 - Disable the active page link in the navigation menu

* Location: beatmap.js / All html pages
* Function: activeLink() is auto-loaded by jQuery upon the loading of the page. Each link has a href attribute with a # in it has that attribute removed completely and associated visual effects are disabled.

##12 - When the headline is selected, a story should open underneath it (accordion)
* Location: beatmap.js / index.htm
* Function: homeAccordion() is auto-loaded by jQuery upon the loading of the page. It hides all the news story content other than the headline. Clicking the headline will cause the story to display again.


