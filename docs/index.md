<html> 
<head>
    <script src="https://aframe.io/releases/0.8.0/aframe.min.js"></script>
  </head>
  <body>
<a-scene>
<a-sky color="#000000"></a-sky>
<a-entity position="-.53 1.937 2">
  <a-camera>
</a-camera>
</a-entity>
<a-entity obj-model="obj: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/vr.obj); mtl: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/vr.mtl)" position="0.3 0 -.8"></a-entity>
<a-entity obj-model="obj: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/blymph.obj); mtl: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/blymph.mtl)" position="0.595 1.676 -1.54" scale=".2 .2 .2" visible="false">
<a-animation attribute="visible" begin="2500" to="true"></a-animation>
<a-animation attribute="position" begin="3000" from="0.595 1.676 -1.54" to=".566 1.577 -1.55" for="2000"></a-animation>
<a-animation attribute="position" begin="4000" from=".566 1.577 -1.55" to=".525 1.511 -1.55" for="2000"></a-animation>
<a-animation attribute="position" begin="6000" from=".525 1.511 -1.55" to=".365 1.407 -1.55" for="2000"></a-animation>
<a-animation attribute="position" begin="8000" from=".365 1.407 -1.55" to=".365 .96 -1.55" for="2000"></a-animation>
<a-animation attribute="position" begin="10000" from=".365 .96 -1.55" to=".072 .96 -1.55" for="2000"></a-animation>
<a-animation attribute="position" begin="12000" from=".072 .96 -1.55" to="-.02 .96 -1.55" for="2000"></a-animation>
<a-animation attribute="position" begin="14000" from="-.02 .96 -1.55" to="-.45 .96 -1.55" for="2000"></a-animation>
<a-animation attribute="position" begin="16000" from="-.45 .96 -1.55" to="-.53 .973 -1.55" for="1000"></a-animation>
<a-animation attribute="position" begin="17000" from="-.53 .973 -1.55" to="-.62 1.037 -1.52" for="500"></a-animation>
<a-animation attribute="position" begin="17500" from="-.62 1.037 -1.52" to="-.68 1.093 -1.52" for="500"></a-animation>
<a-animation attribute="position" begin="18000" from="-.68 1.093 -1.52" to="-.68 1.434 -1.5" for="500"></a-animation>
<a-animation attribute="position" begin="18500" from="-.68 1.434 -1.5" to="-.72 1.49 -1.5" for="500"></a-animation>
<a-animation attribute="position" begin="19000" from="-.72 1.49 -1.5" to="-.7 2.173 -1.58" for="500"></a-animation>
<a-animation attribute="position" begin="19500" from="-.7 2.173 -1.58" to="-.7 2.003 -1.58" for="500"></a-animation>
</a-entity>
<a-entity obj-model="obj: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/pathogen.obj); mtl: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/pathogen.mtl)" scale=".05 .05 .05" position="-1.59 1.889 -1.3" visible="false">
<a-animation attribute="visible" begin="1000" to="true"></a-animation>
<a-animation attribute="position" begin="1500" from="-1.59 1.889 -1.3" to="-.73 2.567 -1.3" for="1000"></a-animation>    
</a-entity>
<a-entity obj-model="obj: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/inflamation.obj); mtl: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/inflamation.mtl)" position="0.414 -.02 -.74">
<a-animation attribute="scale" begin="10000" from="1 1 1" to="1.1 1.1 1.1"></a-animation>
</a-entity>
<a-text></a-text>
</a-scene>
  </body>
</html> 
