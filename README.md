#Responsive-video
================

##STEP 1: 
Just place your video in a wrapper with class "video-container".
```sh
<div class="video-container">
         <iframe src="http://www.youtube.com/embed/ERubh80hIuE" frameborder="0" width="560" height="315"></iframe>
</div>
```
##STEP 2: 
Add the existing CSS property to your css.
```sh
.video-container {
        height: 0; 
        overflow: hidden;
        position: relative;
        padding-bottom: 56.25%;
        padding-top: 30px; 
    }
    .video-container iframe, .video-container object, .video-container embed {
        height: 100%;
        left: 0;
        position: absolute;
        top: 0;
        width: 100%;
    }
```
