# Nostalgia Circus

User-Centric Frontend Development project for Code Institute. 

This project is a website for the band Nostalgia Circus based out of Conway, AR.  
 
## UX

My goal for the UX in this website was to design the website as to be attractive on all devices with an emphasis on a minimalist style and responisve elements for desktop users. This website is eventually planned to be used for in-site booking, so it was important to me that the site be easy to navigate while also being attractive. 

When designing this site, I ended up straying quite a bit from my initial plan for the UX. I elected to align many items vertically rather than horizontally as I previously planned, I added a google maps function, and the about section looks very different than what I initially planned.
I wanted to provide basic infomation on the band for those new to them, information for fans looking to see their shows, and a way for people to contact the band if they have questions or want to book the band for a gig.

*Wireframes:* 
- [Desktop Wireframes](https://imgur.com/a/V1qZIkq)
- [Mobile Wireframes](https://imgur.com/a/rAPQBax)



## Features

On the landing page, the user lands on a fullscreen background of a logo with a bouncing arrow taken from a [codepen](https://codepen.io/bewley/pen/revRQv). As the screen scrolls, the elements on the screen fade thanks to help from [this]( https://www.youtube.com/watch?time_continue=55&v=-_ojaBSxhmk) video. On the landing page, the navbar changes from fixed to staic on screens above 1475px in width. This is because the navbar at this width interferes with the text of the about section and having a solid color navbar that stays on the screen makes for worse UX. In order to have the about page be easy to navigate despite the static navbar, I added an arrow that appears in the bottom right of the screen that allows the user to transition back to the top of the page thanks to the help of [html-online.org](https://html-online.com/articles/dynamic-scroll-back-top-page-button-javascript/). This arrow dissapears when the screen is under 1475px in width due to it not being necessary. When screens are under 1200px in width, the navbar switches to having a white background in order to stay present through scrolling and not interfere with the text in the about section. The space between 1475px and 1200px in width has a transparent background and the navbar remains fixed to the top because this width does not interfere with the text of the about section. 
The music page has 3 embedded elements that are provided by [Soundcloud](https://soundcloud.com). These 3 elements, which scale to become larger when hovered over and can play the music released by the band, provide for a way for fans and those new to the band to easily listen to the band's music.
The upcoming shows page currently lists the next two shows along with a google map location of the next show. The map was provided by [this](https://www.embedgooglemap.net) website.
The last page has a [bootstrap](https://getbootstrap.com) contact form and has icons that link out to the band's social media. 
 
### Features Left to Implement
- I eventually plan to make the site a booking hub for the band where business owners and event organizers can come and book Nostalgia Circus to play at their venues. 

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- HTML
- CSS
- JS
    * Used for landing page elements
- JQuery
    * Used for landing page elements
- [Bootstrap](https://getbootstrap.com)
    * Used to speed up development
- [Soundcloud embed tool](https://soundcloud.com)
    * Used to display music on site in a ux-friendly way
- [Google map embed](https://www.embedgooglemap.net)
    * Used to show a location for the band's next show
- [HTML Validator](https://validator.w3.org)
    * Used to correct errors in HTML code
- [Codepen](https://codepen.io/bewley/pen/revRQv) by [Will Bewley](https://www.youtube.com/channel/UC4K51WXJcaAmj2f80yDwFug) 
    * Used to improve UX on landing page 
- [Scroll activated fade animation](https://youtu.be/-_ojaBSxhmk) by [Rinkans](https://www.youtube.com/channel/UC4K51WXJcaAmj2f80yDwFug)
    * Used to improve UX on landing page
- [Scroll activated arrow](https://html-online.com/articles/dynamic-scroll-back-top-page-button-javascript/) by [html-online.com](https://html-online.com)
    * Used to improve UX on landing page 


## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X