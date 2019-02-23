# The Monkees #
## Frontend Webdevelopment Project ##


## Aim ##

The aim of this project was to create and build a front-end only website that has 4-5 pages for the rock band [The Monkees](https://anthonynicklin.github.io/milestone01-TheMonkees/). 
I was provided with material such as audio and a video clip which they wanted fans to be able to play on their website. Other assests they provided where photos of 
the band, album covers and indivual band member photos. 

## UX ##

Starting with a mobile first desgin approach to this project I started creating wireframes for mobile and small screens. I then moved onto creating mockups 
for medium and desktop/larger screens. The main desgin of the site is clean, simple but also funky. I kept to a simple color scheme in keeping with the main 
background image that I choose to use. Having a clean cut desgin, I felt makes it easier for the fan to read and use the website.
The navigation bar is responsive having break points for smaller and medium size screens. At these breaks points a burgar menu appears top right, and when 
clicked brings a drop down menu with the navigation links. The 'Home' link is displayed in the navigation bar when the drop down menu is collapsed in order 
bring the fan back to the home page with just one click without having to toggle the drop down menu. The layout of the media.html and meet-the-band.html have been 
kept simular in order to give the website consistency. 

Below are user stories that were conducted in order to gain clear goals that needed to be achieved for this website.
1. As a fan I wanted to listen to current and back catalogue tracks.
2. As a fan I wanted to see where and when the band will be preforming.
2. As a fan I wanted to be able to find and book tickets to the bands next gigs.
3. As a fan I wanted to read intresting facts about the band and about each artist.
4. As an event promoter I wanted to hear and preview their tracks.
5. As an event promoter I wanted to see a promotional video of the band.
6. As an event promoter I wanted a way in which I could contact the band for bookings.
7. As an fan I wanted to be able to contact the band to book for my own event.
8. As an event promoter I wanted to check out their soical media via links.
9. As a fan I wanted links to their differnt soical media pages on different platforms.

## Features ##

Features on this website are:

* On every desktop/large screen the logo of the band is presented and there is also a link to the home page.
* The links in the navigation when hovered over turn black with an underline to indicate which link the fans cursor is over.
* When hovering over any links the cursor changes from a pointer to a hand.
* On every page in the footer there are links to the band's soical media pages to the respected soical media platforms.
* For each [live date](https://anthonynicklin.github.io/milestone01-TheMonkees/#live-dates) there is a 'find ticket' button that takes them the respected page on ticketmaster.com.
* The [booking form](https://anthonynicklin.github.io/milestone01-TheMonkees/#book-us) lets the fan input their information and a modal is dispalyed thanking them for their intrested when submitted.
* Video and audio on the [media](https://anthonynicklin.github.io/milestone01-TheMonkees/media.html) page have contorls that the fan can use to fully control the video and audio.

## Technologies Used ##

Below are list of the programming lanuagues, technologies and frameworks used for this website.

* HTML5
* CSS3
* Markdown
    * Used to write the README.md file.
* JavaScript
    * Used to create the responsive navigation bar.
* [Bootstrap3.3.7 framework](https://getbootstrap.com/)
    * The website uses boostrap framework for it's grid system, pagelayout, button styling, navigation bar and modal.
* [Cloud9IDE](https://aws.amazon.com/cloud9/)
    * Cloud9 was the IDE used to write the code for this website.
* [MarvelApp](https://marvelapp.com)
    * This was used to desgin and create the mockups for this project.
* [Google Fonts](https://fonts.google.com/)
* GIT
* [GITHUB](https://github.com)
* [Font Awesome](https://fontawesome.com/)
    * For soical media icons and Glyphicons
* Google Chrome Developer Tools
* Firefox Inspector
* Safari

## Testing ##

I conducted testing across different platforms and web browsers in order to make sure the website works correctly and
looks great across each one. I also asked friends and familys to test cross their own devices to give option and advise. 

Platforms:
* Samsung Galaxy 8
    * Google Chrome
    * Firefox
    * Samsung web browser
* iPad Mini
    * Google Ghrome
    * Firefox
    * Safari
* MacBook Pro
    * Google Chrome
    * Firefox
    * Safari
* Ubuntu 18.0
    * Google Chrome
    * Firefox
* Windows 10
    * Google Chrome
    * Firefox
    * Mircosoft Edge
    * IE 11

Manual testing was conducted to ensure the user story objectives where achieved
1. Audio
    i. Click on "Media" page
    ii. Click on audio control bar to hear and contorl music
2. Book tickets
    i. Scroll down and use navigation link to "Live Dates" section
    ii. Click on "Find Ticket" in order to book ticket for that event
3. View promotional footage
    i. Click on "Media" page
    ii. Click on video contorl bar to view and contorl footage
4. Book the band
    i. Scroll down and use navigation link to "Book Us" section
    ii. Try to submit the empty form and verify that an error message about the required fields appears
    iii.Try to submit the form with an invalid email address and verify that a relevant error message appears
    iv. Try to submit the form with an invalid telephone number and verify that a relevant error message appears
    iiv. Try to submit the form with all inputs valid and verify that a success message appears
5. Social Media links
    i. In the footer of each page click on each soical media icon to be redirected to the respected site

I reached out to fellow students on Slack to view my website and test. A lead mentor writely pointed out a major problem with the responsive
aspect of the website. Even tho the website looks correct on small devices when adjusting a web browser on a desktop below 400px there was huge
overflow. This pointed out I had not applied the mobile first approach correclty. I research more mobile first and went back over notes and videos.
To correct the fault I had to rewrite 60% of my style.css. 


## Depolyment ##

The website was created using Cloud9 IDE using Ubuntu with BASH. Git was used for version control and pushed to a repository hosted on 
GitHub.com. 

The website is delopyed using GitHub pages [The Monkees](https://anthonynicklin.github.io/milestone01-TheMonkees/)

## Credits ##

### Content ###
Information about the band was taked from a number of sources listed below:
* [Wikipedia](https://en.wikipedia.org/wiki/The_Monkees)
* [The Monkees](https://www.monkees.com/)
* [Biography - The Monkees](https://www.biography.com/people/groups/the-monkees)

Please notes some content is make up as I did not want to write the same information that would come most other students would also be writing.

### Images ###
Main background image uses was sourced under free commercia license [Pixaby](https://pixabay.com/en/red-abstract-spiral-2829985/)
Images of band, Monkees logo and artists where provided by Code Institude.

### Media ###
Audio and video was provided by Code Institude.

### Code ###
#### Collapsible responsive navigation bar ####
Code copied and customised from [w3schools.com](https://www.w3schools.com/howto/howto_js_topnav_responsive.asp)
