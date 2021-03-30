# Transforms:
### The value specifies the transform type followed by a specific amount inside parentheses.
![](https://res.cloudinary.com/dno0vkynk/image/upload/v1475392871/CSS3Transforms2D.png)
* **Transform Syntax**
* **2D Transforms**: works in x and y axis, scale change and combining transforms.
* **Combining Transforms**: allow to rotate the element from 0 to 360 drg.
* **Transform Origin**:The transform-origin property can accept one or two values. When only one value is specified, that value is used for both the horizontal and vertical axes. If two values are specified, the first is used for the horizontal axis and the second is used for the vertical axis. 
* **Perspective**: When you want to transform a group of elements all with the same perspective, or vanishing point, apply the perspective property to their parent element.
* **3D Transforms**: including rotateX, rotateY, and rotateZ.
* **Transform Style**: The transform-style property needs to be placed on the parent element, above any nested transforms.
* **Backface Visibility**: When working with three-dimensional transforms, elements will occasionally be transformed in a way that causes them to face away from the screen. This may be caused by setting the rotateY(180deg) value for example. By default these elements are shown from the back. So if you prefer not to see these elements at all, set the backface-visibility property to hidden, and you will hide the element whenever it is facing away from the screen.

-----
------
# Transitions & Animations:
There are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay.
### Example:
     
     .box {
    background: #2db34a;
    -webkit-transition-property: background;
       -moz-transition-property: background;
         -o-transition-property: background;
            transition-property: background;
    -webkit-transition-duration: 1s;
       -moz-transition-duration: 1s;
         -o-transition-duration: 1s;
            transition-duration: 1s;
    -webkit-transition-timing-function: linear;
       -moz-transition-timing-function: linear;
         -o-transition-timing-function: linear;
            transition-timing-function: linear;
     }
    .box:hover {
     background: #ff7b29;
    }


### Transition duration:
The value of this property can be set using general timing values, including seconds (s) and milliseconds (ms). These timing values may also come in fractional measurements, .2s for example.

## Animations:
The @keyframes rule includes the animation name, any animation breakpoints, and the properties intended to be animated.
![](https://miro.medium.com/max/12000/0*bxOzWv3uzgbHid2i)
* Animation name
* Animation Duration, Timing Function, & Delay
* Animation Direction
* Animation Play State

------
------
## 8 simple imazing transitions:
1.  Fade in
2. Change color
3. Grow & Shrink
4.  Rotate elements
5. Square to circle
6. 3D shadow
7. Swing
8. Inset border

