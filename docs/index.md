<html> 
<head>
    <script src="https://aframe.io/releases/0.8.0/aframe.min.js"></script>
  </head>
  <body>
<a-scene>
<a-sky color="#000000"></a-sky> 
<a-entity position="-.76 1.68 1.191">
  <a-camera>
</a-camera>
</a-entity>
<a-entity obj-model="obj: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/vr.obj); mtl: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/vr.mtl)" position="0.3 0 -.8"></a-entity>
<a-entity obj-model="obj: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/macrophage.obj); mtl: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/macrophage.mtl)" position="-.71 -.021 -1.19" scale=".05 .05 .05" visible="false">
<a-animation attribute="visible" begin="6500" to="true"></a-animation>
<a-animation attribute="position" begin="7000" from="-.71 -.021 -1.37" to="-.71 1 -1.19" for="4000"></a-animation>
<a-animation attribute="position" begin="11000" from="-.71 1 -1.19" to="-.76 1.175 -1.19" for="500"></a-animation>
<a-animation attribute="position" begin="11500" from="-.76 1.175 -1.19" to="-.76 1.671 -1.19" for="2000"></a-animation>
<a-animation attribute="position" begin="13500" from="-.76 1.671 -1.19" to="-.81 1.801 -1.19" for="500"></a-animation>
<a-animation attribute="position" begin="14000" from="-.81 1.801 -1.19" to="-.81 2.39 -1.19" for="2000"></a-animation>
</a-entity>
<a-entity obj-model="obj: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/pathogen.obj); mtl: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/pathogen.mtl)" scale=".05 .05 .05" position="-1.59 1.889 -1.3" visible="false">
<a-animation attribute="visible" begin="500" to="true"></a-animation>
<a-animation attribute="position" begin="4000" from="-1.59 1.889 -1.3" to="-.73 2.567 -1.3" for="1000"></a-animation>    
</a-entity>
<a-entity obj-model="obj: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/infresp.obj); mtl: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/infresp.mtl)" position="0.414 -.02 -.74">
<a-animation attribute="scale" begin="5000" from="1 1 1" to="1.1 1.1 1.1"></a-animation>
</a-entity>
<a-text value="skin with a cut" position="-1.07 1.897 -1.13" color="#0000ff" rotation="0 0 -90"></a-text>
<a-text value="inflammatory response" color="#0000ff" visible="false" position="-1.85 3.541 -1.33">
 <a-animation attribute="visible" begin="5500" to="true"></a-animation>   
  <a-animation attribute="visible" begin="8000" to="false"></a-animation> 
 </a-text>
<a-text value="macrophage processed antigen, alerting t cell" color="#0000ff" visible="false" position="-3.13 3.541 -1.33">
<a-animation attribute="visible" begin="14500" to="true"></a-animation></a-text>
<a-cone color="#E7589B"></a-cone>
</a-scene>
  </body>
</html>
