![alt text](https://github.com/cambboyle/PortfolioProject-1/blob/main/assets/images/readme%20images/AmIResponsive.png "AmIResponsive Image")



<!-- omit in toc -->
Cameron's Portfolio
======

- [OVERVIEW](#overview)
- [UX](#ux)
- [FEATURES](#features)
- [TECH](#tech)
- [PROJECT VISUALS](#project-visuals)
    - [Wireframes](#wireframes)
    - [Completed Project](#completed-project)
- [DEPLOYMENT](#deployment-and-testing)
- [CREDITS](#credits)

## OVERVIEW

*https://cambboyle.github.io/PortfolioProject-1/*

This is a website aimed at creating an online portfolio for myself, showcasing some of my skills and technical abilities.

Built using **HTML** and **CSS**.

## UX

----

#### Project Goals

My main goal for this project was to create a intuitive and responsive portfolio that I can use for my career after the project has been submitted. 

My target audience for this project is potential clients/employers.

#### User Goals

- Easy site navigation with large buttons, easy-to-read colours and fonts.
- Learn a bit about me and my skills and interests.
- Locate completed projects.
- Be able to contact me directly from the site by email or by using the buttons/links in the footer to my social media accounts.

#### Developer Goals

- Thought out UX/UI design to ensure that every page is navigable from every page, ensuring the user doesn't get lost or ever have  to press the back button.
- A professional portfolio built only using HTML, CSS and Bootstrap5.
- A project where I can keep updating it and expanding on it as my career progresses.

## Design Choices

The overall design of the website was made to 1. Be easy to navigate for employers/clients and 2. be attractive to any person who views my portfolio.

#### Fonts

- The font I chose to use for my portfolio was Montserrat from google fonts. I love this font because depending on the font weight, it can look like a completely different font, making it versatile to use across the site.

#### Icons

- The icons I used were chosen simply for their purpose i.e. LinkedIn logo was used for the button linked to my LinkedIn.

#### Colouring

- The darker tone of the site was used so that the information I was putting on my site stood out more and is easier for viewers to read. I believe this tone also makes the site look a bit more professional.

- The brighter colours were used for the content of the site, as I said above, to stand out against the darker background. The colours between site pages have no meaning behind them as such. They are just nice bold colours to distinguish the pages the on the site.

#### Style

- I used the same rounded box to contain all of the content on each page, this was used throughout my site to provide consistency when people are viewing the website.

#### Images

- The main images used on the site are of myself, I used these particular images because they are formal, professional-looking images. I opted to use a photo of myself for the main background to the website as I think it will build a connection and formality with a potential employer/client before they have spoken to me.

- The placeholder images I used for the Projects page are not my own, they are royalty free images and credited in the credits section of this README. When I actually have projects of my own, I will use thumbnails of those projects instead.

## FEATURES

- Easily navigable
- Expandable Projects Page - Very simple to create more project boxes for when I need to.
- Email Contact Form.
- Social Links in the footer of every page.
- In depth About Me page with sections on my interests, skills and other info.
- On-site Resume noting my relevant information, education and past work experience (also easy to update the more my career grows).

## TECH

- HTML
- CSS
- Github
- Miro
- VS Code
- CodeAnywhere
- Bootstrap 5
- MDBootstrap

## PROJECT VISUALS

----

### Wireframes

These Wireframes were created using the Miro App, I opted to use this over Balsamiq as I have experience using Miro.

Home Page

![alt text](https://github.com/cambboyle/PortfolioProject-1/blob/main/assets/images/readme%20images/HomePage.png "Home Page Wireframe")

About Me Page

![alt text](https://github.com/cambboyle/PortfolioProject-1/blob/main/assets/images/readme%20images/About%20Me.png "About Me Wireframe")

Resume Page

![alt text](https://github.com/cambboyle/PortfolioProject-1/blob/main/assets/images/readme%20images/Resume%20Page.png "Resume Page Wireframe")

Projects Page

![alt text](https://github.com/cambboyle/PortfolioProject-1/blob/main/assets/images/readme%20images/Projects.png "Projects Page Wireframe")

Contact Page

![alt text](https://github.com/cambboyle/PortfolioProject-1/blob/main/assets/images/readme%20images/Contact%20Page.png "Contact Page Wireframe")

### Completed Project

Home Page

![alt text](https://github.com/cambboyle/PortfolioProject-1/blob/main/assets/images/readme%20images/HomePageFinal.png "Home Page Visual")

About Me Page

![alt text](https://github.com/cambboyle/PortfolioProject-1/blob/main/assets/images/readme%20images/AboutMeFinal.png "About Me Visual")

Resume Page

![alt text](https://github.com/cambboyle/PortfolioProject-1/blob/main/assets/images/readme%20images/ResumeFinal.png "Resume Page Visual")

Projects Page

![alt text](https://github.com/cambboyle/PortfolioProject-1/blob/main/assets/images/readme%20images/ProjectsFinal.jpg "Projects Page")

Contact Page

![alt text](https://github.com/cambboyle/PortfolioProject-1/blob/main/assets/images/readme%20images/ContactFinal.png "Contact Page Visual")

Project 1 Page

![alt text](https://github.com/cambboyle/PortfolioProject-1/blob/main/assets/images/readme%20images/Project1Final.png "Project 1 Page Visual")

## DEPLOYMENT AND TESTING

----

### Testing

----

#### Test 1 - Navigate and cycle through site pages.

- Expected:
    Open site, click link in navbar to other pages, create a full loop of navigating from landing page -> about me -> projects -> contact.

- Test:
    Followed steps as above.

- Result:
    The site acted as expected, no breaks and was able to follow path specified and more.

#### Test 2 - Successful contact form.

- Expected: Fill out contact form which sends email.

- Test:
    Filled out form and clicked send.

- Result:
  Page gets refreshed and no email sent.

- Fix:
    A fix for this would be to add a "mailto:" to the form or set up PHP, my issue with mailto is that it breaks the UX by opening up the viewers default email application. This in my opinion is bad UX design as it takes focus away from the site. I also am yet to learn PHP but when I do learn, I will be adding it to the site to make a fully functional form.
  EDIT: Added the CodeInstitute default formdump to my contact form, this is something I forgot about until going back through the form lessons on the course to see if there was anything I could do.

### BUGS

----

#### Solved Bugs

Kept having issue with row in main content of Resume, Contact and About Me pages. Fixed bug by adding Margin: Auto to the effected columns.

Ran into a bug/error during my deployment phase, where I had added a "/" infront of image urls, github pages ignores them. I had to run through all code for images and links that included these and remvoed them.

Contact Form would refresh page and not send email. I fixed this by adding `action=""` and `method=""` to the forms html and setting the action as the default CodeInstitute FormDump.


### Deployment

----

*write here the process of deploying the site w/ any differences between development code and deployed code.*

This project was developed using CodeAnywhere and VSCode, I switched to VSCode midway because I was consistently getting issues with CodeAnywhere and struggling with load times. Then the project was commited to git and pushed to GitHub.

I deployed the page to GitHub pages from my repository. These were the steps taken to do so:

1. Logged into GitHub.
2. Selected **cambboyle/PortfolioProject-1** from the list of repositories.
3. Clicked on the repo's settings.
4. Scrolled down and selected the GitHub Pages tab.
5. In the source dropdown, keep it as "Deploy from a branch", then select "Master" from the branch dropdown.
6. Click Save, this should now start the build process for the site.

The development branch and Master branch are completely identical.

#### How to run this project locally in VSCode

1. Follow this link to the [GitHub Repository](https://github.com/cambboyle/PortfolioProject-1).
2. Click the green <> Code dropdown.
3. Copy the HTTPS URL for the repository.
4. In VSCode, open up the terminal.
5. Change the directory to where you want the cloned directory to be stored.
6. Type `git clone`, then the paste in the URL from the repo.
7. Press enter in the terminal and the clone should be made.

### Validation

#### HTML

![alt text](https://github.com/cambboyle/PortfolioProject-1/blob/main/assets/images/readme%20images/HTMLValidation.png "HTML Validation")

#### CSS

*Only errors shown are either bootstrap css or "vendor extension related"*
![alt text](https://github.com/cambboyle/PortfolioProject-1/blob/main/assets/images/readme%20images/CSSValidation.png "CSS Validation")

#### Lighthouse

Desktop Result

![alt text](https://github.com/cambboyle/PortfolioProject-1/blob/main/assets/images/readme%20images/LighthouseResultsDesktop.png "Lighthouse Desktop Results")

Mobile Result

![alt text](https://github.com/cambboyle/PortfolioProject-1/blob/main/assets/images/readme%20images/LighthouseResultsMobile.png "Lighthouse Mobile Results")

## CREDITS

----


icons - <https://fontawesome.com>

extra notes and methods - <https://www.w3schools.com>

bootstrap notes and media queries - <https://getbootstrap.com>

material design for bootstrap - <https://mdbootstrap.com>

colour matching/palette design - <https://www.realtimecolors.com>

Portfolio Images (royalty free) - <https://unsplash.com/s/photos/portfolio>

Grayscale Images Filter CSS - <https://www.tutorialspoint.com/how-to-create-a-black-and-white-image-using-css#:~:text=By%20specifying%20grayscale%20value%20to,%2C%20drop-shadow%20to%20images.>

Email Send Form help <https://mailtrap.io/blog/html-form-send-email/>

### Validation Credits

AmIResponsive - <https://ui.dev/amiresponsive?url=https%3A%2F%2Fbytes.dev>

HTML Validator - <https://validator.w3.org>

CSS Validator - <https://jigsaw.w3.org/css-validator/>

