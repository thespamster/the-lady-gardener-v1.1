# The-lady-gardener & how i built a website for my wife's business.

![Header](assets/img/am_i_responsive.png)

## The website 'Tracey the Gardengal', the idea, the discussion and the wireframing.

For my first milestone project I decided that what I really wanted was to design and build a website for a genuine business. Fortunately my wife , Tracey, has over the past three years built up a small gardening business through a combination of Facebook leads and word of mouth. The one thing she doesn't have is a dedicated website, something that she can point potential customers at, a shop window if you will, that will give people an understanding of her business 
ethos and just as importantly a feel for who she is as a person and a gardener.

The basic design and layout of the website was discussed over a period of 2-3 days and some basic wireframe diagrams were hand drawn by myself. These are included here for reference purposes. There was no need for dedicated software such as Balsamiq or my own preferred design software, Figma, as it was easier for us to sit together in our lounge and for me to sketch the ideas on a piece of A4 paper. It was during these initial consultations that the name of the business was finalised as Tracey really liked the fact that a lady gardener is known as either a Gardenerette or a Gardengal.

[Wireframe]()

## Website construction, testing and deployment.

In order to code the website I used a combination of VS Code and Stackblitz IDE's. The main code was written, tested and debugged in VS Code as I have found this IDE to be one of the most fully featured environments currently available. Stackblitz was used to build and test small portions of the code before moving the code over to VS Code. The reason for this is that Stackblitz has a useful 'party trick' in that the preview browser displays the code in real time meaning you can see how the code looks and behaves instantly. (nb. I have since discovered that you can now do this in VS Code by installing the 'live preview' extension from Microsoft). By adopting a reductionist approach to the code build this allowed me to debug in 'bitesize' chunks and thus reduce the risk of any major issues getting into the build as it was constructed.

The testing of the site as a whole was completed using a combination of the desktop browsers Chrome v114.0.5.5735.198, Firefox v114.0.2 and Edge v114.0.1823.67 on my Win 11 Pro desktop PC, mobile Safari on my Wife's iPhone 11 and mobile Chrome on my Android Nothing Phone(1). I also made extensive use of the devtools built into Chrome desktop browser.

To give the site great responsive behaviour across phone, tablet, laptop and desktop screens I took the decision to use the CSS library Bootstrap as there seemed little point in 'reinventing the wheel' and building this from scratch. Three appropriate fonts, Caveat, Delius and Roboto were imported from Google Fonts and the Facebook and Instagram icons were imported from Font Awesome V4.7. The colour scheme was picked using Adobe Colour Wheel and based around the main colour purple, my wife's favourite colour. All the images used are genuine photos shot on my wife's iPhone 11 or my Nothing Phone(1) as my wife felt that photos from her workplaces would give the site a more authentic feel.

Deployemnt of the site is via Github pages with a regular commit/push history available as these were always undertaken at key stages throughout the development period. As the site uses only HTML & CSS there was no need to add a git ignore file.

## The 4-page design and what each page does and why.

My wife wanted a simple straightforward site design and it was agreed that a 4-page design would meet this brief by presenting all relevant information without being unwieldy or difficult to navigate. The header/footer design used across the site gives a nice splash of colour with a nice flourish being the graded colour moving from purple to yellow diagionally across these sections but with the colours reversed in the footer so they run from yellow to purple. The green used has had it's opacity reduced to make it much more pastel in look. Another flourish is the gallery that is presented as a series of black and white photos that turn to colour when hovered over really drawing your eye to the selected picture. Information about the selected plant/flower is presented via the use of the details element in html. Again Bootstrap enabled this feature albeit customised to better suit the look of the site. The third page is a simple contact me section with email and phone options. A nice touch with the email is the use of mailto: to provide a easy way to begin an email message. There is also the option to click on the Facebook/Instagram icons ever present in the footer to be taken to my wife's social media accounts.

## known issues with project.

1/  There is an issue with embedded Google maps and accessibility as it is not readable by current screen readers. this is a known issue and a Google search highlights this. I still felt that it was a good idea to include the embedded map but equally important to highlight this issue. One that hopefully Google can address in the not too distant future.

