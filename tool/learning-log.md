# Tool Learning Log


Tool: **Animate.CSS + Wow.JS**

---
### LOYO 1

2/26/24:

* read through this [article](https://medium.com/codebagng/making-awesome-animations-using-animate-css-and-wow-js-2e9ac4faad75) to use effects in my webpage
    * important tip given --> "Do not hesitate to ask people around you for help, you know not who has the answer to your biggest question!"



### LOYO 2

3/4/24:

[HubSpot](https://blog.hubspot.com/website/css-animation-not-working) is a website used to assist with problem solving CSS Animation issues. In case I get stuck along my LOYO journey, I will go back to this site for reference.

As I was reading through this website I copied and pasted the "Multiple Misaligned Animation Property Values" code into jsbin. Then I proceeded to analyze the CSS and figure out the significance each line of code has.

*  animation-iteration-count → amount of times the animation repeats
*  word-spacing → the distance between each word as the animation is on
*  @keyframe is a rule that specifies the animation code

Below is a code snippet of code that I found interesting, I may consider using it on my own website.

```
 @keyframes change-color {
  25% { color: #00A4BD; }
  50% { color: #FF7A59; }
  75% { color: #00BDA5; }
}
```
This code is using keyframe to specify the code animation that they want to use which in this case is change-color. It enables the text color to be changed into any colors that you pick. This animation is very useful if you are trying to point something out in your website instead of making it **bold** or _italicizing_ it.

_**Next Steps**: I will research ways on how to problem solve Wow.Js errors._




### LOYO 4

3/18/24

I watched this video https://www.youtube.com/watch?v=EkHkiV1pIzE
* I learned how to install animate.css manually into your computer documents.
     * I think I am planning on linking it into my code without downloading it
 * This video was helpful in terms of getting started with a step by step tutorial

useful github link from the youtube video above; https://github.com/matthieua/WOW/blob/master/README.md
* The "build status" section of the README.md is more like a intro for wow.js and animate.css'

On this [github page](https://github.com/matthieua/WOW/tree/master) I liked how the JS code was explained, my initial reaction to the code was so confusing. However as I continued reading and trying to get an understanding, the more I understood.

JavaScript code snippet:

```
var wow = new WOW(
  {
    boxClass:     'wow',      // animated element css class (default is wow)
    animateClass: 'animated', // animation css class (default is animated)
    offset:       0,          // distance to the element when triggering the animation (default is 0)
    mobile:       true,       // trigger animations on mobile devices (default is true)
    live:         true,       // act on asynchronously loaded content (default is true)
    callback:     function(box) {
      // the callback is fired every time an animation is started
      // the argument that is passed in is the DOM node being animated
    },
    scrollContainer: null // optional scroll container selector, otherwise use window
  }
);
wow.init();
```

_**Next Steps**: I will make an attempt to start a independent code practice using both of my tools._


### LOYO 5

In order to implement my learning so far, I made a html and css file to add in my code practice. As I continue to learn new things about my tools I will make changes into these files.

For today I am going to prep for my code and figure out what I want to do. I added html starter templet from W3 schools and put it into my <a href=index.html> index.html </a> 








<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
