<html> 
<head>
    <script src="https://aframe.io/releases/0.8.0/aframe.min.js"></script>
  </head>
  <body>
<a-assets>
<img id="sponch" src="https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/unnamed.png">
</a-assets>
<a-scene>
<a-sky color="#000000"></a-sky>
<a-entity obj-model="obj: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/vein.obj)" material="color: red;" position="0.3 0 -2"></a-entity>
<a-entity obj-model="obj: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/marrow.obj);" material= "src: unnamed.png" position=".044 0 -1.99"></a-entity>
<a-entity obj-model="obj: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/boni.obj)" material="color: white;" position="0.044 0.095 -0.9"></a-entity>
</a-scene>
  </body>
</html>
