
#  What Google Learned From Its Quest to Build the Perfect Team
- The technology industry is not just one of the fastest growing parts; it is also increasingly the world’s dominant commercial culture. And at the core of Silicon Valley are certain self-mythologies and dictums: Everything is different now, data reigns supreme, today’s winners deserve to triumph because they are cleareyed enough to discard yesterday’s conventional wisdoms and search out the disruptive and the new.


- The paradox, of course, is that Google’s intense data collection and number crunching have led it to the same conclusions that good managers have always known. In the best teams, members listen to one another and show sensitivity to feelings and needs.


- The fact that these insights aren’t wholly original doesn’t mean Google’s contributions aren’t valuable. In fact, in some ways, the ‘‘employee performance optimization’’ movement has given us a method for talking about our insecurities, fears and aspirations in more constructive ways. It also has given us the tools to quickly teach lessons that once took managers decades to absorb. Google, in other words, in its race to build the perfect team, has perhaps unintentionally demonstrated the usefulness of imperfection and done what Silicon Valley does best: figure out how to create psychological safety faster, better and in more productive ways.


Article : Transforms
The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

Transform Syntax
```
div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}
```
2D Transforms
1. 2D Rotate
```
.box-1 {
  transform: rotate(20deg);
}

.box-2 {
  transform: rotate(-55deg);
}
2. 2D Scale
.box-1 {
  transform: scale(.75);
}
3. 2D Translate
.box-1 {
  transform: translateX(-10px);
}
4. 2D Skew
.box-1 {
  transform: skewX(5deg);
}
Combining Transforms
.box-1 {
  transform: rotate(25deg) scale(.75);
}
.box-2 {
  transform: skew(10deg, 20deg) translateX(20px);
}
```
# Article : Transitions & Animations
Transitions
The potential to alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, focused on, active, or targeted.

There are four transition related properties in total: transition-property, transition-duration, transition-timing-function, and transition-delay.
```
.box {
  background: #2db34a;
  transition-property: background;
  transition-duration: 1s;
  transition-timing-function: linear;
}
```
## Transitional Property
The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties.
```
.box {
    background: #2db34a;
    border-radius: 6px
    transition-property: background, border-radius;
    transition-duration: 1s;
    transition-timing-function: linear;
  }
  ```
# Transition Duration
The duration in which a transition takes place is set using the transition-duration property. The value of this property can be set using general timing values, including seconds (s) and milliseconds (ms). These timing values may also come in fractional measurements, .2s for example.
```
.box {
  background: #2db34a;
  border-radius: 6px;
  transition-property: background, border-radius;
  transition-duration: .2s, 1s;
  transition-timing-function: linear;
}
```
# Article : 8 SIMPLE CSS3 TRANSITIONS THAT WILL WOW YOUR USERS
```
.fade
{
        opacity:0.5;
}
.fade:hover
{
        opacity:1;
}
```
1. Change color

2. Grow & Shrink
```
.grow:hover
{
        -webkit-transform: scale(1.3);
        -ms-transform: scale(1.3);
        transform: scale(1.3);
}
```
.shrink:hover
{
        -webkit-transform: scale(0.8);
        -ms-transform: scale(0.8);
        transform: scale(0.8);
}
```
1.Rotate elements

2.Square to circle
```
.circle:hover
{
        border-radius:50%;
}
```
# 1.D shadow

# 2. Swing
```
@-webkit-keyframes swing
{
    15%
    {
        -webkit-transform: translateX(5px);
        transform: translateX(5px);
    }
    ```
Inset border