# HTML Images
## We can edit images by using CSS to control size and alignment and how the image should look like . 
## To control image size we use width and height properties, for example : 
img.large {

width: 500px;

height: 500px;}

img.medium {

width: 250px;

height: 250px;}

img.small {

width: 100px;

height: 100px;}
## We can make the size small or meduim or large . 
## To control image align we use float and margine propreties, for example:
img.align-left {

float: left;

margin-right: 10px;}
## To center images we use : 
img.align-center {

display: block;

margin: 0px auto;}

img.medium {

width: 250px;

height: 250px;}
## We can put an image as a background : 
body {

background-image: url("images/pattern.gif");

}
## We can control the background image repeat if we want to repeat it or not .


## Search Engines Optimization
### Search Engines Optimization: is the practice of trying to help your site appear nearer the top of search engine results when people look for the topics that your website covers.

## In every page of your website there are seven key places where keywords can appear in order to improve its findability:
1. #### Page Title
2. #### Web Address
3. #### Headings
4. #### Text
5. #### Link Text
6. #### Image Alt Text
7. #### Page Descriptions


## six steps that will help you identify the right keywords and phrases for your site:
1. #### Brainstorm
2. #### Organize
3. #### Research
4. #### Compare
5. #### Refine
6. #### Map

## We use File Transfer Protocol To transfer the code and images from computer to your hosting company.
## FTP examples : 
1. #### FileZilla (filezilla-project.org)
2. #### FireFTP  (fireftp.mozdev.org)

## We can add viedo and audio elements in HTML, by using the < viedeo> and < audio> elements . 
### ontrol video and audio players programmatically for example :
### HTMLMediaElement.play() 
### HTMLMediaElement.pause()
## To control when to play and pause the video: 
play.addEventListener('click', playPauseMedia);

function playPauseMedia() {
  
  if (media.paused) {
    
    play.setAttribute('data-icon','u');
    media.play();
  
  } else {
    
    play.setAttribute('data-icon','P');
   
    
    media.pause();
 
  
}

}
## Flash 
### Flash has been a very popular tool for creating animations, and later for playing audio and video in websites.
## To add flash into a web page we use JavaScript, for example : 
< title>Adding a Flash Movie< /title>

< script type="text/javascript"src="http://ajaxgoogleapiscom/ajax/libs/swfobject/2.2/swfobject.js">

< /script>

< script type="text/javascript">swfobject.embedSWF("flash/bird.swf",
"bird", "400", "300", "8.0.0");

< /script>
< /title>

