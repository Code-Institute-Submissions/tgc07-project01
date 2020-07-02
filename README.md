# FictionalBakery

##  User Centric Frontend Development Milestone Project
A live demo of this project can be viewed [here](https://andrewsui.github.io/tgc07-project01/index.html).


This is a website created for an imaginary bakery ("FictionalBakery") to serve as a main reference point for the general public to find out important information about the bakery. The website consists of [home](https://andrewsui.github.io/tgc07-project01/index.html), [menu](https://andrewsui.github.io/tgc07-project01/menu.html), [find us](https://andrewsui.github.io/tgc07-project01/find-us.html), [about](https://andrewsui.github.io/tgc07-project01/about.html) and [contact](https://andrewsui.github.io/tgc07-project01/contact.html) pages.

## UX

Wireframes created during the design process can be found here: [mobile](https://github.com/andrewsui/tgc07-project01/blob/master/wireframe/wireframe-mobile.pdf) / [desktop](https://github.com/andrewsui/tgc07-project01/blob/master/wireframe/wireframe-desktop.pdf).

### User Stories
- Customers would want to be able to easily access key information about the bakery such as menu, location, opening hours, raison d’être and contact form. The bakery's address, telephone number and opening hours can be found on every page, so that it extremely easy for potential customers to find this information.
- The bakery's owners would use the website to showcase the quality of their products and the care taken in producing them, demonstrating why the products command a price premium over regular supermarket produce. The website serves as an information resource that does not need to change on a frequent basis. For more frequent customer engagement, the bakery's social media accounts would mainly be used instead, as such there are also social media links on every page.

## Features

### Existing Features
- Responsive web design that automatically adjusts the way content is displayed on different screen sizes. In general, a single column is used for mobile devices and two columns for medium screen sizes and up. When two columns have still been used for mobile devices, the font size has been slightly reduced so that text is not so cramped, but still legible.
- The [menu](https://andrewsui.github.io/tgc07-project01/menu.html) page features an infinitely looping image slideshow for each section of the bakery's menu. The lines joining the menu items and their respective prices are reponsive, changing in length automatically for different screen sizes.
- The [find us](https://andrewsui.github.io/tgc07-project01/find-us.html) page includes an embedded map using [Google Maps](https://www.google.com/maps/place/Ireland+Yard,+London,+UK/@51.512778,-0.10179,19z/).
- The [about](https://andrewsui.github.io/tgc07-project01/about.html) page includes an embedded video from [YouTube](https://www.youtube.com/watch?v=73oENaDiq04).
- The [contact](https://andrewsui.github.io/tgc07-project01/contact.html) page has a form placeholder with all fields being required before the submit button can be activated. The submit button redirects to a [separate web page](https://andrewsui.github.io/tgc07-project01/contact-submit.html) to thank the user for their message.
- External links open in new tabs.

### Features Left to Implement
- Change home page main image to one where baker is not wearing any accessories.
- Change menu page images to ones with lighter backgrounds to give the page a brighter look.
- Contact page submit button should send an email to business' email address.
- Contact page submit button currently redirects to a separate page to thank user for submitting a message, but a modal might be a better user experience.

## Technologies Used

- HTML
- CSS
- [Bootstrap](https://getbootstrap.com/)

## Testing

All testing was done manually. The following tests were performed:

1. [Menu](https://andrewsui.github.io/tgc07-project01/menu.html):
  - Verified image slideshow keeps looping for as long as website was left open and displays as expected.

2. [Find us](https://andrewsui.github.io/tgc07-project01/find-us.html):
  - Verified that embedded map was able to be interacted with and the "view larger map" link successfully opened Google Maps in a new tab.

3. [About](https://andrewsui.github.io/tgc07-project01/about.html):
  - Verified that embedded YouTube video plays as expected.

4. [Contact](https://andrewsui.github.io/tgc07-project01/contact.html) page:
  - Tried to submit the empty form and verified that an error message about the required fields appears.
  - Tried to submit the form with an invalid email address and verified that a relevant error message appears.
  - Tried to submit the form with all inputs valid and verified that the user is redirected to a page displaying a thank you message.

5. Navbar links:
  - All navbar links were checked to verify they link to the correct pages.

6. Telephone number for the bakery on all pages:
  - Verified that the link successfuly redirected phone call app on mobile device.

7. Social media links on all pages:
  - Verified that the facebook and instagram links open in new tabs on PCs.

To check compatibility and the layout's responsiveness the website was tested using different browsers (Chrome, FireFox and Safari) across a range of devices (Android and iOS mobile and tablet devices, and Windows and Ubuntu PCs.

## Deployment

A live demo of this project can be viewed [here](https://andrewsui.github.io/tgc07-project01/index.html) which has been hosted using GitHub Pages.

## Credits

### Content and Media
- The photos used in this site were obtained from [Unsplash](https://unsplash.com/)
- The bakery's logo design used in this site was created using [FreeLogoDesign](https://www.freelogodesign.org/)
- The facebook and instagram logos used in this site were obtained from [Iconfinder](https://www.iconfinder.com/)
- The embedded map on the [find us](https://andrewsui.github.io/tgc07-project01/find-us.html) page linked using [Google Maps](https://www.google.com/maps/place/Ireland+Yard,+London,+UK/@51.512778,-0.10179,19z/)
- The video on the [about](https://andrewsui.github.io/tgc07-project01/about.html) page was linked from [PARAGRAPHIC's YouTube channel](https://www.youtube.com/channel/UCQtzPvhc-8PQrmxcZUVdI7Q), with the original video being hosted [here](https://www.youtube.com/watch?v=73oENaDiq04).

### Acknowledgements

- I received inspiration for the [menu](https://andrewsui.github.io/tgc07-project01/menu.html) page's image slideshow from [this](https://www.urbaninfluence.com/make-a-background-image-slider-with-css-keyframes/) website and the HTML and CSS code was adapted from it.
- I used [this](https://cubic-bezier.com/) website to determine cubic-bezier function values in order to customise the above image slideshow's animation-timing.
