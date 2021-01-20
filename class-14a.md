# CSS
## The transform property comes in two different settings:
1. #### Two-dimensional 
2. #### Three-dimensional

## Transform Syntax 
### The actual syntax for the transform property is quite simple, including the transform property followed by the value for example : 
div {

  -webkit-transform: scale(1.5);

     -moz-transform: scale(1.5);

       -o-transform: scale(1.5);

          transform: scale(1.5);

}
 
## 2D Transforms 
1. #### 2D Rotate
2. #### 2D Scale
3. #### 2D translate 
4. #### 2D Skew

## 2D rotate example : 
.box-1 {

  transform: rotate(20deg);

}

.box-2 {

  transform: rotate(-55deg);

}

## 3D Transforms
1. #### 3D rotate
2. #### 3D Scale
3. #### 3D Translate
4. #### 3D Skew

## Backface Visibility example : 
.box-1 {

  transform: rotateY(180deg);

}

.box-2 {

  backface-visibility: hidden;

  transform: rotateY(180deg);

}
## Transitions
### Transition properties:
1. #### transition-property,
2. #### transition-duration
3. #### transition-timing-function
4. #### transition-delay

## For example :
.box {

  background: #2db34a;

  transition-property: background;

  transition-duration: 1s;

  transition-timing-function: linear;

}

.box:hover {

  background: #ff7b29;

}
## Customizing Animations
### Customizing animations examples : 
1. #### Animation Iteration
2. #### Animation Direction
3. #### Animation Play State
4. #### Animation Fill Mode

## CSS3 has introduced countless possibilities for UX designers, and the best thing about them is that the coolest parts are really simple to implement.
### 8 simple effects that will add life to your UI :
1. #### Fade in
2. #### Change color
3. #### Grow & Shrink
4. #### Rotate elements
5. #### Square to circle
6. #### 3D shadow
7. #### Swing
8. #### Inset border
