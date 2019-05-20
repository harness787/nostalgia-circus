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
- I also plan to add the band's official youtube to the youtube icon located in the contact tab once it is created.

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- HTML
- CSS
- JS
    * Used for landing page elements
- JQuery
    * Used for landing page elements
- [Fontawesome](https://fontawesome.com)
    * Used for icons such as scrolling arrow and social media icons
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

I'm very happy with how well I acheived the inteded purpose for each of the user stories. I have tested all screen widths for functionality and UX through two browser's inspect element tool (Chrome and Opera) and my iPhone 7 for true mobile testing. 

The embedded elements in the music page allows the user to play the music in the website. If the user wishes to visit the soundcloud page, they are easily put into a new tab that takes them into the track they are interested in. 
The links in the upcoming shows page all open in new tabs with the exception of the text located at the bottom of the screen that links to the in-site contact page. The elements hover and don't overlap and the google maps takes the user to the location pinged in a new google maps tab. 
The contact form will not submit without all forms filled out and the email address formatted correctly. The social media icons link out to the band's social media with the exception of the youtube link since the band doesn't have an official youtube channel set up. It currently links to the youtube home page.

The project and its images scale to fit different sizes to optimize UX through the use of bootstrap col classes.  

One bug I was struggling with for a long time was that the testing I was doing on my iPhone was rendering no background image on the landing page. I realized this was due to the "background-attachment:fixed" class not working in mobile browsers. The post on this [StackOverflow](https://stackoverflow.com/questions/30102792/css-media-query-target-only-ios-devices) page helped me solve this problem.
## Deployment
I'm currently hosting this site on GitHub pages directly from the master branch. 

## Credits

### Content
- All text was written by me.

### Media
- All photos used on this site were developed or taken by me or one of the band members. 

### Acknowledgements

- I received inspiration for this project from other music artist/band websites like http://www.kidcudi.com and https://injuryreserve.online.