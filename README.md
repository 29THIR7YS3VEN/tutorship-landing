# The landing page for the Acrux Marine and Comet Digital Tutorship Programme
## Directory Details
- `index.html` - The homepage
- `css/style.css` - Css file for the layout of the page
- `css/common.css` - CSS file for the jquery animations
- `js/jquery-3.6.0.min.js` - Jquery source code, do not edit.
- `js/scripts.js` - Javascript file mainly for the dropdown function
- `js/email.js` - Javascript file deals with the emailing system for the form
- `js/animations.js` - For triggering jquery animations
- `images/*` - All images
## Editing info
### Changing the animations
Change the class name of the animation you wish to change according to the below:
- u-fade-type-static: Simple fade-in animation
- u-fade-type-left: Slide from the left
- u-fade-type-right: Slide from the right
- u-fade-type-top: Slide from the top
- u-fade-type-down: Slide from the bottom
- js-window-trigger: Trigger the animation on document ready
- js-scroll-trigger: Trigger the animation on scroll
### Setting up emailJS
Go to https://dashboard.emailjs.com/ to create an account to generate an API key and replace the default one on line 3 of `email.js`. You may need to enable two-factor auth in order for it to work with Gmail
## Attribution
- [Design by Emmanuel A.](https://github.com/emman29)
- [Jquery animations used created by Wakasato](https://github.com/Wakasato/jQuery_fadeIn_animation)
