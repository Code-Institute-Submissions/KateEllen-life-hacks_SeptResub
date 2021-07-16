# Life Hacks

## Author 
Kate_Ellen

## Project Overview 

![Website Display](https://github.com/KateEllen/life-hacks/blob/master/assets/images/documentation/responsive-screenshot.png)


This site is designed for people who love life hacks, but hate waisting time. It has been designed to genuinely help people with daily tasks, and make their lives a little easier. 
This isn't five minute crafts. This is where you come when you want to cut out all the useless life hacks and find exactly what you need, when you need it. 

## UX

### Wireframes 

Below are the wireframes I created when first starting my project. I mainly stuck to the wireframes, only changing certain styles such as the accrodian for the "Mini Hacks" instead of a box. 
- [Homepage](https://github.com/KateEllen/life-hacks/blob/master/assets/images/documentation/wireframe_1.png)
- [Food Hack Page](https://github.com/KateEllen/life-hacks/blob/master/assets/images/documentation/wireframe_2.png)
- [Mini Hacks](https://github.com/KateEllen/life-hacks/blob/master/assets/images/documentation/wireframe_3.png)
- [Mobile Home](https://github.com/KateEllen/life-hacks/blob/master/assets/images/documentation/wireframe_4.png)
- [Navigation](https://github.com/KateEllen/life-hacks/blob/master/assets/images/documentation/wireframe_5.png)

## Design Choices 

#### Colours 

- I chose the colour #38b6ff for the images and footer as it is a calm welcoming colour. It's not too bright or loud making a great user experience. 

- Black was chosen for the font colour to make it easy for users to read. 

- The #1A5276 colour on the navigation was chosen to tie in with the images and footer. I chose a navy/blue colour instead of the same one to make it easily stand out. It is also used in the mobile nav to make it stand out to users. 

- White is used in the mobile nav font as it makes the options very clear to users, as opposed to black.

#### Images

- I created all my main images on [Canva](https://www.canva.com/). I did this to keep the theme across the website as I found it very difficult to find images that were suitable. 

- I found my three image link pictures on [Pixby](https://pixabay.com/). I specifically chose these images as they are of similar colour and style, providing a visually pleasant experience. 

## Features 

### Existing Features 

#### Navigation 
 - Featured across all 5 pages. It is identical across all pages, which allows for easy navigation. 
 - This allows users to easily navigate throughout the website without having to us a back button. 

 ![Navigation](https://github.com/KateEllen/life-hacks/blob/master/assets/images/documentation/life-hack-navigation.png)

 #### Mobile Navigation 
 - The mobile navigation is a convenient 'Hamburger' menu. Which hides to prevent taking up too much space on the mobile site.
 - It is featured at the top right hand corner even when scrolling to allow for easy navigation and a great user experience. 

 ![Mobile Navigation](https://github.com/KateEllen/life-hacks/blob/master/assets/images/documentation/life-hack-mobile-navigation.png)

  #### Image Links 

  - This section on the homepage allows users to navigate to the three content pages without having to scroll back up to the navigation. It also adds some fun imagery to indicate what page you will be navigating to. 
  - The images feature large buttons that stick with the colour theme helping users to see which section they will be going to. 

![Image Links](https://github.com/KateEllen/life-hacks/blob/master/assets/images/documentation/image-links-screenshot.png)

#### Footer
 - The footer features social media links for the website's socail media account. Making it convenient for user's to interact. 

 ![Footer](https://github.com/KateEllen/life-hacks/blob/master/assets/images/documentation/footer-screenshot.png)

 #### HTML & CSS Accordian/ "Mini Hacks"
 - The accrodian featured at the bottom of all the pages (excluding the homepage and form page) make a fun accessible way to show extra hacks that you don't need a video to explain. 
 - The accordian also tidies up the page and saves space. Preventing the pages from getting too cluttered looking. 

 ![Accordian Closed](https://github.com/KateEllen/life-hacks/blob/master/assets/images/documentation/accordian-closed.png)
 ![Accordian Open](https://github.com/KateEllen/life-hacks/blob/master/assets/images/documentation/accordian-open.png)

 #### Form 
 - The form page is easily accesible and a convenient way for users to submit their own ideas with ease
 - It is easily read with clear instructions, and the link is featured across the website and featured on the navigation so users can find it anywhere on the site.

 ![Form](https://github.com/KateEllen/life-hacks/blob/master/assets/images/documentation/form-screenshot.png)

### Features left to impliment. 
- I would like to add a site wide competiton to the form section, to encourage people to send in ideas. 
- The competition would be featured as "The Best Life Hack Awards". Where the winner would recieve a prize as insentive. 
- There would be a public vote held on the social media accounts to choose the winner. 


## Testing

### Lighthouse Audit 
- Home Page 
![Homepage Audit](https://github.com/KateEllen/life-hacks/blob/master/assets/images/documentation/lighthouse_1.png)
![Food Hack Page](https://github.com/KateEllen/life-hacks/blob/master/assets/images/documentation/lighthouse_2.png)
![Form Audit](https://github.com/KateEllen/life-hacks/blob/master/assets/images/documentation/lighthouse_3.png)

### Validator Testing 
#### W3C CSS Validation 
1. When I first put my CSS through the validator I recieved 1 error. ![Css Error](https://github.com/KateEllen/life-hacks/blob/master/assets/images/documentation/css_validation_1.png)
2. I went to the line of code where the error was and fixed it. This resulted in my CSS passing validation. ![CSS No Error](https://github.com/KateEllen/life-hacks/blob/master/assets/images/documentation/css_validation_2.png)

#### HTML Validator 
- I fixed a lot of errors using the HTML validator, but due to time restriction not all could be resolved. 

#### Cross Browser and Device Testing

- I tested my site on the below. 
1. Samsung S20 - 5.97 X 2.72 
2. MacBook Pro - 12.78 X 8.94 
3. dev tools emulator: pixel 2 - SM 411 x 731 mm

- It was also tested on safari, chrome and firefox. 

### Outstanding Defectsgs 

- On some smaller screens the three images on the home page can line up incorrectly. Due to time restrictions I did not fix this. 

![Image Defect](https://github.com/KateEllen/life-hacks/blob/master/assets/images/documentation/image_defect.png)

#### Submission form:
    1. Go to the "Your Ideas" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address with no @ symbol and verify that a relevant error message appears
    4. Try to submit form without entering name and verify that an error message appears.
    5. Try to submit the form with all inputs valid and verify that a success message appears.

#### Accordian: 
    1. Go to "Cleaning" page.
    2. Scroll down to the bottom of the page and click the "mini hacks" bar.
    3. Make sure it shows content and doesn't overlap the footer when it is extended.
    4. Repeat on "DIY" and "Food" pages to ensure they all work and look the same. 

#### Social Media Links: 
    1. Open any page on website. 
    2. Scroll to the bottom of the page where the footer is and hoover over each to ensure they change color and rotate. 
    3. Click on each link to ensure they bring you to the correct social media page, also ensure they bring you to a new tab. 
    4. Reapeat on all pages to ensure they all work correctly as above.             

## Deployments 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  ![Settings Tab](https://github.com/KateEllen/life-hacks/blob/master/assets/images/documentation/deployment_1.png)
  - Scroll down the page and find the Github pages section, and click on the link.
  ![Github Page Link](https://github.com/KateEllen/life-hacks/blob/master/assets/images/documentation/deployment_2.png)
  - From the source section drop-down menu, select the Master Branch
  ![Select Source](https://github.com/KateEllen/life-hacks/blob/master/assets/images/documentation/deployment_3.png)
  - Select the save button. 
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://kateellen.github.io/life-hacks/

### Credits 

## Content 
-  Mini Hacks content were taken from the below. 
- [Love Food](https://www.lovefood.com/gallerylist/70590/50-food-hacks-that-are-borderline-genius)
- [Good House Keeping](https://www.goodhousekeeping.com/uk/house-and-home/household-advice/a27451631/ghi-best-cleaning-hacks-tips
)
- [Best Life Online](https://bestlifeonline.com/easy-home-hacks/)

- The icons in the footer were taken from [Font Awesome] (https://fontawesome.com/)

## Acknowledgments
- I would like to specifically acknowledge my mentor Malia. She has steered me in the right direction throughout this entire project. 
- The Love Running walkthrough project was a great tool. It allowed me to easily find solutions to problems I knew I had already done that I just needed a refresher on. 
- I learned how to do the accordian thanks to [CodePen](https://codepen.io/alligatorio/pen/KKzWqVX).
- Watching this handy video Youtube helped me with making my Youtube videos responsive. [tipswithpunch](https://www.youtube.com/watch?v=9YffrCViTVk)
- For my hamburger menu I used a combination of online tutorials [medium.com](https://medium.com/@heyoka/responsive-pure-css-off-canvas-hamburger-menu-aebc8d11d793) and my mentor Malia. 
- My responsive image on this README.md was created with [Ami.responsivedesign] (http://ami.responsivedesign.is/#)