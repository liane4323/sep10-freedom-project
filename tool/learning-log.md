# Tool Learning Log


Tool: **Animate.CSS + Wow.JS**

---
## LOYO 1

2/26/24:

* read through this [article](https://medium.com/codebagng/making-awesome-animations-using-animate-css-and-wow-js-2e9ac4faad75) to use effects in my webpage
    * important tip given --> "Do not hesitate to ask people around you for help, you know not who has the answer to your biggest question!"



## LOYO 2

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




## LOYO 4

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


## LOYO 5

In order to implement my learning so far, I will create a practice web page from scratch. I made a html and css file to add in my code practice, as I continue to learn new things about my tools I will make changes into these following files.

*  <a href=index.html> index.html </a>
*  <a href=style.css> style.css </a>

For now, I am going to prep my code and figure out what I want to do. I added html starter templet from W3 schools and put it into my html file. I am going to use animate and wow to reveal animations as you scroll down the page. I will be using 2 images, h1 and paragraphs.

### MVP

* Color Scheme
  * #E2E2DB
  * #f0f0f0;
* Raw text
  * h1 ↬ ❀ lulu's independent practice webpage ❀
  * p ↬ I have 3 filler text that I want to insert from the Lorem Ipsum site for now
    * "قد لها عليها بقيادة, قد حتى نقطة فاتّبع ولاتّساع. وسفن ولكسمبورغ أم عدد, تم الى دارت لهيمنة. بين ان صفحة شرسة, أم عدد ألمّ أراضي التاريخ،. ما أما بهيئة الأسيوي التخطيط. قام لإعلان السادس عل, لم مكن كرسي الغالي الهجوم, يذكر أهّل أمدها لم كلا."
    * ""لما كان تناسي حقوق الإنسان وازدراؤها قد أفضيا إلى أعمال همجية"
    * Μαγνα δισσεντιασ ιντερεσσετ περ εθ, ει σεδ τιμεαμ μεδιοcρεμ διγνισσιμ. Αδ νθμqθαμ ανcιλλαε δισπθτανδο ηισ, ειθσ vιδιτ τατιον ιδ ηασ. Εφφιcιαντθρ cοντεντιονεσ ρεπρεηενδθντ νο περ. Μελ θτ διcερετ δεφινιτιονεσ, qθισ ιδqθε εθ δθο. Εα λεγερε απεριαμ ρεπθδιανδαε cθμ. Vιξ νο ηενδρεριτ σcριπσεριτ.
  * imgs ↬ 2 nature pictures
    *  <a href=pic1.1.jpg> pic1 </a>
    *  <a href=pic2.2.jpg> pic2 </a>


## LOYO Work Week

We have 3 last days to work on learning our tool, so here is what I plan on doing.

### Agenda

* Day 1: I plan on working on my independent webpage that I created to practice my tools. I will insert the context that I had already prepped into my html page and tinker around with how I want my webpage to look. I already know that I want my website to be long enough to scroll down so that the animation will work.

* Day 2: On this day I will use animate.css to start animating. I will figure out how the animations work + what I should animate. My MVP is to at least make 3 things animated, but I will try and animate all of my content.

* Day 3: I will use on wow.js in order to hav my animations work as I am scrolling on my webpage. If I have any issues I will be using this day to troubleshoot, make edits + reflect.

#### Day 1
_4/3/24_

I completed my html and css, I did run into an issue that took so much time to fix. At first I had trouble with my css because it was unresponsive. I decided to delete my style.css file and linked my css into my index.html. It worked in the end and I am proud of my work. Taking into consideration that I completed my code from scratch. Sometimes my lines of code wouldn't work so I had to go back and review it thoroughly. It turned out to be spelling mistakes/errors.

#### Day 2
_4/4/24_

I took time in class to make any last html/css changes that I was unhappy with. My website is looking good now! The animations that I added will make it better. Later on today, I started working on applying my animations. I made sure to install animate.css using a CDN. I was very excited when I tested out an animation on my h1, and it worked!

* I used https://animate.style/ to get my animations

#### Day 3
_4/5/24_

This is my last working day, I managed to complete my MVP and more! I reached the goal that I had set for myself which is to animate all of my headings and imgs. During the proccess of coding, I linked wow.js before closing my body tag. I am proud of my work and I will be using some of these animations and applying them into my Freedom Project!





<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
