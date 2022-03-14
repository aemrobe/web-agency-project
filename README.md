# Web Agency challenge

## Table of contents

- [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

in this challenge I try transition property in my elements.

transition property gives a rule how an element should transit from one value of the propety to the other value of property.
for example:- I use transform property to .front-text class in this challenge.

```
HTML
   <article class="service black-bg ">
           <div class="front-text ">
              <span class="service-icon">
                    <i class="fa fa-line-chart"></i>
              </span>

              <h2 class="service-title">
                         Analytics
              </h2>
            </div>

           <div class="back-text ">
              <h2 class="service-title align-left">
                     web development
               </h2>

                <p class="service-text">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae nam fuga, rerum labore porro nesciunt rem quam
                    laboriosam dolor exercitationem!
                 </p>

                <button class="service-btn " type="button">Read More</button>

            </div>
   </article>
```

```
css
.front-text{
transition: transform 1s ease;
}

.service:hover .front-text{
tranform: translateY(-200px);
}
```

the transform property will move .front-text class to the top so this transition property tells .front-text class should move from it's current position to the top within 1s and also it tells the .front-text class should move slowly at first,fast at the middle,slowly at the end;

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- desktop-first workflow

### What I learned

in this section I learn how can I use transition property.

### Continued development

for the future I want to reinforce my skills of css grid, css flexbox ,responsive design,css animation.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@aemrobe](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@Aemro112](https://www.twitter.com/Aemro112)
