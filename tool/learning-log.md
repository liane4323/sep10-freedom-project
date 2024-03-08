# Tool Learning Log


Tool: **Animate.CSS + Wow.JS**


---

2/26/24:
* read through this [article](https://medium.com/codebagng/making-awesome-animations-using-animate-css-and-wow-js-2e9ac4faad75) to use effects in my webpage
* important tip given --> "Do not hesitate to ask people around you for help, you know not who has the answer to your biggest question!"

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
This code is using keyframe to specify the code animation that they want to use which in this case is change-color. It enables the text color to be changed into any colors that you pick. This animation is very useful if you are trying to point something out in your website insead of making it bold or italicizing it. 

_**Next Steps**: I will research ways on how to problem solve Wow.Js errors._


<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
