# yluo8925_9103_tut4
#Week 8 Quiz Homework#

## Part 1: Imaging Technique Inspiration

1. The idea is for a bunch of social media images to shoot out from one point, but end up static and not moving across random locations across the canvas

[Social media facebook livestream like and love reaction increasing icons flying up animation on green screen background](https://www.vecteezy.com/video/26427782-social-media-facebook-live-stream-like-and-love-reaction-increasing-icon-flying-up-animation-on-green-screen-background)

2. For the project I would like to learn to set up a constraining point for all the objects that are shooting out. I think this is important that we will need to animate certain objects, possibly with classes if there are more objects to be included in, and I want to learn on how to animate a number of different objects and set them all statically to random points. This may also give me a better understanding of how object animation and location works, and makes it easier to set up the creative aspect of the project.
- [Social media image web effect picture 1](assets/Social%20media%20image%201.jpg)
   - if possible I could branch out the icons with webs or other shapes and images to create a sort of web effect
- [Social media image web effect picture 2](assets/Social%20media%20image%202.jpg)

## Part 2: Coding techniques

**I think the constrained function is able to stop the object / and constrain the object at a certain point**
```
y = constrain(y,0,570);

function keyPressed() {
  if (keyCode === UP_ARROW) {
  ymod = -1;
  } else if (keyCode === DOWN_ARROW) {
  ymod = 1;
  }
}
```

**Next I could draw multiple objects using a class and for loop by creating an array**
** replace icons by loading the images and storing it into the array **

```
let Icons = [];
let numIcons = 20;

function setup(){
createCanvas(400,400);

Like = new Icon();
Smile = new Icon();
Laugh = new Icon();

for(let i = 0, i<numIcons; i++){
Icons[i] = new Icon();
}
print(icons[20]);


}


```