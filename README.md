## Installation
``` yarn add gsap ```

## Utility
```javascript
import {gsap} from 'gsap';

gsap.to('.elem1',{
   duration:1,
   y:-50 //to move to the position of y = -50;
   //animation...
}) 
```

### ScrollTrigger
```javascript
import {ScrollTrigger} from 'gsap/ScrollTrigger'

gsap.to('.elem1',{
  duration:1,
  y:-50,
  scrollTrigger:{
  trigger:'.elem1',
  start:'top 80%',
  end:'bottom 25%,
//EVENTS onEnter onLeave onEnterBack onLeaveBack
//OPTIONS play,pause,resume,reset, restart,complete, reverse, none
	toggleActions:"restart none none reverse"
  
  }
})
```
