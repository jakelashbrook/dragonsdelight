# Dragons Delight Cafe and Bakery Website

[You can view the project here on Github Pages](https://jakelashbrook.github.io/dragonsdelight/.)

![Site Screenshot](/assets/images/site-screenshot.jpg)

This is the main online prescence for Dragons Delight excluding their Social Media profiles. The aim is to
provide everything that customers are looking for in one place. It is designed to be responsive so that 
users can access it from multiple devices. This site will be made with a mobile first approach due to the fact
the main income of the business comes from adventurous tourists exploring Amsterdam.

User Experience (UX)
===== 
  - First Time User Goals:

    - a. As a first time user, I want to access a menu to see what products are available should I choose to visit.
    - b. As a first time user, I want to be able to easily navigate through the site content and find what I'm looking
         for with ease.
    - c. As a first time user, I want to see pictures of the restaurant and food to act as evidence of the standard and quality of food. 
    - d. As a first time user, I want to easily find contact methods such as social media, email or telephone links.


- As a Returning user:
    - a. As a returning visitor, I want to know how to make a reservation.
    - b. As a returning visitor, I want to check that the opening times have not changed.
    

- As a Frequent user:
   - a. As a frequent user, I want to know how I can keep up to date with all the latest
        Dragons Delight news. Is there a newsletter?
   - b. As a frequent user, I want to know about any loyalty schemes or special offers available to customers.  

   
 ## Design 

  - **Colour Scheme:**
        - The colour scheme for the website will be an offshade of white (#fafafa), a dark shade of grey (#323232) and a light brown 
          (#daa520) to bring in the idenity of the business and their colour scheme within the building.
  - **Typography:**
        - Originally there were going to be two fonts used across the site, both supplied by [Google Fonts](https://fonts.google.com/). 
        "Just Another Hand" for the headings and logo of the site, and "Noto Sans JP" for the rest of the site. 
        Sans-serif will be used as the backup default font-family. However, after doing UX Survey (See in Testing Section)
        it became clear that users were struggling to read the headings. So I opted to use "Noto Sans JP" across the site,
        and "Just Another Hand" exclusively for the logo.

  - **Imagery:**
        - Imagery will be used frequently in the site to catch the users attention and entice them to sample
        some of the great products available. The page will consist of areas with Images as backgrounds,
        and there will also be a Image "Gallery" Section for users to look through. 

## Wireframes
       
#### The Mobile Wireframe  

![mobile wireframe here.](/docs/wireframes/mobile-wireframe.jpg)

**_The site will have one page with 3 sections within it. There are 4 wireframes sketched for the desktop version.
Please see the Images for each wireframe below:_**

#### The Navigation Wireframe  

![Navigation Wireframe](/docs/wireframes/navigation-wireframe.jpg)  

#### The Menu Wireframe  

![Menu Wireframe](/docs/wireframes/menu-wireframe.jpg)  

#### The Reservation Wireframe  

![Reservation Wireframe](/docs/wireframes/reservation-wireframe.jpg)  

#### The Gallery Wireframe  

![Gallery Wireframe](/docs/wireframes/gallery-wireframe.jpg) 

The site has slightly evolved in the process of design, I re-evaluated my UX Stories several times throughout
the design process to make sure I had fully assessed the culture and experience needs of both the user and the
company. I decided a good way of keeping up with relevant news would be a newsletter, so that those who did not
posess Social Media accounts could remain in the loop. I also decided that the Reviews Section was unnecessary on
Mobile Devices due to the auto-scrolling feature making it appear glitchy. There is a link in the main navigation to
the source of the reviews content- so i decided to address this feature in a future release where i hope to make a 
specialised website for mobile users that address their specific needs and evolving the first release to cater just 
for larger devices. See the Release Planning Section for more details! 

## Features
  - Easy navigation through the site with a scroll to the top button on all buttons, 
    and fixed navigation on desktops.
  - Responsive on all devices, including the Samsung Galaxy Fold. Smaller than Bootstrap Breakpoints.
  - Social Media Links, with future further integration planned with Facebook Messenger.
  - Easy Order Now CTA on all devices.  
    


Technologies Used
====

### **Languages Used:**  

- [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)  

- [CSS3](https://developer.mozilla.org/en-US/docs/Archive/CSS3#:~:text=CSS3%20is%20the%20latest%20evolution,flexible%20box%20or%20grid%20layouts.)

### **Frameworks, Libraries and Programs Used:** 
1. [Bootstrap 4.0.0:](https://getbootstrap.com/docs/4.5/getting-started/download/)
    - Used throughout the website for responsive components and the grid system.
2. [Google Fonts:](https://fonts.google.com/) 
    - Used to import the 'Just Another Hand' for the site title and certain features and 'Noto Sans JP' fonts to the
      style.css page. Both fonts are used across the entire site.
3. [Font Awesome:](https://fontawesome.com/)
    - Used across all sections in the site to catch the users attention and fit with UX 
      conventions of being able to easily identify the meaning of content areas and links from the icons 
      displayed.
4. [Git:](https://git-scm.com/)
    - Used for maintaining version control for possible later edits, changes, updates or fixes. 
      The Gitpod terminal was used to commit to Git, and then Git pushed to GitHub.
5. [GitHub:](https://github.com/)
    - Used to store the project as a repository after being pushed by Git. 
6. [W3.css](https://www.w3schools.com/w3css/default.asp)
    - Used to add extra responsivity and styling to the layout of the cover Image text overlay. 
    I originally planned to include more W3.css animations on the gallery area, but decided to hold back 
    for a later release so the site can visibly grow more over several releases.
7. [EZ Gif](https://ezgif.com/)  
    - Used to edit the width/height of images and decrease their file sizes
   whilst maintining the maximum quality possible. 
8. [Minify Code](http://minifycode.com/)   
   - Used to Minify the CSS file to improve rendering performance by the
    browser. Minify Code was also used to beautify the HTML code to make easier for other developers to read through
    the document.

Testing
====
### **Validation** 
The W3C Markup Validator and The W3C CSS Validator Services were used to validate every page of the project
to ensure there were no syntax errors in the project:  

  - [W3C Markup Validator - Results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjakelashbrook.github.io%2Fdragonsdelight%2F)
  - [W3C CSS Validator - Results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fjakelashbrook.github.io%2Fdragonsdelight%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)  

### **Testing User Stories from the UX Section**
 - **First Time User Goals:**  

    i. As a first time user, I want to access a menu to see what products are available should i choose to visit.  
      - a. Upon entering the site, users are instantly greeted with the option to go to the Menu on the top navigation 
      bar.
      - b. Once clicking on the "Menu" button you're taken directly to the Food and Drink Menu section of the site.
      - c. The user has the option to collapse or expand either Menu.  
    
    ii. As a first time user, I want to be able to easily navigate through the site content and find what I'm looking
        for with ease.  
      - a. Upon entering the site, you find a fixed navigation bar that takes you to all the main sections of the site.
      - b. Throughout the site there is a "Back to the top button" that will take the user back to the top of the page at 
        a click.  

    iii.  As a first time user, I want to see pictures of the restaurant and food to act as evidence of the standard and quality of food.
      - a. Upon entering the site, you are met with a cover image displaying succulent Vegan Pancakes filled with berries to act as a
           taster for the standard of food you can expect to find at Dragons Delight.
      - b. As soon as you enter the site you are given the option to navigate straight to the gallery using the top navigation menu.
      - c. You can find images of food throughout the page acting as background images for informative content.   
    
    iiii.  As a first time user, I want to easily find contact methods such as social media, email or telephone links.  
      - a.  There are contact methods for emailing and calling displayed in the naviagtion menu with icons and titles describing them upon hovering.
      - b.  There are also Social Media Links available in the top navigation, which users could also contact Dragons Delight via.
      - c.  There are further email and call links provided underneath the opening times encouraging users to contact if they have any enquiries.
  

 - **Returning User Goals:**  

    i.  As a returning visitor, I want to know how to make a reservation.
      - a. As soon as you enter the site you are given the option to "Reserve". Upon clicking 
      the "Reserve" button in the top navigation you are taken to the reservation form.
      - b. Users that are unsure are encouraged to make enquiries via email or phone using links 
      at the bottom of the Opening Times section.

    ii.  As a returning visitor, I want to check that the opening times have not changed.
      - a. Upon entering the site you see the Opening Times section straight away underneath the 
      cover image.
      - b. Users are encouraged to make enquiries via email or phone within this section if they need
      assistance.

 - **Frequent User Goals:**  

    i. As a frequent user, I want to know how I can keep up to date with all the latest
    Dragons Delight news. Is there a newsletter?
      - a. The website offers Users the chance to sign up to the company newsletter by simply entering
      their email address and clicking "submit". 
      - b. The website also highlights the Social Media Links for Dragons Delight, and informs Users that
      they can keep up to date with all the latest news via Facebook and Instagram.  
      
    ii. As a frequent user, I want to know about any loyalty schemes or special offers available to customers.  
      - a. The website offers information about the loyalty card scheme and how it works underneath the 
      newsletter sign up banner. 
      - b. Next to the Loyalty Scheme section, there is information about the special Student Club currently
      on offer at Dragons Delight. Users can click the email link to sign up.

### **UX Survey**
As part of my User Experience analysis I decided to run a survey with close family and friends, and the company
that the website will be for. During the testing phase I deployed the site to GitHub pages and made a survey with 
the following questions:  

- **1. What changes could be made to make the site look more appealing?**
    - One survey reply suggested to use snaps with customers in, however the company
    did not want to use this approach out of fear of not having consent to publish.
    - Another response suggested using better quality photos. This was a tough part of
    designing the site. Currently most of their content library is amateur photography.
    The company plans to get a photographer in for some proffesional photos, at this point
    all images on the website will be upgraded. Images have been set at 600x600 to try and make 
    them as responsive as possible.
    - Another User suggested changing the heading font on the sections to make the site more 
    readable. This action has been taken and now only has Noto Sans JP across the site accept 
    for the logo title.  

- **2. What could be improved with the functionality/navigation of the site?**
    - One Survey User suggested the button to the top didn't take the page right to the top
    of the page. This comment was immediately addressed and has now been fixed.
    - Other suggestions were noted for later releases when Javascript will be added.
- **3. What other functionalities do you think the site should have?** 
    - Most Users of the survey stated that nothing came to mind.
    - One User stated a Cake Ordering System, this is planned for a later release.
- **4. Do you have any suggestions for other improvements to the site?**
    - The majority of survey users had nothing to add.
- **5. How would you rate your overall experience with the website?**
    - All Users voted Good or Very Good.  

Some of the answers in the survey were deemed irrelevant because the Users had merely overlooked 
things rushing through the process of evaluation. All answers have been throughly investigated, 
the issues raised that haven't been addressed in this release will be scheduled for the next so
that Users feel a sense of evolution when returning to use the site.

*You can view the survey results [here](/docs/ux-survey-results.pdf).*

### **Further Testing**
  - The website has been tested on Google Chrome, Internet Explorer, Microsoft and Safari Browsers on 
  multiple occasions.
  - All links on the site have been thoroughly tested on numerous occasions.
  - A User Experience Survey was completed by friends and family, as well as staff members of Dragons
  Delight.
  - The website has been viewed on a variety of devices from Desktop, Laptop, a series of iPhones, iPad,
  Moto G4, Huawei, Pixel, and more.
  - Google Lighthouse was used throughout the development of the site.
  - Responsinator was used used in the later stages of testing the site.


Release Planning
====

**Initial Release**  

This is the current version of the website. Everything you see in the [linked repository](#) is the first release
of the Dragons Delight MVP website. There will be later releases planned as my coding knowledge expands so that
the site can continue to grow and evolve to meet the users and companies needs. Time is also a factor in assesing 
later releases. Stages are yet to be decided, but you can see a list below of areas that will be addressed in future
releases.


**Later Releases**  
- A seperate design for mobile phone users. I believe the culture of users on mobile phones is different to 
those who would be accessing the site via laptop or desktop. Users on mobiles are generally in a rush to find
information. Meaning they want things short and sweet, quick actions on the go. So with this in mind, I would 
like to make an exclusive version of the site for mobiles when the time is available. This would be heavily 
focused on touch screen devices and how the site needs to be easy to use without keyboards and mouses. This will
be easier to enforce once I have learnt how to code with Javascript. Eg. A touchscreen friendly swipe "Gallery" 
for mobiles and tablets once more knowledge of Javasccript has been acquired. 
- Multi Lingual options with flags of relevant languages to click on. The next logical step will be to make a Dutch 
version of the website. The reason English was decided on first was due to the culture of the business. Most of the 
clients are expats or tourists, and the business is ran using the English language. However, with ambitions to expand
into the community- I would like to make a Dutch version of all the content available. I will be working on this for
the next release. Other languages will also be considered at later stages.
- A "Bakery Store" where users can pre-order cakes for collection. There will be a 24 hour period before the cakes can
be picked up, and the owner is working on content and descriptions for this. This will come into force at a much later 
stage.
- A "Work For Us" area where users can apply for a job with their CV's.
- A "Staff Portal" where rotas, holiday requests, personnel details, and edits to the site can be made from.

Other Ideas may be added to this area at a later stage in conjunction with the business and user needs.  

**RELEASE NOTE:** *All of these releases will be made when more time is available and more software languages have been learnt to enact 
them.*


Deployment 
==== 

### **GitHub Pages**

 I deployed the project to GitHub Pages directly from my repository setting. 
 You can deploy for yourself following these steps:
 1. Log into your [GitHub Account](http://github.com/) and locate the [Dragons Delight Repository](https://github.com/jakelashbrook/dragonsdelight)
 2. At the top of your repository, you should see a navigation explicitly for your repository
 starting with Code and ending with Settings. Click on the "Settings" button on this menu.
 3. Scroll down the "Settings Page" until you reach the "GitHub Pages" section. 
 4. Then, Click on the "Source" button. 
 5. In the Dropdown, hit the "None" option and finally select the "Master Branch".
 6. After this confirmation the page will refresh and take you back to the top of the "Settings" page.
 7. Simply scroll back down to "GitHub Pages" section and you will locate [link](https://jakelashbrook.github.io/dragonsdelight/.) for the published site.

*You can find out more about GitHub Pages [here](https://pages.github.com/).*

 ### **Forking the repository**

 You can fork the repository to make a copy of the original repository where you can make edits or changes to 
 the files without affecting the original repository version. If you would like to fork the repository, follow
 these instructions:
 1. Log into [GitHub](http://github.com/) and locate the [Dragons Delight Repository](https://github.com/jakelashbrook/dragonsdelight).
 2. At the top of the repository (using the repository navigation bar, not the site navigation) just above the
 "Settings" button you can locate the "Fork" Button.
 3. Press the "Fork" Button.
 4. You should now have a copy of the [Dragons Delight Repository](https://github.com/jakelashbrook/dragonsdelight) in your GitHub Accounts Repository area.

*You can find out more about forking a repository [here](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/fork-a-repo).*

 ### **Making a Local clone** 

 1. Log into [GitHub](http://github.com/) and locate the [Dragons Delight Repository](https://github.com/jakelashbrook/dragonsdelight).
 2. Check under the repository name for the "Clone or Download" button.
 3. To clone the repository using HTTPS, underneath "Clone with HTTPS", copy the link.
 4. Open GitBash and change the current working directory to the location where you want the cloned version
    of the directory to be installed.
 5. Type `git clone` and then paste the HTTPS code you copied ealier.  

    For example:  

    `$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY`
 6. Press Enter and your local clone should be created.  

*You can find more supportive information on the process of cloning a repository [here](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository).*

Credits  
==== 

### **Code**
 - [Bootstrap 4.0.0](https://getbootstrap.com/docs/4.3/components/navbar/) Framework used throughout the website
 for responsive components and the grid system.
- [Google Map Generator](https://www.embedgooglemap.net/) was used for the map iFrame in the Find Us section. The code has been edited slightly via 
 CSS and certain HTML parts removed to optimize its style within the page.
 - [W3.css Display Container](https://www.w3schools.com/w3css/w3css_images.asp) was used to display the Order CTA 
 overlaying the cover image.

### **Content**
 - All of the content was developed by Jake Ashley Lashbrook. Business operation times and menu items were provided
   by Dragons Delight, Tolstraat 200, Amsterdam, 1074 VN, NL.
### **Media**
 - All Images used on the site are owned by Dragons Delight and taken from their [Facebook Page]("https://www.facebook.com/DragonsDelightAmsterdam")
   with consent to be exclusively used by Jake Ashley Lashbrook in developing their future website.
### **Acknowledgements** 
 - Antonio Rodriguez , my Code Institute Mentor for supporting me through my learning within the Development industry
   and Code Institute platform. 
 - The Code Institute Team, for teaching me skills that enabled me to push my knowledge capacity further day after day and 
   introducing me to working with Bootstrap as a framework.
 - Dragons Delight Cafe in Amsterdam for helping me to decide on changing career path and trusting me to develop my first
   website for them.
