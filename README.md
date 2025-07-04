# milestone-project-1-galactic-quest (https://garyweeks.github.io/milestone-project-1-galactic-quest/)

## Name of the project: Galactic Quest

Galactic Quest is a ficticious videogame centred around action and role playing game mechanics. I got the idea from the many videogames I have worked with and how Indie game studios set up their websites, usually though Wix.

Usually, on the first deployment a games studio will want to see a user sign up for a newsletter in order to capture their name and address to keep a user up to date with what is going on during the development and to build hype around the game. Communities will also start to be built at this stage. Early screenshots and media will be shown to help the user understand the look of the game better.

### UX

At the beginning I wanted the website to have a look and feel of a traditional indie videogame website that seperates each section in a visually pleasing manner with a layout that will be familiar to the users visiting the website. I designed the color around a carousel image that helped provide continuity throughout the website.

### Color scheme

Initially, I looked a hero image that would have impact on the homepage and got AI to generate 3 ficticious images for the game. I used one of the images to generate a primary colour, a seconday colour and one used for shadows, as well as a shade of black using https://imagecolorpicker.com.

Hex codes for colors:
Primary color: #e8cdea
Header text color: #252525
Secondary color: #948395
Body text color: #3a3a3a
Shadow color: #3f3840

![screenshot of primary color from color picker website](/documentation/primary-color.png)

I wanted to make sure the black I was using for the body has enough contrast with the primary color and ran the colors through webaim contrast checker to make sure it passed the test.

![image of primary color passing contrast test against the off black font color.](/documentation/contrast-checker.png)

### Typography

I wanted to go with a heading font that typifies the space genre of game, as well as have a slight retro feel as a nod to the  
older games like Frontier and Mass Effect that really moved the genre forward many years ago. Using an initial Google search to give me ideas I settled on PT Mono and a body text font of Manrope to compliment it.

https://fonts.google.com/?query=pt+mono Used for the headers
https://fonts.google.com/?query=manrope Used for the body
https://fontawesome.com Used for the collapsable burger in the navbar and contact us social icons in the footer

### Existing features

Currently, the website features a carousel with 3 images to create an initial impact

![screenshot of homepage showing the carousel](/documentation/server1.png)

A features section below the carousel was also created to give users of the website an idea of what's included in the game.

![screenshot of feature cards explaining what's involved in the game](/documentation/server2.png)

A gallery was also created and added a trailer (using Google Veo to generate the trailer clips and edited with Movavi) to create impact on the gallery page. The trailer has been muted as per best practice.

![screenshot of trailer at the top of the gallery](/documentation/server4.png)
![screenshot of gallery images on gallery page](/documentation/server5.png)

A registration page and form for a newsletter has also been included.

![screenshot of registration page](/documentation/server7.png)

### Future features

- Replace carousel with hero image and have a scrolling carousel of screenshots underneath
- For a game's release have buttons for each platform supported by the game and direct links to purchase
- Enbedded social networks into the site
- Blog posts from the development team to highlight development goals of the game

### Testing

Testing was initially done to check the speed of the website and pages using the Lighthouse tool in Google's dev tools. The website achieved a highscore across desktop tests and performance speeds were low for mobile testing.

![screenshot of test screen from lighthouse](/documentation/lighthouse1.png)
![screenshot of test screen from Lighthouse](/documentation/lighthouse2.png)
![screenshot of test screen from lighthouse](/documentation/lighthouse3.png)
![screenshot of test screen from lighthouse](/documentation/lighthouse4.png)

The website was also tested on the most popular browsers (Chrome, Mozilla and Edge) and all appeared the same with no failed results.

![screenshot of test on Chrome browser](/documentation/chrome1.png)
![screenshot of test on Chrome browser](/documentation/chrome4.png)
![screenshot of test on Edge browser](/documentation/edge1.png)
![screenshot of test on Edge browser](/documentation/edge4.png)
![screenshot of test on Firefox browser](/documentation/lighthouse1.png)
![screenshot of test on firefox browser](/documentation/firefox4.png)

- Tested navlinks on homepage to make sure they link correctly to each page
- Scrolled up and down through the homepage to make sure of a smooth experience
- Clicked on button to make sure it links to the correct page
- Clicked on each footer icon to make sure each social network opens on a different tab and links to the correct network
- Used dev tools to test the homepage at each break point to make sure the website maintains its integrity in the graphical elements
- Checked to make sure the carousel on the homepage was autoplaying the correct images and the transition was smooth
- Checked to make sure the embedded video was autoplaying and muted on the gallery page
- Checked the navbar links on the gallery page linked to correct pages
- Checked footer icons opened in new tab and linked correctly to each social network on the gallery page
- Scrolled up and down the gallery page to make sure of a smooth transition experience
- Used dev tools on gallery page to make sure the embedded video and gallery images were responsive on all screen sizes and maintain a continuity that's visually pleasing.
- checked the registration form to make sure all required fields give a message if something is not added (name, email)
- checked registration form to make sure that if all fields are input correctly the submit button links to a thank you page.
- checked that thank you message on thank you page has a return home button shown
- checked that the return button on the thank you page links back to index.html

HTML and CSS validation checks were done using w3c validator and no issues were found

![screenshot of html validation](/documentation/validation.JPG)
![screenshot of html validation](/documentation/validation1.JPG)
![screenshot of html validation](/documentation/validation2.JPG)

### Known issues

- Currently, the favicons are not working through normal browsers but are on VS server
- margin left issue on Gallery and Index pages
- button primary color not correct on homepage button
- Background images not scaling correctly for the registration and thank you pages.

### Credits

- Code Institute: Love running module - Navbar and Footer workflow
- Bootstrap: Grid and Base cards
- fontawesome: burger and social media icons
- Google Fonts: Header and body fonts
- Google Gemini and Veo: Image and Video Clip creation
- W3schools.com: HTML and CSS code reference materials
- Movavi: Video editing software
- Youtube: Codinglab for form design workflow
- Youtube: Learn Web: Css card design ideas
