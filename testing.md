# Testing #

- All the features of this project have been manually tested  in order to make sure they respond effectively. Moreover, users can move from page to page since all of them are interconnected. 


- In the case of the ** Resume feature **. The document is open in a different window, giving the user the chance to download the document in a pdf format. 

 - Contact form:
When filling the form if the information required in the contact form is not correct (wrong email format, or not filling the text boxes.) an error message about the required fields will appear. 

As part of the testing process this website was tested using:
 - [W3C Markup Validator](https://validator.w3.org/) 
 - [Jigsaw W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

- To achive the correct validation through these validator some modifications were made. such as:
   - The hamburger menu had to be replaced since the one originally used was not compatible. 
   - the buttons menu had to be also restructured since "a" elements can not be child of buttons. 
## W3C Markup Validator

- ## Home page ##

![Home page](Readme-images/index.png)

- ## Contact page ##

![contact](Readme-images/contact.png)

- ## Portfolio page ##

![portfolio](Readme-images/portfolio.png)
 
- ## Skills page ## 

 ![skills](Readme-images/skills.png)



## W3C CSS Validator

![CSS](Readme-images/w3c_css.png)




 This web has been tested in the following browsers:

 - [Mozila fire fox](https://www.mozilla.org/en-US/firefox/new/)
 - [Opera](https://www.opera.com/)
 - [Chrome](https://www.google.com/chrome/)
 - [windows Explorer](https://www.microsoft.com/en-us/edge).


 ## Responsiveness ##


This website is responsive. Consequently, it has been developed as to  be displayed in any device. 
The main changes users can evidence when accessing the site in a different device are:
In devices up to 576px two menus are desplayed. One in the upper site of the page. known as hamburger menu. the other one is located in the lower part of the site. just before the footer where users can also find another menu with bigger buttons. 

In devices with more than 576px  all pages have a top fixed navigation bar. 

As illustrated in the image below, this website has been tested in all devices  available in Google chrome Developers tool. The results are the followings:


![responsiveness](Readme-images/table-0.png)

![responsiveness](Readme-images/table-1.png)

As we can see the website responds effectively in all devices except for the Portfolio page in the Galaxy fold. In this device some images and texts are slightly resized and moved. but still noticiable. 

## Bugs ##
I had some problems with the navigation bar. I  tried doing it myself but when i got to make the dropdown menu work, it did not work. finally made the menudrop work. It needed to  add the query link from boostrap to the header.

- After having fixed the problem mention above i came across with another problem related to the drop menu, When validating in the W3C Markup Validator site. This time the validator showed an error related to the use of buttons inside the 'a' Element which made me change the whole menu since. according to the validator this

- In order to pass the validator i also had to replace some "sections" for "divs" since the validator indicated that those sections were missing a header. 

- When trying to add a description to the images from the gallery i could not add a layer to the element "img" therefore i decided to omit this feature. 

-
## As recruiter I want to :
- **Have access to examples of projects that the developer has built.**
  - When the recruiter or client clicks on **Portfolio** is brought to a gallery of images with examples of the works the developer has built or made part of.

- **See the developer's skills**
  - In the **skills** page The user can find the developers skills illustrated in two graphic that display the level of performance and knowledge regarding the different technologies the developer works with. 

- **Interact with the examples given but the developer**
  - In the **portfolio** page  the images from the gallery are linked to the websites so as to let developers to interact direclty with the examples. 


- **Have direct contact with the developer**
  - In the **contact** page there is a text-box where users can sent a direct message to the developer. Also, the telephone number and email are attached to this page as to facilitate the direct interaction between the recruiter and the developer. 


- **Reach the developer through his social media channels**
  
  - In the footer the user can find all the links to the social media of the web developer 
    - [Faceook](https://www.facebook.com/)
    - [Instagram](https://www.instagram.com/)
    - [Twitter](https://www.twitter.com/)
    - [Github](https://www.github.com/)
    - [Linkedin](https://www.linkedin.com/)
 

- **Know about his educational background.**
  - when accessing the resume page the user is redirected to a pdf file with his personal information: Educational background and working experience. 

- **To move easly and intutively through the wbsite.** 
  - In order to make the page accessible and intuitive, the page counts with a navigation bar fixed at the top of the website for devices with a minimun width up to 768px. Devices with a maximun width up to 768px display a dropdown menu fixed in the top of the screen, as well as another navigation menu placed just above the footer. 


- **Find easy what i am looking for.**
  - The page is design to let people reach any feature of the website with less than three clicks starting from the home page. 




 

