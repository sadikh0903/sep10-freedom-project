# Entry 4
##### 3/9/26
## **Content**
Mr Mueller introduced us to a bunch of tools to use for our SEP 10 Freedom project and our invention, the tool that I decided to go with was Aframes. Aframes is used for a variety of things like creating 3D models that also incorperate VR to make your boring old model, more interactive and with purpose.  I used this tool to create a 3D model of how the basis of my invention (Mediscan+) will work. 

I started to learn how to use Aframes through Aframes school which was like a workshop made for understanding the basics. I had a lot of trouble with grasping how I would implement Aframes into my freedom project, and even understanding how I would use it originally but, this all became much easier once I began to work on Aframes itself. I used After using Aframes for a week, this is what I can take away;
I learned how to rotate my objects in a variety of ways through the rotation on the a-box position, this is useful for manipulating geometric shapes & normal shapes, I also learned you can move these objects by;
* Moving the object left by decreasing the position's X value
*  Moving the object up by increasing the position's y value
* Moving the object back by decreasing the position's z value
* Moving the object right by increasing the position's x value.
* learned this by using the Aframe schools tutorial, and by searching up tutorials on youtube
* I'm still having trouble on the rotation aspect, and adding other effects on this.
* I'm going to try making my own little combination of geometric shapoes using all of the aspects I've learnt through learning log 1 & 2.
(This is all from my learning log)

I had trouble with some of the Aframes tinkering code because this is what I had originally (which didn't really display amything and none of the geometric functions worked)
``` <html>
  <head>
    <script src="https://aframe.io/releases/1.7.1/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-box position="-1 0.5 -3" rotation="0 45 0" color="#4CC3D9"></a-box>
      <a-sphere position="0 1.25 -5" radius="1.25" color="#EF2D5E"></a-sphere>
      <a-cylinder position="1 0.75 -3" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
      <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
      <a-sky color="#ECECEC"></a-sky>
    </a-scene>
    <a-entity id="leftHand" hand-controls="hand: left; handModelStyle: lowPoly; color: #ffcccc"></a-entity>
<a-entity id="rightHand" hand-controls="hand: right; handModelStyle: lowPoly; color: #ffcccc"></a-entity>

</a-entity>
  </body>
</html>
```
This code was incorrect as the VR hands didn;'t display, and none of the geometric changes were applied. I got this working after reviewing Aframes code again, and watching a few youtube tutorials.
```<html>
  <head>
    <script src="https://aframe.io/releases/1.7.1/aframe.min.js"></script>
  </head>

  <body>
    <a-scene>
      <a-box position="-1 0.5 -3" rotation="0 45 0" color="#4CC3D9"></a-box>

      <a-sphere position="0 1.25 -5" radius="1.25" color="#EF2D5E"></a-sphere>

      <a-cylinder position="1 0.75 -3" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>

      <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>

      <a-sky color="#ECECEC"></a-sky>

      <!-- VR Hands -->
      <a-entity id="leftHand"
                hand-controls="hand: left; handModelStyle: lowPoly; color: #ffcccc">
      </a-entity>

      <a-entity id="rightHand"
                hand-controls="hand: right; handModelStyle: lowPoly; color: #ffcccc">
      </a-entity>

    </a-scene>
  </body>
</html>
```
[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
