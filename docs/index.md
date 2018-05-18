<html> 
<head>
    <script src="https://aframe.io/releases/0.8.0/aframe.min.js"></script>
  </head>
  <body>
<a-scene>
<a-sky color="#000000"></a-sky>
<a-entity obj-model="obj: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/vein.obj)" material="color: red;" position="0.3 0 -2"></a-entity>
<a-entity obj-model="obj: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/marrow.obj);" material= "src: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/docs/unnamed.png)" position=".044 0 -1.99"></a-entity>
<a-entity obj-model="obj: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/boni.obj)" material="color: white;" position="0.044 0.095 -0.9"></a-entity>
<a-sphere color="yellow" radius=".03" position=".28 2 -1.35"><a-text value="b lymphocyte" color="black" position="-.09 -.01 .07" scale=".15 .15 1"></a-text></a-sphere> 
<a-text value="bone marrow" color="black" position="0.15 1.5 -1.35" scale=".23 .23 1"></a-text>
<a-text value="blood vessel =>" color="black" position="-.25 1.5 -1.35" scale=".2 .2 1"></a-text>
<a-text value="bone" color="black" position="0 1.2 -.98" scale=".2 .2 1"></a-text>
</a-scene>
  </body>
</html>
