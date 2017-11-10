# Lab_08
jQuery Effects and Animation

## Part 1, One-Page FAQ ##
* When a question is clicked, the corresponding answer will appear.
* When a question whose answer is visible is clicked, then the answer should disappear.
* Read and follow instructions in faqLab.pdf.

## Part 2, Login Slider ##
* Select the paragraph with the "Login" message in it.
* Attach a _click_ event handler to that paragraph.
* Toggle the display of the form _on_ and _off_.
* Read and follow the instructions in sliderLab.pdf.

## Part 3, Animated Dashboard ##
* Select the \<div\> tag.
* Attach a _hover_ event.
* Add the animate function for the _mouseEnter_ event.
* Add another animate function for the _mouseLeave_ event.
* Read and follow the instructions in animateLab.pdf.

## NOTES: ##
## jQuery Effects ##
Making elements on a web page appear and disappear is a common JavaScript task such as drop-down navigation menus, pop-up tooltips, and automated slideshows. jQuery supplies a few functions to make this easier.

*$('.submenu').hide()* would hide all of the tags with a class of submenu. 

Each effect function also can take in an optional speed and a *callback* function.
  * speed represents the amount of time the effect takes to complete
    * can be *fast, normal, slow* or a number of milliseconds 
    * $('element').fadeOut('slow');
  * callback is a function that runs when the effect is finished
  
  ### Basic Showing and Handling ###
  jQuery provides three functions for basic hiding and showing of elements:
  * _show()_ - makes a hidden element visible
  * _hide()_ - hides a visible element
  * _toggle()_ - switches the current display value
    
  ### Fading Elements In and Out ###
  For more dramatic effect, you can fade elements in or out
  * _fadeIn()_ - makes hidden element fade into view
  * _fadeOut()_ - hides a visible element by making it fade out of view
  * _fadeToggle()_ - combines both fadeIn() and fadeOut()
  * _fadeTo()_ - fades and image to a specific opacity. Must provide a speed value
    * _$('p').fadeTo('normal', .75);_ - fades at normal speed to .75 opacity

