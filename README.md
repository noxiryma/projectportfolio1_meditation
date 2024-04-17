# Project Portfolio 1 - So Hum 
## A meditation for beginners website with a fictional meditation group 
### PP1 - Amy Rixon - 19/04/2024

![I am responsive screenshot](assets/images/readme-images/pp1shair.jpg)



## **[Live Site](https://noxiryma.github.io/projectportfolio1_meditation/index.html)**
## **[Repository](https://github.com/noxiryma/projectportfolio1_meditation)**


## Table of contents

1. [ UX ](#ux)
2. [ Features ](#features)  
3. [ Features Left to Implement ](#left)  
4. [ Technology used ](#tech) 
5. [ Testing ](#testing)  
6. [ Bugs ](#bugs)  
7. [ Deployment](#deployment)
8. [ Credits](#credits)
9. [ Content](#content)  
10. [ Acknowledgements](#acknowledgements)  


## UX

### Colour Scheme 

The colour scheme I chose for this website is one that is both warm, earthy and calming. The aim is to invite the user to have a relaxing experience whilst gaining information on the subject of meditation which whilst practicing this will also lead to a calm and clearer mind. 

The colours I chose were aided with the help of the website **[Color Mind](http://colormind.io/)** and the details of the three colours I chose for the content are as follows:

![Color wheel screenshot](assets/images/readme-images/color-wheel.jpg)

>A dark brown with a warm undertone: #401c04
>A terracota pink: #de8e8a
>Plain white: #ffffff

Images used for the website also compliment the main colour scheme of the design with rich warm tones and have a good contrast so the pictures are seen clearly. 

### Font 

The font family used for this site is 

"Montserrat Alternates", sans-serif; 

![Montserrat Alternates 400 screenshot](assets/images/readme-images/montserrat-400.jpg)

with a weight of 400 for the main content and a weight of 700 for the title header. Used to imply a logo for the site and give a clear heading.

![Montserrat Alternates 700 screenshot](assets/images/readme-images/montserrat-700.jpg)


The font was chosen for it’s accessibility as well as it’s design. The text is clear to read and has a more rounded style creating a smooth and relaxing experience for the user whilst they read and learn new information on the subject of meditation. 


## FEATURES

## Parallax

The initial design for the website was to have a main banner image at the introduction of each page followed by sections of information separated with a circular image accompanying them. During my first mentoring session where I had built the basis of the website and had started this design on my home page, my mentor advised I experiment with parallaxes and flipcards. After introducing a parallax on the home page as the introduction image I decided to make the whole page include the parallax feature with each new section of information there would be a new parallax image and each section would have a translucent white background with the text aligned centre of the page. 

## Flex 


Whilst I wanted to include this parallax feature throughout the website the postures.html page was an important page to have the images displayed clearly as the demonstrate information that the user would need to access. Not being able to see the visual information clearly this could lead the user to practicing the postures incorrectly and would go on to cause discomfort or injury over time. 

The images were aligned on the page using flex in css and are balanced through the page with images alternating positions on the page to demonstrate a new posture to try and section of information. 

I experimented in the building of the website with flipcards for the postures page but because it was important to include all the information regarding each posture along with their variations. The flipcards were too small but also didn’t fit the flow of the website so I chose to use the above method instead in portraying this information. 


### index.html 

![Home Page screenshot](assets/images/readme-images/home-laptop.jpg)

The home page header contains a link to the home page with the title of the website. A favicon is used in the tab title of the webpage of a person sat in a meditation posture (an iconic visual link to the subject of the website). The navigation bar is positioned to the right, written in a list format in html and styled in css to display inline. 

![Home Page header screenshot](assets/images/readme-images/header.jpg)

There was spacing added between each of the links to make the text and title of each link clear as to where the user is navigating too with a border bottom feature added in css to highlight which page the user is currently on. A hover over feature has also been written to show the user which link they are about to click. 


In a responsive smaller screen from 320px to 768px the navigation menu moves to be stacked on top of one another but still with the feature of a border at the bottom of the active link. 

![Home Page 320px screenshot](assets/images/readme-images/320-home.jpg)

Each section of text is aligned to the centre with spacing between the lines of text added so it is clear and easy to read. 

![Home page roots of meditation screenshot](assets/images/readme-images/home-page-content.jpg)

The parallax feature encourages the user to keep scrolling down to the bottom of the page and the final image links with the sign up page as this section encourages the user to sign up to join group meditations which is a service this website offers for beginners. There is an internal link to the sign up page in this section. 

![Home Page last section screenshot and footer](assets/images/readme-images/home-page-footer.jpg)

The footer contains links to social media websites where if this was an official website there would be a direct link to their pages demonstrating different techniques of meditation and motivation for the user. 

### postures.html 

![Postures page screenshot](assets/images/readme-images/postures-top.jpg)

The second page of the website was originally going to be regarding techniques but on thought of the layout of information it is better to be in the correct posture before implementing the practice. 

![Postures page content screenshot](assets/images/readme-images/postures-content.jpg)

The layout of this page starts with a parallax and then displays clear images of each posture and has a rule of three in regards to the information given. Each section apart from the first and last has 3 subtitles of the subject clearly stated. Displaying what the posture is and the benefit, the method of getting into the posture and a variation should the user wish to make this posture more comfortable for them. 

![Postures page content screenshot responsive](assets/images/readme-images/320-postures.jpg)

In the responsive smaller screens the images are placed to fit the width of the screen and as the opening of each new posture. This was altered in the media query for screens up to the size of 768px. 

### techniques.html

IMAGE OF TECHNIQUES PAGE 

The postures page is more important to have a visual instruction aid whereas this page it was more important to portray the information for the user via text. So the parallax feature was reintroduced on this page and flex was used to design the layout of each section to make them align in columns of three. 

Each new technique has a new parallax image to clearly show the user they are moving on to the next technique along with a clear to read centred heading for each section. 


### signup.html 

IMAGE OF SIGN UP PAGE 

The sign up page for the website has a clear heading to detail why and what the user is signing up for. As it was important to have relevant digital contact information only the email address and a location is asked for to determine where the user is located. Radio buttons were used to have the user select when and how often they wish to join the group meditations. Each field is required and has been tested before submission that all must be completed before submission. 

The parallax image used on the home page is used again on this page as the two sections are linked together and gives the user a visual link. 

The submit button has a hover over feature to change colour to show the user that they are about to click the link to submit. 



## Features left to implement

### Home Page 

In future I would like to add a responsive icon for the navigation menu for smaller screens so it is cleaner and less busy in the header on smaller screens. 

I would like to add links in the benefits section to studies made on meditation and their benefits. 

I would like to make the introduction quote changeable to be a different affirmation for the user to see each week. 


### Postures page 

I would like to have a video with subtitles accompanying each posture to give the user a live follow along to see how to get into each posture with clear instructions on variations and who these variations are good for. 

I would have liked to have had more consistent images of the same person or a more diverse range of people demonstrating each posture to show that meditation is for everyone. 

I would have liked to include a link to a business willing to be associated with the website who can sell the user props with a discount code link from this website. 

### Techniques 

I would like to have had a audio file or a video with subtitles to demonstrate each technique and to have something for the user to follow along with in real time. 


### Sign Up 

I would have liked to include a gallery of the groups of people that currently meet for meditation practice. 

I would have liked to include an interactive map to help the user locate their nearest meditation group.

I would have liked to have had an information section on groups that are going to be appearing in new locations. 


### Technology used 

