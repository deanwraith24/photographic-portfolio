# Chasing Light Photographic Portfolio

[Link to live project](https://deanwraith24.github.io/photographic-portfolio/)

Chasing Light Photographic Portfolio is a portfolio site for my personal wildlife photography that I have taken in my time working in wildlife conservation in South Africa. The goal was to showcase my images in an easy to access and view style. The site consists of 4 pages that help to reach this goal.

![Image of responsive site](https://github.com/deanwraith24/photographic-portfolio/blob/main/assets/img/Responsiveness%20image.png)

### <u>Table of Contents</u>

* [Planning](#planning)
  * [External User Goals](#external-user-goals)
  * [Site Owner Goals](#site-owner-goals)
  * [User Stories](#user-stories)
  * [Wireframes](#wireframes)
  * [Fonts, Colors and Images](#fonts-colors-and-images)

* [Features](#features)
  * [Header](#header)
  * [Footer](#footer)
  * [Home Page](#home-page)
  * [About Page](#about-page)
  * [Portfolio Page](#portfolio-page)
  * [Contact Page](#contact-page)

* [Future Enhancements](#future-enhancements)

* [Testing](#testing)
  * [Manual Testing](#manual-testing)
  * [Validation](#validation)
  * [Issues](#issues)

* [Deployement](#deployement)

* [Credits](#credits)

### <u>Planning</u>

#### <u>External User Goals</u>
The goals for users of this site are to see a collection of photographs taken over a period of time working in wildlife conservation on various reserves around South Africa.

#### <u>Site Owner Goals</u>
The goals of the site owner are to showcase a range of images of various wildlife and wildlife experiences.

#### <u>User Stories</u>
Below is a table of the User Stories for the site with acceptance criteria and tasks to achieve the criteria,

|User Story|Acceptance Criteria|Tasks|
|:---------|:------------------|:----|
|As a potential client, I can view a gallery<br> of wildlife photographs so that I can assess<br> the photographer's style and quality of work.|- Gallery displays multiple wildlife photographs in a grid layout<br>- Images load correctly and are responsive<br>- Each image has appropriate alt text for accessibility|- Create portfolio grid layout<br>- Implement responsive image sizing<br>- Add alt text to images<br>- Optimize images for web|
|As a visitor, I can read about the photographer's <br>background and achievements so that I can understand<br> their experience and credibility.|- About page displays photographer's biography<br>- Awards and achievements are clearly listed<br>- Page includes relevant images|- Create biography section<br>- Implement awards section<br>- Add supporting images<br>- Ensure responsive layout|
|As an interested client, I can submit a contact<br> form so that I can inquire about services<br> or collaboration opportunities.|- Form includes fields for name, email, country, and message<br>- All required fields are marked<br>- Form validates input before submission|- Build form structure<br>- Implement validation<br>- Style form elements<br>- Add form functionality|
|As a mobile user, I can access the website navigation menu<br> so that I can browse different pages on my smartphone.|- Navigation menu collapses into hamburger menu on mobile devices<br>- Menu expands when clicked<br>- Navigation links are easily clickable on mobile|- Set up Bootstrap navbar<br>- Style mobile menu<br>- Implement responsive behaviour<br>- Optimize for touch|
|As a visitor, I can access the photographer's social media<br> profiles so that I can follow their work on different platforms.|- Social media icons are visible in the footer<br>- Icons link to correct social media platforms<br>- Links open in new tabs|- Create footer layout<br>- Implement social icons<br>- Configure links<br>- Style interactions|
|As a first-time visitor, I can view a selection of featured<br> images on the homepage so that I can<br> quickly understand the type of photography offered.|- Homepage displays featured images<br>- Images are professionally presented<br>- Clear link to full portfolio is available|- Create homepage layout<br>- Optimize featured images<br>- Style presentation<br>- Add portfolio link|

#### <u>Wireframes</u>

<u>Home Page Wireframe</u>

![Home Page Wireframe](https://github.com/deanwraith24/photographic-portfolio/blob/main/assets/img/Home%20Page%20Wireframe.png)

<u>About Page Wireframe</u>

![About Page Wireframe](https://github.com/deanwraith24/photographic-portfolio/blob/main/assets/img/About%20Page%20Wireframe.png)

<u>Portfolio Page Wireframe</u>

![Portfolio Page Wireframe](https://github.com/deanwraith24/photographic-portfolio/blob/main/assets/img/Portfolio%20Page%20wireframe.png)

<u>Contact Page Wireframe</u>

![Contact Page Wireframe](https://github.com/deanwraith24/photographic-portfolio/blob/main/assets/img/Contact%20Page%20Wireframe.png)

#### <u>Fonts, Colors and Images</u>

* Fonts
The fonts for the site were sourced from [Google Fonts](https://fonts.google.com/). The heading font used is Oswald and the body font used is Lato.

* Colors
Font colors used are #CC5500 and  #777777

* Images
All the images included in the project are my personal images.

### <u>Features</u>

#### <u>Header</u>

The site name links back to the home page. The various links in the nav bar link directly to their specific page and highlight when in use.

![Header](https://github.com/deanwraith24/photographic-portfolio/blob/main/assets/img/Header.png)

#### <u>Footer</u>

The various icons link to the specific social media pages and open in a new window.

![Footer](https://github.com/deanwraith24/photographic-portfolio/blob/main/assets/img/Footer.png)

#### <u>Home Page</u>

On the Home Page, the text directing users to the Portfolio page is clickable and links directly to the portfolio page.

![Home Page](https://github.com/deanwraith24/photographic-portfolio/blob/main/assets/img/Home%20Page%201.png)

![Home Page](https://github.com/deanwraith24/photographic-portfolio/blob/main/assets/img/Home%20Page%202.png)

#### <u>About Page</u>

![About Page](https://github.com/deanwraith24/photographic-portfolio/blob/main/assets/img/About%20Page%201.png)

![About Page](https://github.com/deanwraith24/photographic-portfolio/blob/main/assets/img/About%20Page%202.png)

#### <u>Portfolio Page</u>

![Portfolio Page](https://github.com/deanwraith24/photographic-portfolio/blob/main/assets/img/Portfolio%20Page.png)

#### <u>Contact Page</u>

![Contact Page](https://github.com/deanwraith24/photographic-portfolio/blob/main/assets/img/Contact%20Page.png)

### <u>Future Enhancements</u>

The list below is some features that could be added in the future to enhance the user experience.

* Blog
A blog can be added where stories about specific images or experiences can be shared and a sign up to receive notifications of new posts can be added.

* Market Place
A page where users can order prints and have them shipped to them.

### <u>Testing</u>

#### <u>Manual Testing</u>

|Feature|Expected|Testing|Result|
|Navbar Main Heading Link|Return to Home page when clicked|CLicked from portfolio page|Passed|
|Navbar links|Navigate user to associated pages|Checked user was directed to correct page when link clicked|Passed|
|Call to action link|Direct user to protfolio page|Clicked link to check|Passed|
|Social Media Link|Open specific social media site in new browser tab|Clicked each icon|Passed|

#### <u>Validation</u>
 * HTML
 For the HTML I used W3C Markup Validation Service.

 * CSS
 For the validation of the CSS I used Jigsaw CSS validatior.

#### <u>Issues</u>

The hero image was not scaling correctly to be responsive on smaller screens. The fix for this issue:
- Updated the #hero-section to have consistent width and other properties without the fixed max-height that was causing scaling issues
- Modified the #hero-image styling to properly scale using width: 100% and height: auto
- Added object-fit: cover to maintain the aspect ratio while filling the container
- Added display: block to remove any potential whitespace that might affect image rendering
- Kept the responsive max-height declarations in the media queries to ensure the image scales appropriately at different viewport widths

### <u>Deployement</u>

The project was deployed using GitHub Pages. The steps to deploy are as follows:

 1. Open the repository and click on the settings tab.
 2. Navigate to the Pages tab in the menu on the left.
 3. Choose deploy from a branch and select main branch.
 4. Click save and you can access the deployed website from the Pages tab.

### <u>Credits</u>

The content on the site was written by myself. The About me and Awards text is made up and non-factual or real. I used W3 Schools to trouble shoot some of the speed bumps I had and to get some ideas for the code I used in my form. I also used the course work from the Code Institute LMS.
