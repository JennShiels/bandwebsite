# User Centric Frontend Development Project
 Band Website - The Dropouts Galway

##  The following guidelines were used when developing this project:

 #1   Create a website of around 4-5 pages, or (if using a single scrolling page) these should be separate page areas.
 
 #2   Incorporate main navigation and grid layout (you might want to use Flexbox or Bootstrap to accomplish this).
 
 #3   Whenever possible, strive to use semantic HTML5 elements to structure your HTML code better.
 
 #4   Make sure your site is as responsive as possible. You can test this by checking the website on different screen sizes and browsers.
 
 #5   We advise that you write down user stories and create wireframes/mockups before embarking on full-blown development.
 
 #6   The site can also make use of CSS frameworks such as Bootstrap, just make sure you maintain a clear separation between the library code and your code.
 
 #7   You should conduct and document tests to ensure that all of your website’s functionality works well.
 
 #8   Write a README.md file for your project that explains what the project does and the need that it fulfills. It should also describe the functionality of the project, as well as the technologies used. Detail how the project was deployed and tested and if some of the work was based on other code, explain what was kept and how it was changed to fit your need. A project submitted without a README.md file will FAIL.
 
 #9   Use Git & GitHub for version control. Each new piece of functionality should be in a separate commit.
 
 #10   Deploy the final version of your code to a hosting platform such as GitHub Pages.

### Overview
 
### What is this website for?
 
This website is for a duet band. It aims to promote the band and show potential clients their work, introduce the members of the band and their contact details for future bookings
 
### What does it do?
 
This website has 4 pages that can be navigated through the menu bar. The Home page introduces the band members. 
The Music page showcases the band's previous gigs around Galway. The Events page shows images of the band in various 
places around Galway and gives information about the band and what events they cater to.
The Contacts page has a form where the user enters their information and can enter a comment that is sent to the band's email account.

### How does it work
 
This website uses **HTML5** , **CSS** and **JScript**. The site is styled with **Bootstrap**. The quiz has been created using **Javascript** and modal for enlarging images is displayed using some **JQuery** code. **Bower** has been used to manage package dependencies for deployment of site on github pages. The site can be viewed [HERE](https://futoisaru.github.io/hippo/)

## Features
 
### Existing Features
- Eye catching front page
  - Sliding picture box
- Information page.
  - Sidebar to navigate to different parts of the information
- Media page with plenty of pictures and a video
- Links page to other sites with information about Hippopotami
- Quiz page for viewers to test their knowledge
    - Form for viewers to input their answers or check the correct box
    - Submit button so viewers can see how they scored on the quiz

### Features Left to Implement
- None

## Tech Used

### Some the tech used includes:
- **HTML**, **CSS** and **Javascript**
  - Base languages used to create website
- [AngularJS](https://angularjs.org/)
    - We use **AngularJS** to handle page routing and to build custom directives
- [Bootstrap](http://getbootstrap.com/)
    - We use **Bootstrap** to give our project a simple, responsive layout
- [JQuery](https://jquery.com)
    - Use **JQuery** for boostrap and displaying modal
- [npm](https://www.npmjs.com/)
    - We use **npm** to install **http-server** in order to view the site
- [Bower](https://bower.io)
    - Using **Bower** to manage package dependencies

## Testing
- Prototype code was written and tested using jasmine
- All code used on the site has been tested to ensure everything is working as expected
- Site viewed and tested in the following browsers:
  - Google Chrome
  - Opera
  - Microsoft Edge
  - Mozilla Firefox

## Contributing
 
### Getting the code up and running
1. Firstly you will need to clone this repository by running the ```git clone <project's Github URL>``` command
2. After you've that you'll need to make sure that you have **npm** installed
  1. You can get **npm** by installing Node from [here](https://nodejs.org/en/)
4. After those dependencies have been installed you'll need to make sure that you have **http-server** installed. You can install this by running the following: ```npm install -g http-server # this also may require sudo on Mac/Linux```
5. Once **http-server** is installed run ```http-server -c-1```
6. The project will now run on [localhost](http://127.0.0.1:8080)
7. Make changes to the code and if you think it belongs in here then just submit a pull request

## Credits

### Media
- The photos used in this site were obtained from [Pixabay](https://pixabay.com/)
- The video used on this site belongs to Nat Geo Wild channel on [youtube](https://www.youtube.com/watch?v=WfrG95GyU9U)

### Information
- The information used to create this site was from a number of sources
    - Wikipedia webpage on [Hippos](https://en.wikipedia.org/wiki/Hippopotamus) and [Pygmy Hippos](https://en.wikipedia.org/wiki/Pygmy_hippopotamus)
    - The African Wildlife Foundation [website](http://www.awf.org/wildlife-conservation/hippopotamus)