2/  During the deployemnt of the build it has also become apparent that Gitpages doesn't always update correctly when using a custom domain name. Hence the need to revert to the standard address for the site on occasion throughout the build and deployment. Once the build has been finalised then the site will use the custom domain 'traceygardengal.com' as this is a better and more professional address for my wife's website and definitely much preferred when giving the website address to potential clients.

3/  The garden images section was added at a later stage in the build to show a complete garden build including landscaping. The images used are again all shot on mobile phone but presented as if they are retro photographs. There are however a couple of issues with the presentation. Firstly, on very high resolution screens ie. either QHD or 4K the images are very widely spaced from each other making the screen look very sparse. Secondly on much narrower screens ie. mobile phones the images stack on top of each other obscuring the images. An unintended effect of this is that they do look like a pile of photographs. On other displays from tablet size upto 1080p desktop displays the photo gallery looks very nice and the decision has been taken to leave this section as it is whilst acknowledging the shortcomings.

## software/websites used for this build

[Bootstrap v5.3 - CSS library](https://getbootstrap.com/)

[Font Awesome v4.7 - Icons](https://fontawesome.com/v4/)

[Adobe Color - Colour Wheel](https://color.adobe.com/create/color-wheel)

[Convertio - Convert JPEG to WEBP](https://convertio.co/jpg-webp/)

[Compress images for website](https://compressnow.com/)

[Custom domain for website](https://domains.google.com/)

[Creates a glass effect using CSS](https://css.glass)

# Tracey the Gardengal

My wife has, over the past three years or so, built a successful garden business having decided to quit her safe but boring office based job of ten years plus. She generates her business through word of mouth with a small part coming from Facebook, it's probably a 90/10 split in favour of word of mouth. She has also just started on Instagram but what is really needed is something that she can get her existing clients to give to potential new clients as an introduction to what she does. Something for potential new clients to have a look at before they speak to her or she contacts them. 

Tracey the Gardengal's website took shape from this simple idea. Together we discussed the format, basic layout and exactly what my wife wanted the site to do. Wireframing was done by hand on a sheet of A4 as it was just easier for us and given that we are husband and wife a lot more comfy that way sitting on our sofa. I have included an image of the hand drawn wireframes for reference purposes. It was also very important that the site works just as well on a mobile device as laptop/desktop as more and more people even in the age demographic that my wife predominantly deals with are just using a mobile device to access the internet.

![Responsive Mockup](https://ui.dev/amiresponsive?url=https://www.traceygardengal.com)

## Features 

### Existing Features

- __Colour Palette__

Tracey decided straight away that her favourite colour, purple, should feature throughout the site. In order to give the site a strong identity it was agreed that a limited colour palette should be used. There are only five colours used throughout the site. The primary site colours of purple, yellow and green were picked using Adobe's colour wheel site. These colours are complimentary and work very well together. The purple and yellow have been used without modification with the green being softened using the rgba command allowing a reduced opacity. It was decided that rather than using the blue from the colour wheel a slightly different shade, the official Facebook/Meta light blue would be used when hovering over the icons in the footer. The final colour is black for the navbar and the text throughout the site to give maximum contrast for legibility and accessibility.

- __The images used__

It was also discussed and decided upon that all the images used throughout the site needed to be from Traceys's work or home and were shot using either my wife's iPhone 11 or my Nothing Phone(1). In keeping with the idea that the site is an introduction to my wife's passion for gardening it was felt that stock/professional pictures would not suit the site ethos. This feature brings an honesty and integrity to the images used.

- __The Header__

  - The way the colours in the header blend together going from purple in the top left to yellow in the bottom right was done to soften the header which could have looked a bit too much if it had been one solid colour.
  - The font, Caveat by Google, was chosen to give a handwritten feel to the title that is in keeping with the 'homegrown' ethos of the site.
  - Featured on all four pages, the use of customised bootstrap buttons really pulls the navigation bar to the fore, making it easy to see and very obvious as to what it does. The use throughout the site of a limited but very well chosen     colour palette, discussed above, means it's nigh on impossible to lose your way on the site and helps achieve the goal of user-friendly, intuitive navigation.

![Header](assets/img/navbar_contrast.png)

- __The Home Page__

  - The home page includes a picture of Tracey's own garden in Buckfastleigh, with a animation that initially draws the eye to the garden.
  - The 'about me'part of the homepage gives a little bit of background to Tracey's decision to become a gardener and the passion that she has for the job.
  - Included in the 'about me' part is an explanation of what each part of the site does.

![Home Page](assets/img/homepage_contrast.png)

- __The Footer__ 

  - Rather than repeat the exact colour blend of the header the decision to reverse the blend so that it is yellow to purple from top left to bottom right gives a nice contrast to the header whilst maintaining colour consistency. 
  - Putting the Facebook and Instagram icons in the footer and having them as links to those sites makes it very easy for people to navigate there and contact Tracey. Having them in the footer means they are present on all four pages of the site.

![Footer](assets/img/footer_contrast.png)

- __Plants__

  - The plants gallery is the main focus of the site and allows Tracey to display images of some of her favourite plants and flowers with a brief description for each available underneath. The gallery is presented in black and white with the selected picture transforming to colour really drawing the visitors eye to that particular image. There is also an image of the gardengal herself with an introduction to the gallery.
  - This section is valuable to the user as every gardener Tracey has ever met loves looking at and talking about pictures of plants and flowers.

  ![Gallery](assets/img/plants_contrast.png)

- __Garden__ 

- When we first moved to Buckfastleigh the garden was just a typical new build garden ie. a boring lawn and nothing else. This series of photos shows the transformation of the garden into something a lot more interesting than just a lawn.
- A completely different kind of gallery compared to the plant gallery, showing a different aspect to gardening that of landscaping. Presented in a very different style from the plant gallery with it made to look like a series of retro photographs.

![Gallery](assets/img/garden_contrast.png)

- __The Contact Page__

  - In addition to the icons in the footer that are present throughout the site the contact section adds a clickable email icon that launches an email window allowing potential clients to contact Tracey this way. It also shows another image of the gardengal and includes an embedded interactive Google map that shows Buckfastleigh allowing people an opportunity to check out how far they are from the Tracey's location. This is important in a rural setting where people may not be completely familiar with a location and it's surrounding area. 

![Contact](assets/img/contact_contrast.png)

### Features Left to Implement

- As the site is complimentary to Tracey's word of mouth business model there are no further features to implement and the site is considered complete whilst acknowledging that the plant gallery will need updating from time to time keep abreast of current plant/flower trends.

## Testing 

My testing of this site has, I believe, been as thorough as it can be. Each part of the build was built first in Stackblitz IDE allowing me to build 'bitesize' chunks of code and test them before adding them into my main code built using VS Code IDE. I do my development work using a 27" QHD Iiyama monitor allowing me to ensure that it presents itself well when viewed on a very hi-res monitor. I also have a secondary Iiyama 24" 1080p monitor allowing me to further check how the site presents itself at a resolution that I think more people use. However the design was conducted from a mobile forward viewpoint so extensive use was made of Chrome devtools and devtools' ability to mimic a wide range of devices from mobile phones to tablets. Devtools has a responsive mode where you can change the resolution to whatever you want and I used this to mimic a few other resolutions such as 1368*768 which is also a quite common monitor resolution. The devices mimic'd were the iPhone SE, iPhone XR, iPhone 12 Pro, Moto G Power, Kindle Fire HD, Galaxy Fold, Google Nest Hub, Google Nest Hub Pro, iPad, iPad Air, iPad Mini, iPad Pro, Samsung Galaxy S8+, Surface Pro 7 and Surface Duo. In addition to these virtual devices I tested extensively using Chrome on my Android Nothing Phone(1) and Safari on my wife's iPhone 11. Desktop browsers used for testing were Chrome v114.0.5.5735.198, Firefox v114.0.2 and Edge v114.0.1823.67. There are of course a multitude of different browsers out there and it is difficult to guarantee behaviour across all of them, but I believe that a good variety of devices have been tested for including phones, tablets, folding phones and desktops and the most common browsers have been tested with the exception maybe of desktop Safari. The responsive test (link included earlier in this readme) does mimic Apple devices and this includes Safari on an iMac and given that the site responds well on this test site I have no reason to believe there would be any issues for anyone using an Apple computer. 

Each breakpoint in Bootstrap was thoroughly tested with various customisations made to my code to ensure that the site maintains its integrity regardless of the device used to view it. Additional breakpoints have been added to ensure not only that the site looks good at all likely viewing resolutions but also that it maintains this integrity whether the device used is in portrait mode or landscape mode. The various texts from header, footer and main body of pages adjusts accordingly and where possible the units used for describing height and width are not fixed ie px for pixels but more responsive units such as % percentage, or dvh dynamic viewport height. Where these cannot be used such as with embedded Google maps which insists on px pixels a class and wrapper have been custom created to give a measure of responsiveness.

I also got friends involved and asked them to view the website an give feedback as other people can often see something that's been missed and their feedback was used to make further modifications to the resonsiveness of the site. A special mention need to be made to Richard Kraft, a fellow student and a web developer who offered to look at the site and give constructive feedback. This feedback was invaluable in getting the site to where it is now.

During testing the main issues were overspill of text from the homepage into the header and footer, overspill of the photos in the garden section into the header and footer and poor presentation including overspill of the website title, navbar buttons and the text on the site when viewed on a mobile device in landscape mode. There was also an issue with the large email icon sitting behind the Google map when viewed on a mobile device in landscape mode and an issue with the image on this page not presenting correctly, again when a device is in landscape mode. All of these issues have been corrected with the email icon and image being removed from landscape mode but being present in portrait mode. Adjustments were made to font sizes at various breakpoints and of the three paragraphs of text on the homepage, one paragraph is removed under certain conditions to eliminate overspill as I did not want scrollbars to be used as I feel that this is a poor user experience.

Realised at the last minute of testing/checking that there was a serious flaw with the logic being used when applying media queries. Breakpoints had to be rewritten and then minor bugs solved due to the refined logic.


### Validator Testing 

- HTML
  - No errors were returned when passing the home page through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fwww.traceygardengal.com%2Findex.html)
  - No errors were returned when passing the gallery page through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fwww.traceygardengal.com%2Fgallery.html)
  - No errors were returned when passing the garden page through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fwww.traceygardengal.com%2Fgarden.html)
  - No errors were returned when passing the contact page through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fwww.traceygardengal.com%2Fcontact.html)
 
- CSS
  - No errors were found when passing the css code by direct imput through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator)
    ![W3C CSS Validated](assets/img/w3c_css_validated.png)

### Unfixed Bugs

There are no unfixed bugs that am I am aware of. Testing has been very thorough throughout the build.

## Deployment 

- The site was deployed to GitHub pages. The steps to deploy were as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the Source section drop-down menu, select the Master Branch
  - Once the Master Branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 
  - In custom domain 'www.traceygardengal.com' has been saved with a successful DNS check as the site address needs to better reflect my wife's business.

The live link can be found here - https://www.traceygardengal.com/index.html 

## Credits 

A special thank you to [Richard Kraft](https://www.linkedin.com/in/richardjohnkraft/), a fellow student and software developer, for taking timeout from his busy schedule to offer advice, support and feedback as I tackled my first project.

### Content 

- Responsive site code courtesy of Bootstrap, [Bootstrap v5.3 - CSS library](https://getbootstrap.com/)
- The glass effect used on the homepage to highlight the year of the home page image courtesy of Glassism, [Creates a glass effect using CSS](https://css.glass)
- The Facebook, Instagram & Email icons courtesy of Font Awesome, [Font Awesome v4.7 - Icons](https://fontawesome.com/v4/)

### Media

- All images used were shot on my wife's iPhone 11 or my Android Nothing Phone(1) avoiding any copyright issues.