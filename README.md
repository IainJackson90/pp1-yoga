# YOGA

## [Click here to view website ](https://iainjackson90.github.io/pp1-yoga/)

YOGA is a site that will help people to find a place of relaxsation after a long
day.
It is a place where you can experiance to be mindfull and present in the moment, 
a place to conect with nature or just relax in a sauna.
We have many facilities avalable to be used at your own descretion.

![Am I Responsive](./assets/docs/am-i-responsive.png)

# Features

The website is designed to be user friendly, simple and responsive.

## Exsiting Features 

- _Logo_

  - The logo is a link to the home page , displayed on each page of the webpage.
  - It is intended as a home panic button

![Logo](./assets/docs/logo.png)
    
- _Navigation Bar_
  
  - The navigation bar has links to three pages to make navigating trough the 
     website simple.
  - The navbar is displayed on the top right on larger screen sizes and displayed
    underneath the logo on smaller screen sizes
  - Each page has the navigation bar exept the thank you page
  - When hoveriong over the navigation bar the tex font will increas in size to
    make it visualy more simple to see whitch page you want to select
  - The nav bar will also have a undrline to show whitch page you are currently
    viewign.  
   
![Navigation bar](./assets/docs/nav-bar.png)

- _Landing page image_
  
  - The landing page is picture about capturing peace and being mindfull and in 
    the moment setting the mood for the website
  - It also will give an idia of what the content of the website is about 
    
![Hero Image](./assets/docs/hero-image-readme.png)
    
  - Ontop of the landing page image is a animation that does a breathing efect
    trying to simulate a deep breath in and a long breath out.
  - the animation is on the bottom right on larger screen sizes and will move 
    to the top left on smaller screen sizes
    
![Cover text](./assets/docs/cover-text.png)

- _Why you should start YOGA section_

  - This section is about good health benifits you will start to feel 
  - it gives the user a idia of ehat to expect when they do yoga
  - it will provide usifill information to the user if yoga is what hey are looking to do
 
![Why start YOGA](./assets/docs/why-start-yoga.png)
    
  - On the right of the content is a picture, on larger screens it will display on the right
    and on the smaller screen sizes it will display underneath the "why you should start yoga"
    section

![YOGA section picture](./assets/docs/man-yoga-section.png)

- _Facilities and Operating hours_
  
  - This section will provde infromation to the user of what they can expct to find
    when they join the classes
  - It will also disply a table of operating hours 

![Facilities and Operating hours](./assets/docs/what-we-do.png)

- _The Footer_
   
   - The footer is available on each page 
   - The footer has social meadi links 
   - The social links has a pop up animathin when you hover over them to give a button feeling

![Footer](./assets/docs/footer.png)

- _Gallery_
  
  - The gallery will have images of what the classes will look like 
  - this section will provide the user with visual content describing what to expect
  - The gallery is responsive and will arange content dependent on screen size 
  
  ![Gallery](./assets/docs/gallery.png)
   
- _Sign Up Page_

  - This page gives the user a opertunity to sing up for a class ither indoor
    or outdoor classes
  - it also contains contakt information fot he user if they feel to get in touch
    for any aditional information 

![Sign-Up](./assets/docs/sign-up.png)

- _Features left to implement_
  
  - Have live online YOGA classes
  - Hvae a motivational mindfullnes content section
  - Have a coment section where users can rate there classes

# Testing

While building the webpage i have incounterd some bugs:

- _Bugs I Encounterd_
   
   - Nav Bar
    
     - The navigation bar did not display in the order it was intended or in the order
       i have placed them in the html page.
       I fixed this bi placing the nav bar into a flex-box, it changed the order
       to how i intended it to be.
       
   - Hero image 
     
     - The hero image is a large size whitch has a impact on the performanse, i have
       made a consius dession to keep it this way for qauality aof the image and also 
       the image fit the content of this page very well
     - The hero image looked very dull over the background so i added a thin border to make 
       it stank out more to give it contrass
       
   - why you should start yoga
     - The content and imagage I had in  two seprate divs and strugled to get the content
       and picture to work corectly together with sizing when i change screen sizes,
       I found placing both of the divs into a flex-box i manage to get the content
       and the picture be responsive to the idia i had.
     - The Picture is not displayed in the native reselotion it is a bit stretched 
       and caouses a performance isue, I feel the image does not look visualy unpleasing
       and i need it to be the size it is to fit the content.
       
   - Gallery
  
     - The gallery images was overflowing into the head of the page,
       I fixed it by giving the head of the page a fixed hight and a margin bottom 
       whitch pushed all the gallery images down away from the head of the page 
       
   - sing Up Form

     - The sign up form had some contrass problems so i gave the div a transparent 
       dark background so the user can see the contetn better and not take away the 
       ambioance of the background 
       
    
# Validator Testing 

I put the website trough a series of validators to make sure it conforms to a valid 
standard here are the tests and resaults 

## [HTML Validattor ](https://validator.w3.org/)

All the html pages was validated and had noe errors, oonly had warnings about 
the comments i left in the purposefully to help navigate trough the code easier

![HTML Validaror](./assets/docs/html-validator.png)

## [CSS Validator](https://jigsaw.w3.org/css-validator/)

All CSS has been validated and is free from erros

![CSS Validator](./assets/docs/css-validator.png)

## Lighthouse testing for desktop

![Lighthouse Test Desktop](./assets/docs/lighthouse.png)

## Lighthouse testing for mobile 

![Lighthouse test Mobile](./assets/docs/lighthouse-mobile.png)

## [Contrast Validator](https://color.a11y.com/)

![Conrtast validator](./assets/docs/contrast.png)
