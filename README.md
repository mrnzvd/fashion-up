
# Fashion Up

Fashion Up is a real brand developed by my friend, the designer Taísa Souza. My purpose with this project is to create an institutional website for her where she can introduce her brand and also have a space for customers to book alterations.

![Website view](https://beyondthesight.net/Mariana/Fashion/Images/read/landingpage.png)

# Table of contents
- [UX](#ux)
    - [Site Purpose](#site-purpose)
    - [Site Goal](#site-goal)
    - [Audience](#audience)
    - [Current users](#current-users)
    - [New Users](#new-users)
- [Design](#design)
    - [Colour Scheme](#colour-scheme)
    - [Typography](#typography)
    - [Imagery](#imagery)
- [Features](#features)
    - [Navigation Bar](#navigation-bar)
    - [Landing Page](#landing-page)
    - [The Brand](#the-brand)
    - [The Designer](#the-designer)
    - [Alterations](#alterations)
    - [Projects](#projects)
    - [Contact and Thank you page](#contact-thankyou)
    - [Footer](#footer)
    - [Scroll to top button](#scroll-to-top)
    - [Future Features:](#future-features)
- [Testing](#testing)
    - [Validator Testing](#validator-testing)
- [Libraries and Programs used](#libraries-and-programs-used)
- [Deployment \& Usage](#deployment--usage)
    - [Deployment](#deployment)
    - [How to Fork](#how-to-fork)
    - [How to Clone](#how-to-clone)
- [Credits](#credits)
  - [Content](#content)
  - [Media](#media)
  - [Acknowledgements](#acknowledgements)
    

# UX
### Site Purpose
The purpose of this site is to introduce Fashion Up as a brand sharing information about the brand itself and the designer.

### Site Goal
The site's goal is to provide in-depth information about the brand, the designer and upcoming projects to create an engaging communit. Also, customers will be able to easily book alterations and contact the designer.

### Audience
Anybody that is interested in upcycling fashion. The primary target audience is female 16-55.

### Current Users
- People that already utilize Taísa's alterations services.

### New Users
- Will learn about the brand. 
- Will be able to book alterations. 

# Design
### Colour Scheme
The colour scheme was created on [coolors](https://coolors.co/) by Taísa, the designer, and shared with me. The reasoning behing the colour scheme is to have clean neutral colours with pops os pink, her favourite colour. 
![Colour Pallette](https://beyondthesight.net/Mariana/Fashion/Images/read/color.png)

### Typography
The typography was chosen by Taísa, the designer, and downloaded from [CDN fonts](https://www.cdnfonts.com/category/handwritten). The aim is to have the contrast from a handwritten font for titles to a more mechanical font for paragraphs.

### Imagery
The banner image was created by me on [Canva](https://www.canva.com/). The other images were produced by Taísa, the designer, who shared with me with the purpose to add it on the website.

# Features
### Languages  used
- HTML 
- CSS
- Javascript

### Navigation Bar
The navigation bar contains all five sections. This is a single page website and each item directs to its section. 

![navigation bar](https://beyondthesight.net/Mariana/Fashion/Images/read/navigation.png)

### Landing Page
![landing page](https://beyondthesight.net/Mariana/Fashion/Images/read/landingpage.png)

The landing page, displayed above, shows the store's main statement, the navigation bar and the banner image not appearing on its entirety. The reason why the banner image is not appearing fully is to entice visitors to see the rest of the page's information, which they can do by scrolling down or clicking on the menu.

### The Brand
![the brand](https://beyondthesight.net/Mariana/Fashion/Images/read/thebrandsection.png)
This section is directly below the landing page, and shares information about the brand and their mission. 

### The Designer
![the designer](https://beyondthesight.net/Mariana/Fashion/Images/read/thedesignersection.png)
As in fashion the designer is the face of the brand, this section's aim is to introduce the designer's point of view about fashion and a bit of their history.

### Alterations 
![alterations](https://beyondthesight.net/Mariana/Fashion/Images/read/alterationssection.png)
The main service offered at this moment is clothing alterations, so this section is there to facilitate booking using [Calendly](https://calendly.com/). 

### Projects
![projects](https://beyondthesight.net/Mariana/Fashion/Images/read/projectsection.png)

The brand's main focus is to be as sustainable and eco-friendly as possible and in this section updates about projects targetting this theme will be shown.

### Contact and Thank you page
![contact](https://beyondthesight.net/Mariana/Fashion/Images/read/contactsection.png)
A contact form was added at the end of the page so users can send their messages. After submission, the user will be redirected to a thank you page as seen below.

### Footer
![footer](https://beyondthesight.net/Mariana/Fashion/Images/read/footer.png)

Social media links were added to the footer.

### Scroll to top button
![scroll](https://beyondthesight.net/Mariana/Fashion/Images/read/scrollbutton.png)

As this is a one page website a scroll to top button, using Javascript, was added to make the navigation easier.

### Future Features:
- Videos showing clothing creation process.
- Videos and updates from projects that took place.
- When the brand is ready to launch and they start selling clothes, an ecommerce feature will be added. 

# Testing
First HTML testing through W3 validator returned syntax errors with extra slashes added to the end of images which was related to the HTML version, which were fixed. Also returned errors related to Calendly iframe. The code in the iframe wasn't changed as it affected the calendar that is needed to book alterations. 

No errors returned in the first CSS W3 validation.

### Validator Testing

Passed through validator landing page and thank you page. No errors in HTML for the thank you page. The errors on landing page are from Calendly iframe which is important to keep so it wasn't removed.

![landingpage](https://beyondthesight.net/Mariana/Fashion/Images/read/htmlvalidation.png)
![thankyoupage](https://beyondthesight.net/Mariana/Fashion/Images/read/thankyoupagevalidationhtml.png)

No errors reported on CSS validation for both pages.

![landingpagecss](https://beyondthesight.net/Mariana/Fashion/Images/read/cssvalidation.png)
![thankyoupagecss](https://beyondthesight.net/Mariana/Fashion/Images/read/thankyoucss.png)

Tested website using lighthouse. Although for a one page website the score is not as low. Future alterations can improve rating. 

![lighthouse](https://beyondthesight.net/Mariana/Fashion/Images/read/lighthousecheck.png)

# Libraries and Programs used
- Github: Store Repository
- Gitpod: Creation of HTML, CSS. Javascript and ReadMe
- CDN Fonts: Font family 'Sans Serife' and 'Meringue'
- Canva: Creation of banner image
- Google Chrome Dev Tools: Styling media queries and testing with lighthouse.
- Ionos: Image storage
- W3: Code validation

# Deployment & Usage


### Deployment
1. In the GitHub repositories, navigate your way to the settings tab
2. From there on your left hand side find the 'Pages' tab, click on it.
3. In the build and deployment section, select 'source' and then 'deploy from a branch'
4. Then underneath that select 'main' and 'root'
5. Click save
6. Your page should refresh automatically or manually with a link to your deployed website.
7. The link can be found here: <https://mrnzvd.github.io/fashion-up>


### How to Fork
- Log in (or sign up) to [Github](https://github.com/).
- Go to respository for this project [Fashion Up](https://github.com/mrnzvd/fashion-up).
- Click the fork button in the top right corner.


### How to Clone
- Log in (or sign up) to [Github](https://github.com/).
- Go to respository for this project [Fashion Up](https://github.com/mrnzvd/fashion-up).
- Click on the code button, select whether you would like to clone with HTTPS, SSH, GitHub CLI and copy the link shown.
- Open the terminal in your code editor and change the current working directory to the location you want to use for the clone directory.
- Type 'git clone' into terminal and then paste the link you copied in step 3.
- Press enter.

# Credits

### Content

- HTML, CSS and Javascript code were created following [Code Institute course](https://codeinstitute.net).
- [W3 schools](https://www.w3schools.com) was used for code inspiration.
- ReadMe inspiration: [Potters Club](https://github.com/SaskiaPacker/potters-club), [Ghost Cod Team](https://github.com/alakeldev/ghost-cod-team-website-pp1) and [Nacka Tomato Society](https://github.com/Pelikantapeten/p1-nacka-tomato-society).
- Favicon was added following [W3 Guide](https://www.w3schools.com/html/html_favicon.asp).
- 404 page created by [Github guide](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-custom-404-page-for-your-github-pages-site). 
- [Calendly](https://calendly.com/) iframe was added following their guidelines.


### Media

- Pictures from Taísa Souza were taken and shared by her.

### Acknowledgements

- I want to say a big thank you to my mentor Martina for sharing her wisdom and to my friend Taísa for letting me use her brand to create this project.