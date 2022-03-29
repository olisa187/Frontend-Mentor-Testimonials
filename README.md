# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

- This testimonial card is a reponsive one is designed for the user to veiw it in both desktop and mobile
devices.

### Screenshot

#### Desktop version of the testimonial card.
![](screenshot-desktop.jpg)

#### Mobile version of the testimonial card.
![](screenshot-mobile.jpg)

### Links

- Solution URL: [Github page](https://github.com/olisa187/Frontend-Mentor-Testimonials)
- Live Site URL: [Testimonial card grid](https://harmonious-parfait-d16536.netlify.app)

## My process
    
My process in building out this testimonial cards is listed below

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

During the bulding out of this testimonial challenge I introduced a html tag that I mostly don't see other 
developer use. I decided to use the hgroup tag to group the name of the testifer and his or her verification 
status as one knowing fully well that I could have done this using other html tags. 

I learned the use of flow mechanism or styling in css to add margin to all child element of the parent container excluding the first-child of each parent element or tag in the main container.

I really love the way I was able to list all the color styles in the root. Thereby, creating different variable name for each of the colors that will in turn aid to change a specific color across the site if the need be. Therefore, I have listed the html structure and css style below for easy veiwing.

```html
<hgroup class="testifier-details">
    <h3>Kira Whittle</h3>
    <h4>Verified Graduate</h4>
</hgroup>
```

```css
:root {
    /* color styles */
    --clr--m-v: 263, 55%, 52%;
    --clr-v-d-g-b: 217, 19%, 35%;
    --clr-v-d-b-b: 219, 29%, 14%;
    --clr-white: 0, 0%, 100%;
    /* Neutral colors */
    --clr-l-g: 0, 0%, 81%;
    --clr-l-g-b: 210, 46%, 95%;

}

body *+* {
  margin-top: 1.5em;
}
```

finally, in this challenge I learnt how to link images in a mark down file using the '[]' square bracket symbol, create main-headers and sub-headers using the hash symbol.

### Continued development

In future development of more web pages and app I will really like to focus on the use of BEM that is Block Element Modifiers as one of my attribute naming convention across my web pages to enable me to easily modify related element and tags across the entire built web page saving me the stress of changing them one after the other. 
In summary, to this I will like to focus more in making a good structured content.

### Useful resources

- [CSS GRID, Flexbox](https://www.youtube.com/c/TraversyMedia) - TraversyMedia youtube page really help to crown and fully understand css-grid and flexbox

- [CSS styles](https://www.w3schools.org) - I used to web page as reference to read their article on some css styles and html structures that I might have found difficult in comprehending its use or have forgotten how to use them.

- [Github](https://www.docs.github.com) - This is an amazing article which helped me finally to get to start working with git and github from creating a SSH auth in my local machine to initilizing a git repository to staging of files to commiting of staged files and last but not the least to pushing of files from my local machine to my github. I'd recommend it to anyone still learning about git and github.

- [Git](https://www.youtube.com/watch?v=RGOj5yH7evk&t=51s) - This video from Gwen Faraday also helped me to crown my sucess in the mastering of git and github. I will also recommend to this comprehensive tutorial video to any one venturing into the use of git and github and to those who learn very good by videos. 

## Author

- Frontend Mentor - [@olisa187](https://www.frontendmentor.io/profile/olisa187)
- Twitter - [@Olisa187](https://www.twitter.com/olisa187)


## Acknowledgments

I want to Acknowledge people that have been of benefit to my learning progress and process in the world of web development even though I have not met them directly but their online content have gone a long way to my development progress.

- Traversy media
- Kelvin Powell
- Gwen Faraday
- DevsEdu
- frontendmentor.io
