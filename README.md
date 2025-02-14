# Keep Riding

[Link to live project.](https://mayasharma2110.github.io/Keep-Riding/)

This is a website for a fictional horse riding school.  

It is aimed for those who are interested in taking up horse riding or those with previous experience who wish to improve their skills.
The riding school is for those of any age, gender or ability. 

Mockups:
![Home Page Mockups](assets/mockups/mockup-home.PNG)

![Prices Page Mockups](assets/mockups/mockup-prices.PNG)

![Contact Page Mockups](assets/mockups/mockup-contact.PNG)

## Table of Contents

* [UX](#ux)
  * [User Stories](#user-stories)
    * [First Time Visitor Goals](#first-time-visitor-goals)
    * [Returning Visitor Goals](#returning-visitor-goals)
    * [Frequent User Goals](#frequent-user-goals)
  * [Strategy](#strategy)
    * [Business Goals](#business-goals)
    * [User Goals](#user-goals)
  * [Scope](#scope)
  * [Structure](#structure)
    * [Wireframes Home](#wireframes-home)
    * [Wireframes Prices](#wireframes-prices)
    * [Wireframes Contact](#wireframes-contact)
    * [Wireframes Comments](#wireframes-comments)
  * [Skeleton](#skeleton)
    * [Colours](#colours)
    * [Typography](#typography)
    * [Imagery](#imagery)
  * [Surface](#surface)
* [Features](#features)
    * [Existing Features](#existing-features)
    * [Features Left to Implement](#features-left-to-inplement)
* [Technologies Used](#technologies-used)
* [Testing](#testing)
  * [Margins](#margins)
  * [Headers and Footers](#headers-and-footers)
  * [Home Section](#home-section)
  * [Prices Section](#prices-section)
  * [Contact Section](#contact-section)
  * [Online Validation](#online-validation)
  * [Lighthouse Validation](#lighthouse-validation) 
  * [User Stories from the UX Section](#user-stories-from-the-ux-section)
  * [Fixed Bugs](#fixed-bugs)
    * [Navigation Bar Colours](#navigation-bar-colours)
    * [Collapsible Hamburger Menu](#collapsible-hamburger-menu)
    * [Carousel Images](#carousel-images)
    * [Form Fieldset](#form-fieldset)
    * [Minor Fixes](#minor-fixes)
* [Deployment](#deployment)
  * [Creation](#creation)
  * [GitHub Pages](#github-pages)
  * [Local Clone](#local-clone)
  * [Forking](#forking)
* [Credits](#credits)
  * [Code](#code)
  * [Content](#content)
  * [Media](#media)
  * [Acknowledgments](#acknowledgments)

## UX

### User Stories

#### First Time Visitor Goals

* As a first time user, I want to understand the purpose of the website and learn about the riding school.

* As a first time user, I want to be able to navigate through the site easily.

* As a first time user, I want to be able to view the website on a laptop, tablet or phone and I want the content to be displayed well on any device.

* As a first time user, I want to see what facilities are offered by the riding school.

#### Returning Visitor Goals

* As a returning user, I want to check the range of lessons that are offered and the prices. 

* As a returning user, I want to read reviews from current and previous customers about this school.

* As a returning user, I want to contact the school to book a lesson and/or ask for additional information.

* As a returning user, I want to find out where I can follow the riding school on social media platforms.

#### Frequent User Goals

* As a frequent user, I want to check the lessons that are offered.

* As a frequent user, I want to check the cost of the lessons offered and see if there are any special offers.

### Strategy

#### Business goals

* Increase interaction with potential new customers.

* Increase presence and following on social media platforms including Facebook and Instagram.

* Increase the number of lessons/hacks booked.

#### User Goals

* To see what the school offers in terms of facilities, lessons and prices.

* To be able to contact the school to ask for more information or book.

* To be able to see some pictures of the horses and riding.

* For the school to offer private and small groups lessons, so they can improve quicker.

* For the school to have an indoor and outdoor arena(s), so that you can ride in any weather conditions.

* For the school to offer hacks for a more relaxed riding experience.

### Scope

Key features to be included based on user stories are:

* Responsive website on mobile, tablet and laptop size devices.

* Interactive elements: 
  * Navbar becomes a burger menu on mobile, also hovering over elements (in navigation bar and footer) gives a colour change.
  * On the home page there is a carousel where users can scroll through some pictures.

* About Us - allows users to find out who we are and what we do by having them read a short paragraph.

* Facilities - allows users to find out what specific services we can provide and the facilities we have, by reading a list.

* Reviews - allows users to find out how other customers have enjoyed our services, by providing reviews from previous and current customers.

* Prices - allows users to find out what specific lessons are offered and at what cost, by providing the information in a table format.

* Contact/Booking Form - allows users to contact the school if they wish to book a service or ask for extra information. 

* Footer with links to social media accounts - allows the users to keep up to date with the school by following on social media.

### Structure

All pages of the website will have a consistent navigation bar - which collapses when viewed on a small screen.

All pages of the website will have a footer with links to the social media accounts that users can view and follow to keep up to date with the company.

The website will use bootstrap grids to make the layout responsive to different devices and screen sizes.

The home page will contain an about us section explaining the goals of the riding school.

The home page will contain a facilities section explaining what the riding school has to offer and what makes it special from competitors.

The home page will contain a reviews section showing how other customers have enjoyed their time at the riding school.

The website will contain a prices section which shows the lessons offered and their prices, including any special offers.

The website will contain a contact section which allows users to get in touch with the school to request more information or book a lesson.

### Skeleton

I used Balsamiq to make the wireframes for this project. The website was designed to have 3 pages - home, prices and contact.
The wireframes were created for all pages for phone, tablet and desktop devices.

#### Wireframes Home

Mobile

![Home Page Phone Wireframes](assets/wireframes/home-phone.PNG)  

Tablet

![Home Page Tablet Wireframes](assets/wireframes/home-tablet.PNG)

Desktop

![Home Page Desktop Wireframes](assets/wireframes/home-desktop.PNG)  

#### Wireframes Prices

Mobile

![Prices Page Phone Wireframes](assets/wireframes/prices-phone.PNG)  

Tablet

![Prices Page Tablet Wireframes](assets/wireframes/prices-tablet.PNG) 

Desktop

![Prices Page Desktop Wireframes](assets/wireframes/prices-desktop.PNG) 

#### Wireframes Contact

Mobile

![Contact Page Phone Wireframes](assets/wireframes/contact-phone.PNG)  

Tablet

![Contact Page Tablet Wireframes](assets/wireframes/contact-tablet.PNG) 

Desktop

![Contact Page Desktop Wireframes](assets/wireframes/contact-desktop.PNG)  

The full wireframes can be found [here](assets/wireframes/Keep_Riding_Wireframes.bmpr).

#### Wireframes Comments

Please not there are a few changes to the final site since the wireframes were made:

* Margins and padding were not included in the wireframes.

* Home page: A carousel of images is displayed instead of a single image.
This was added as it fulfils the user need to view several pictures of horses and removed the need for a separate gallery page.

* Home page: The desktop wireframe has all 3 sections side by side. 
Once the margins and specific text was added this view did not look ideal 
so, it was kept the same as the tablet layout.

* Prices page: I added a special offers section like that of lessons/hacks.
This was added as it increases the chance of returning/frequent users booking a block of lessons instead of just one at a time.
It also helps the user save some money and for the business it
increases the chances of returning/frequent users continuing to use this school in the future.
This is also a feature that most riding schools offer as the sport/hobby is costly for regular riders.

* For the contact page a background image and some information on opening times was added.
This was because once the form was created the page looked a bit bare when viewed on a desktop.
It also provides the user with information on when the school is open, helping them decide if this school 
aligns well with their own schedule.

* For the contact page a background image to the form was added. 
This was added as the user wants to see pictures of horses throughout the site where possible.

### Surface

#### Colours

The two main colours used in the website are yellow (palegoldenrod) and brown (saddlebrown).
I picked these colours because I wanted the colour theme to match that of horse riding (brown/beige).

However, I did not want the website to feel dull or bland, so I made some elements turn blue (#0c0cff) when the user hovers over them.  
I also picked pictures with some brighter colours in them, where possible, to help make the website more pleasing to the eye.

I used darkslategrey and whitesmoke colours for most of the text colour and saddlebrown for headings.

#### Typography

The two fonts used are from google fonts these are Roboto Slab for the headings and Montserrat for the body. 

#### Imagery

I found some images from the internet and further information can be found in the credits section.
I aimed to pick a good balance of images to show horse riding in action and horses in a field.

## Features

### Existing Features

* Responsive on mobile, tablet and laptop size devices.

* Interactive elements:
  * Navbar becomes a burger menu on mobile, also hovering over elements (in navigation bar and footer) gives a colour change.
  * Carousel for user to scroll through photos of horses and horse riding in action.

* About Us - allows users to find out who we are and what we do by having them read a short paragraph.

* Facilities - allows users to find out what specific services we can provide and the facilities we have, by reading a list.

* Reviews - allows users to find out how other customers have enjoyed our services, by providing reviews from previous and current customers.

* Prices - allows users to find out what specific lessons are offered and at what cost, by providing the information in a table format.

* Contact/Booking Form - allows users to contact the school if they wish to book a service or ask for extra information. 

### Features Left to Implement

* It would be nice to add a gallery of the horses at the school with a brief description of each. 
Key information for each horse could include name, age, sex, breed, colour, likes and dislikes.
This would make the riding school and horses feel more personable to users.

* It would be good for the site to include information on the instructors so the user is more confident in picking this school.
Details for each instructor could include name, age, years of riding experience, years of teaching experience and any awards received from competitions.  

* It would be nice to have a carousel for the reviews of the riding school on the home page. 
This would allow for many reviews to be displayed on the site without taking up too much space
and further encourage users to book with the school.

## Technologies Used

* HTML - used to create the main content for the website.

* CSS - used to add style and colour to the content.

* [Bootstrap Version 4.1.3](https://getbootstrap.com/docs/4.1/getting-started/download/)
  * Used grid layout to ensure the content was responsive to different device sizes (mobile, tablet and laptop).
  * Used to that the navbar could collapse when viewed on small screens but expand on medium and larger size screens.
  * Used to create the carousel of images on the home page.

* [Gitpod](https://www.gitpod.io/) - used to write the code for the website.

* [GitHub](https://github.com/) - used to store the current and previous versions of the code. It was also used to host the live website through GitHub Pages. 

* [Google Fonts](https://fonts.google.com/) - used to import the Roboto Slab and Montserrat font families that 
are used throughout the website.

* [Font Awesome](https://fontawesome.com/) - used to display the social media icons in the footer of each page.

* [Balsamiq Wireframes](https://balsamiq.com/wireframes/) - used to create the wireframes for the website.

* [Tinypng](https://tinypng.com/) - used to compress the images so they loaded quicker on the website.

* [Am I Responsive](http://ami.responsivedesign.is/#) - used for the mockups of the website on different devices.

## Testing

### Margins

* Checked the margins are consistent across all pages and that they respond to changes in device width in the same way.

### Headers and Footers

* Checked the links in navigation bar and footer worked for all 3 pages. 

* Checked the navigation bar showed the user what page they were on with a bottom border.

* Checked the navbar is responsive - collapses on small screens and expands on medium and larger size screens.

* Checked the links in the navigation bar change colour and become bold when you hover over them. 

* Checked the links in the footer change colour when you hover over them.

### Home Section

* Checked the carousel is responsive and changes image automatically.  
I also checked the controls and indicators work as expected to allow the user to view a specific image. 

* Checked the layout of 3 sections is responsive to different size devices.

* Checked the resized images are used on small screens to improve load time and that the images still look good.

### Prices Section

* Checked the elements are responsive to different size devices.

* Checked there was a bottom margin between picture and tables when viewed on small device and right margin when viewed on medium and larger devices due to the change in layout.

* Checked the images always fill width 100% of their parent div and the height adjusts automatically.

* Checked the images look good when viewed on different screen sizes.

### Contact Section

* Checked the contact-img is responsive to different size devices. 
  * The height changes based on the device the website is viewed on.
  * The positioning changes based on the device the website is viewed on.

* Checked the motivational text and opening times table are horizontally centered in the contact-img.

* Checked the form makes a user enter all text fields: name, email (needs an @ in the field), phone number, 
tick one of the radio box options, select an experience/ability level 
and enter some text in the enquiry textarea.
The form does not check for a correct phone number format currently, only that something is entered. 
To validate a correct number format is entered this requires JavaScript.

* Checked the form is responsive to different size devices. 
  * The label, input and textarea widths change based on the device the website is viewed on.
  * The width and left/right margins change based on the device the website is viewed on.
  * The positioning of the background image changes based on the device the website is viewed on.

* Checked the submit button changes colour and background colour when you hover over it.

* Checked the reset button changes colour and background colour when you hover over it.

### Online Validation

* I checked the website loads and responds as expected on Google Chrome, Microsoft Edge and Internet Explorer browsers.  
I specifically checked the navbar and carousel work as expected on these browsers also.

* Used chrome developer tools and [responsinator](https://www.responsinator.com/) to check responsiveness on mobile, tablet and laptop devices.  
I also checked the website on my HP 15 inch laptop, Philips 20 inch monitor and Sony smartphone.

* Used the [w3c validator](https://validator.w3.org/) to validate my html (for all 3 pages of the website) to check for no errors or warnings. 
* Used the [jigsaw validator](https://jigsaw.w3.org/css-validator/#validate_by_input) to validate my style.css file to check for no errors or warnings. 
I did not validate css of the whole website as this included the imported bootstrap files.

### Lighthouse Validation

I used [lighthouse](https://developers.google.com/web/tools/lighthouse) in chrome developer tools to check the websites performance in terms of 
performance, accessibility, best practises and SEO.
This was done for all 3 pages of the website and for both mobile and desktop devices.
The summary table below shows these metrics.

| Device | Page |  Performance | Accessibility  | Best Practises  | SEO |
|---|---|---|---|---|---|
| Mobile  |  Home | 89% | 100% | 93% | 100% |
| Mobile  |  Prices | 96% | 100% | 93% | 100% |
| Mobile  |  Contact | 73% | 100% | 93% | 100% |
| Desktop  | Home | 95% | 100% | 93% | 100% |
| Desktop  | Prices | 98% | 100% | 93% | 100% |
| Desktop  | Contact | 94% | 100% | 93% | 100% |

Full reports can be found below:
* [Mobile Home](assets/lighthouse/lighthouse-mobile-home.pdf)
* [Mobile Prices](assets/lighthouse/lighthouse-mobile-prices.pdf)
* [Mobile Contact](assets/lighthouse/lighthouse-mobile-contact.pdf)
* [Desktop Home](assets/lighthouse/lighthouse-desktop-home.pdf)
* [Desktop Prices](assets/lighthouse/lighthouse-desktop-prices.pdf)
* [Desktop Contact](assets/lighthouse/lighthouse-desktop-contact.pdf)

From the home reports there is a suggestion to "Serve images that are appropriately-sized to save mobile data and improve load time".
From this I checked [this link](https://web.dev/serve-responsive-images/) and used commands like the example given below
to resize all carousel images 50% smaller and use these for small devices (width under 768px) instead of the full size image used for larger devices:

> convert -resize 33% flower.jpg flower-small.jpg

I also added html code (shown below) so that the browser displays the correct size image to optimise runtime/performance.

> div class="d-sm-block d-md-none" --> Small image here 

> div class="d-none d-md-block" --> Original size image here

I also resized (50%) the images used on the contact page in case this improved performance although it was not directly suggested in the report.
I added a media query into css so that small devices used the resized image instead.

The link above did mention that it is common to serve 3-5 sizes of an image, however in the interest of time I served 2 sizes of each image.
If more time was available more sizes could have been created using the above code and adding some extra html/css code for which image size to display and when.

New metrics for home and contact pages after updates above:
| Device | Page |  Performance | Accessibility  | Best Practises  | SEO |
|---|---|---|---|---|---|
| Mobile  |  Home | 94% | 100% | 93% | 100% |
| Desktop  | Home | 97% | 100% | 93% | 100% |
| Mobile  |  Contact | 80% | 100% | 93% | 100% |
| Desktop  | Contact | 95% | 100% | 93% | 100% |

Full reports can be found below:
* [Mobile Home Rerun](assets/lighthouse/lighthouse-mobile-home1.pdf)
* [Desktop Home Rerun](assets/lighthouse/lighthouse-desktop-home1.pdf)
* [Mobile Contact Rerun](assets/lighthouse/lighthouse-mobile-contact1.pdf)
* [Desktop Contact Rerun](assets/lighthouse/lighthouse-desktop-contact1.pdf)

From the re-run reports above the performance of both mobile and desktop home page improved by this change, 
however the mobile images could be resized a bit better from the report - the 50% I used was a rough guess as I didn't want to resize too much.
The performance of mobile and desktop contact page also improved, however there could still be some improvement for the mobile.

### User Stories from the UX Section

* First Time Visitor Goals  

  * As a first time user, I want to understand the purpose of the website and learn about the riding school.
    * When the user first enters the site, they are greeted with a clear navigation bar when viewed on mobile or desktop devices showing the 
    company name and the 3 pages the user can view. 
    *  Below the navigation bar there is a carousel of images of horse riding and horses.
    This clearly indicates the purpose of the website. There are also many pictures of horses and horse riding throughout the website.
    The carousel will go through the pictures automatically or can use controls/indicators to pick an image to view.
    * The colour scheme (yellow and brown) also matches the theme of horses 
    and horse riding and makes it clear to the user the motivation of the website.
    * From here the user can:  
      * View the carousel images  
      * Scroll down to learn more about the riding school, 
    the "about us" section partially revealed on most devices (see mockups at the top of this file), giving some content hinting and 
    encouraging the user to scroll down. 
    The "about us" section is fully revealed when the website is viewed on a tablet and the "facilities" and "reviews" sections are partially revealed.  
      * Navigate to the prices or contact pages.

  * As a first time user, I want to be able to navigate through the site easily.
    * At the top of each of the 3 pages there is a clear navigation bar which fills the full width of the device screen.
    * When viewed on larger screens the navigation bar has clear text including the company name and 3 links to the pages of the website.
    * When viewed on a mobile device the navigation bar includes the company name and the links 
    collapse into a hamburger icon (which can be opened and closed by the user).
    The hamburger icon is used widely throughout many sites, so this is easy for the user to understand its purpose.
    * All 3 pages also have a similar general shape in terms of margins and padding which makes the user feel assured they are on the same site.

  * As a first time user, I want to be able to view the website on a laptop, tablet or phone and I want the content to be displayed well on any device.
    * The margins and padding respond to the width of the device throughout the site.
    Less margins are given for smaller width devices and more for those with a larger width.
    * All text is easily read when viewed on any device.  
      * The font-size and padding of the links in the hamburger menu are smaller when viewed on a mobile device.  
      * The font-size of the opening hours table content is smaller when viewed on a mobile device.
    * All images are clear when viewed on any device.  
    Also, the background images for the opening hours table and form have different positioning for different devices so the horse(s) can always be seen.
  
  * As a first time user, I want to see what facilities are offered by the riding school.
    * This is shown clearly in its own section on the home page.

* Returning Visitor Goals

  * As a returning user, I want to check the range of lessons that are offered and the prices. 
    * The lessons type (group or private), duration and prices are displayed clearly in the prices page.
    * There are also hacks offered by the school for a more relaxed and informal riding experience.
    * Additionally, there is a special offers section for those dedicated riders to book a block of 5 lessons and save some money.

  * As a returning user, I want to read reviews from current and previous customers about this school.
    * This is shown clearly in its own section on the home page.

  * As a returning user, I want to contact the school to book a lesson and/or ask for additional information.
    * There is a clear contact page and contact form there the user can ask for more information or also enquire about a new or existing booking.
    * There are also the opening times for the school on this page so the user can have an idea on when to expect a response back from the school.
    They can also get an idea if the timing lessons offered would fit with their schedule.
    * When the form is submitted successfully the user is taken to another page that confirms their message has been received.

  * As a returning user, I want to find out where I can follow the riding school on social media platforms.
    * Social media links are displayed in the footer of each page. The footer uses icons which are widely used across the internet so the user will be familiar with what they mean.
    * The footer fills the full width of the device screen, is the same on all 3 pages and placed at the bottom of each page.
    * The links open in a new tab so that the user can view these social media accounts
    and follow/like the school, while remaining on the original website.
    * The social media links allow the users following such accounts to keep up to date with the school.

* Frequent User Goals

  * As a frequent user, I want to check the lessons that are offered.
    * A frequent user can check the lessons offered by viewing the prices page of the website 
    and see the lessons offered.
    
  * As a frequent user, I want to check the cost of the lessons offered and see if there are any special offers.
    * A frequent user can check the cost of lessons offered by viewing the prices page of the website 
     and they can scroll to the bottom to see information of any special offers.

* Business Goals

  * Increase interaction with potential new customers.
    * Users can use the contact form as a way of interacting with the school. 
    They can also follow/like the school on various social media platforms and like/share content they post.

  * Increase presence and following on social media platforms including Facebook and Instagram.
    * Social media links are displayed clearly in the footer and using conventional icons.

  * Increase the number of lessons/hacks booked.
    * Information on services offered is clearly in the prices page of the website, 
    there is also a section on special offers to entice potential new customers.
    Users can then use the contact form to get in touch with the school to book.

### Fixed Bugs

#### Navigation Bar Colours

In the navigation bar the active page text was not showing as the correct colour (saddlebrown).
![Navbar problem](assets/bugs/navbar-problem.PNG)
I discovered the problem using chrome developer tools to find the css selector of the problem text.  
![Navbar fix](assets/bugs/navbar-fix.PNG)

#### Collapsible Hamburger Menu

When the hamburger menu was opened on a small screen, I wanted the navigational items to have smaller text and less padding.
I also did not want the underline to be shown on the active page in this circumstance.

From looking in chrome developer tools I noticed the change in the classes of the div element (highlighted below) 
from "collapse" to "collapsing" to "collapse show".

![Hamburger problem](assets/bugs/hamburger-menu.PNG)

Therefore, I thought I could target the below css selectors. 

> .navbar-light .show .navbar-nav .nav-link, .navbar-light .collapsing .navbar-nav .nav-link  

However, the div has "collapse show" classes when viewed on a larger device and not just when the navbar becomes a hamburger menu.
I targeted the above elements within a media query to solve this.

#### Carousel Images

For the carousel the images I picked had different aspect ratios, 
and this caused the overall height of the element to change every few seconds which was not pleasant to view 
as the below elements also changed position due to the carousel.  

I resolved this by making sure all the images had the same aspect ratio using cropping.

#### Form Fieldset

I made the fieldset height to be 100% so that they looked better on larger screens when these are set side by side.  

However, this made the height of the parent element (div with class “col-12 col-lg-6” in my case) smaller 
than that of fieldset height, which was unexpected.  This also caused issues with the submit and reset button 
positioning and making them inside the fieldset in some situations.

I tried experimenting with different height values for fieldset and its parent div which did not solve the 
problem and then I googled and found this [stack overflow post](https://stackoverflow.com/questions/9116689/fieldset-does-not-follow-its-parents-height
) and from the post some [runnable example that explains the problem clearly](http://jsfiddle.net/3hfytpw4/).  

Running the example demonstrates the problem clearly (images below) you can see that the parent 
does not have the height which aligns with that of the fieldsets.

![Fieldset problem result](assets/bugs/fieldset-problem.PNG)
![Fieldset problem html](assets/bugs/fieldset-html.PNG)
![Fieldset problem css](assets/bugs/fieldset-css.PNG)

After some trial and error, I found that commenting out the padding and margins in the css resulted in the below
desired result:
![Fieldset problem css](assets/bugs/fieldset-fix.PNG)

I removed the top/bottom padding and margins of fieldset and added these instead to the parent/child elements 
of fieldset. Note: The left/right padding and margins did not seem to cause any problems. Perhaps there is a more elegant solution to what I used but this worked fine for my needs, although a bit cumbersome.

#### Minor Fixes

* For the carousel I added a 4th indicator by adding an extra list item to the carousel-indicators ordered list.

* In the prices section I had the images with a width of 100% as inline text, I discovered this error through the  [validator w3c](https://validator.w3.org/).
I removed this from the html and instead targeted these elements in the css file.

* For the text on the contact-img this was hard to pick a suitable colour for the text as the picture
has many colours.  
I added a black transparent overlay so that the white text could be seen easier.

* For the contact form I added a black transparent overlay similar to above, so the white text was easier to read 
where the image had a lighter green colour.  
However, this made the heading, submit and reset buttons look faded out due to the overlay.  
I added the position relative to these elements to solve the issue.

* In the form I wanted the fieldset dotted line to go around the whole element.  
Due to bootstrap the fieldset legend width was set to 100%, discovered from chrome developer tools,
I added a width of auto to the element to solve the problem.

* In the form I made the textarea cols responsive by adding a width of 100% to the element.

* In the form I had set my labels for contact form to have a width of 40%, 
however my label "What is your experience/ability?" was greater than 40% width on some screen sizes causing a truncation issue.  
I changed the property to have a min-width of 40% instead which fixed the problem.

* For my footer I noticed the social media links did not all fit on one line when viewed on my phone, 
so I updated the left/right padding from 10% to 7%.

## Deployment

### Creation

* All code was written in Gitpod and used [this template](https://github.com/Code-Institute-Org/gitpod-full-template) from Code Institute.
* Files were added to the staging area using "git add ."
* Files were committed to the local repository using "git commit -m 'commit message here'".
* Committed changes were pushed to the GitHub repository.

### GitHub Pages

To deploy the project to a live website the below steps were followed:

* Navigate to the GitHub repository you wish to deploy.
* Click on Settings and scroll to the "GitHub Pages" section.
* Choose "master branch" as the source and click save.
* Scroll back down to the "GitHub Pages" section and the deployed website link will be given.
* Note: It can take a few moments for the website to be deployed, so the link may not work immediately 
after you deploy using GitHub Pages.

### Local Clone
To make a local copy of a repository on your own GitHub account you can clone it.
This allows others to view the original code and/or make changes to it (on their own local copy).
Changing the code on your local repository will not affect the original code or deployed website.

To clone a repository in GitHub you can follow the steps below:
* Log into GitHub and locate the repository you wish to clone.
* Click on the code button (to the left of the green Gitpod button) and copy the https URL given.
* Open Gitpod (or another editor if you prefer).
* Use the "git clone 'insert copied URL here'" command.
* A clone of the original repository will now be available for you locally 
on your own repository to view/edit as you wish.

### Forking

Forking is another way to  make a local copy of a repository on your own GitHub account to do this follow the below steps:

* Log into GitHub and locate the repository you wish to fork.
* At the top-right of the repository (and top-right of the green Gitpod button), locate the fork button.
* A copy of the original repository will now be available for you locally 
on your own repository to view/edit as you wish.

## Credits

### Code

* The bootstrap library was used to help make this website responsive for different devices. 

* Bootstrap also allowed me to create a dropdown navigation bar for smaller devices and the carousel on the home page.  
I could not have added these features without bootstrap as I currently do not have knowledge of JavaScript.

### Content

* All the content in the website is fictional and made my myself, I used one of my own pictures and other images from online, information below in the media section.

* I gained inspiration for the layout of the website by looking at other horse riding websites 
including [Hall Place Equestrian Centre](https://hall-place.com/) and [Palmers Riding Stables](http://palmers-stables.com/). 

* The above websites also helped me with what content to put in the 
about us and facilities sections on my home page.

* I had a look at the google reviews for the above riding schools to get an idea of what reviews to make for my fictional school.

### Media

* Carousel-img4 is an image I own.

* I found the following images online from [Pexels](https://www.pexels.com/): 
  * carousel-img3 - owner Helena Lopes [image link here](https://www.pexels.com/photo/white-horse-running-on-green-field-1996337/)
  * lessons - owner Tatiana Twinslol [image link here](https://www.pexels.com/photo/women-riding-horseback-on-sand-in-paddock-5368712/)
  * hacks - owner Helena Lopes [image link here](https://www.pexels.com/photo/people-riding-horses-during-sunset-3854868/)
  * contact-img - owner Eberhard Grossgasteiger [image link here](https://www.pexels.com/photo/four-assorted-color-horse-on-grass-fields-near-tall-trees-during-sunset-1366913/)
  * contact-form - owner Mali Maeder [image link here](https://www.pexels.com/photo/black-horse-running-on-green-field-surrounded-with-trees-101667/)

* I found the following images online from [Unsplash](https://unsplash.com/): 
  * carousel-img2 - owner Elisa Pitkänen [image link here](https://unsplash.com/photos/3ZfwMzo9sy4)
  * special-offers - owner Raphael Wicker [image link here](https://unsplash.com/photos/P6JRr7-FxLw)
 
* I found the following image from [StockSnap](https://stocksnap.io/): .
  * carousel-img1 - owner Matthias Zomer [image link here](https://stocksnap.io/photo/lawn-green-3EV0OZ7ZJO)

* Please note I did minor editing (cropping only) to some of these photos.

The images in relation to the fieldset bug (fieldset-problem, fieldset-html, fieldset-css, fieldset-fix) are from this [runnable example](http://jsfiddle.net/3hfytpw4/)
from this [stack overflow post](https://stackoverflow.com/questions/9116689/fieldset-does-not-follow-its-parents-height).
 
### Acknowledgments

* Code Institute for teaching me the basics of HTML, CSS and bootstrap to allow me to create this website.

* My mentor Antonio Rodriguez who helped provide feedback on this website and improvements that could be made.

* The Slack community for providing support throughout the course so far.  

* Thanks to the fellow students on Slack and my friends who viewed the website and gave feedback on any improvements/changes that could be made. 

* The websites that I used to gain inspiration for creating my own horse riding school website 
([Hall Place Equestrian Centre](https://hall-place.com/) and [Palmers Riding Stables](http://palmers-stables.com/)).

