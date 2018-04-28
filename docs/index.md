<html> 
<head>
    <script src="https://aframe.io/releases/0.8.0/aframe.min.js"></script>
  </head>
  <body>
<a-scene>
<a-sky color="#000000"></a-sky>
 <a-image src="https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/Screen%20Shot%202018-04-27%20at%205.39.48%20PM.png" width="5" height="1" position="0 1.7 -2"></a-image>
<a-entity position="0 2.2 4">
    <a-entity camera look-controls wasd-controls>
      <a-entity position="0 0 -3"
                geometry="primitive: ring; radiusInner: 0.1; radiusOuter: 0.15;"
                material="color: cyan; shader: flat"
                cursor="maxDistance: 30; fuse: true">
        <a-animation begin="click" easing="ease-in" attribute="scale"
             fill="forwards" from="0.2 0.2 0.2" to="1 1 1" dur="150"></a-animation>
        <a-animation begin="fusing" easing="ease-in" attribute="scale"
             fill="backwards" from="1 1 1" to="0.2 0.2 0.2" dur="1500"></a-animation>
      </a-entity>
    </a-entity>
  </a-entity>
</a-scene>
  </body>
</html>
