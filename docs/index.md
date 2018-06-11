<html> 
<head>
    <script src="https://aframe.io/releases/0.8.0/aframe.min.js"></script>
  </head>
  <body>
<a-scene>
<a-sky color="#bfbfbf"></a-sky> 
<a-entity position="-.81 1.81 1.237">
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
<a-animation attribute="visible" begin="27000" to="false"></a-animation>
</a-entity>
<!-- Pathogen 1 -->
<a-entity obj-model="obj: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/pathogen.obj); mtl: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/pathogen.mtl)" scale=".05 .05 .05" position="-1.59 1.889 -1.25" visible="false">
<a-animation attribute="visible" begin="500" to="true"></a-animation>
<a-animation attribute="position" begin="4000" from="-1.59 1.889 -1.25" to="-.73 2.567 -1.25" for="1000"></a-animation>
<a-animation attribute="visible" begin="15000" to="false"></a-animation>
</a-entity>
<!-- Pathogen 2 -->
<a-entity obj-model="obj: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/pathogen.obj); mtl: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/pathogen.mtl)" scale=".05 .05 .05" position="-1.59 2.07 -1.25" visible="false"> 
<a-animation attribute="visible" begin="500" to="true"></a-animation>
<a-animation attribute="position" begin="4000" from="-1.59 1.889 -1.25" to="-.74 2.863 -1.25" for="1000"></a-animation>
<a-animation attribute="visible" begin="40000" to="false"></a-animation>
</a-entity>
<a-entity obj-model="obj: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/infresp.obj); mtl: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/infresp.mtl)" position="0.414 -.02 -.74">
<a-animation attribute="scale" begin="5500" from="1 1 1" to="1.1 1.1 1.1"></a-animation>
</a-entity>
<a-text value="skin with a cut" position="-1.07 1.897 -1.13" color="#0000ff" rotation="0 0 -90"></a-text>
<a-text value="inflammatory response" color="#0000ff" visible="false" position="-1.46 3.541 -1.33" scale=".5 .5 .5">
 <a-animation attribute="visible" begin="5500" to="true"></a-animation>   
  <a-animation attribute="visible" begin="8000" to="false"></a-animation> 
 </a-text>
<a-text value="macrophage processed antigen, alerting t cell" color="#0000ff" visible="false" position="-1.85 3.541 -1.33" scale=".5 .5 .5">
<a-animation attribute="visible" begin="14500" to="true"></a-animation>
<a-animation attribute="visible" begin="21000" to="false"></a-animation> 
</a-text>
<a-cone color="#000000" rotation="180 0 0" scale=".04 .09 .04" position="-.84 2.25 -1.19" visible="false">
<a-animation attribute="visible" begin="15500" to="true"></a-animation>  
<a-animation attribute="visible" begin="27000" to="false"></a-animation>
</a-cone>
<a-text value="antigen" position="-.91 2.25 -1.08" color="#ffff00" scale=".25 .25 .25" visible="false">
<a-animation attribute="visible" begin="15500" to="true"></a-animation>  
<a-animation attribute="visible" begin="27000" to="false"></a-animation>    
</a-text>
<a-entity obj-model="obj: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/htc.obj); mtl: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/htc.mtl)" position="-.71 -.021 -1.19" scale=".07 .07 .07" visible="false">
<a-animation attribute="visible" begin="15500" to="true"></a-animation>
<a-animation attribute="position" begin="16000" from="-.71 -.021 -1.37" to="-.71 1 -1.19" for="4000"></a-animation>
<a-animation attribute="position" begin="20000" from="-.71 1 -1.19" to="-.76 1.175 -1.19" for="500"></a-animation>
<a-animation attribute="position" begin="20500" from="-.76 1.175 -1.19" to="-.76 1.671 -1.19" for="2000"></a-animation>
<a-animation attribute="position" begin="22500" from="-.76 1.671 -1.19" to="-.81 1.801 -1.19" for="500"></a-animation>
<a-animation attribute="position" begin="23000" from="-.81 1.801 -1.19" to="-.83 1.929 -1.19" for="2000"></a-animation>
<a-animation attribute="visible" begin="27000" to="false"></a-animation>
</a-entity>
<a-entity obj-model="obj: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/blymph.obj); mtl: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/blymph.mtl)" position="-.59 -.02 -1.5" scale=".2 .2 .2" visible="false">
<a-animation attribute="visible" begin="27500" to="true"></a-animation>
<a-animation attribute="position" begin="29000" from="-.59 -.0763 -1.37" to="-.59 .86 -1.5" for="4000"></a-animation>
<a-animation attribute="position" begin="33000" from="-.59 .86 -1.5" to="-.65 .984 -1.5" for="500"></a-animation>
<a-animation attribute="position" begin="33500" from="-.65 .984 -1.5" to="-.64 1.514 -1.5" for="2000"></a-animation>
<a-animation attribute="position" begin="35500" from="-.65 1.514 -1.5" to="-.71 1.602 -1.5" for="500"></a-animation>
<a-animation attribute="position" begin="36000" from="-.71 1.602 -1.5" to="-.7 2.476 -1.5" for="2000"></a-animation>
<a-animation attribute="visible" begin="40000" to="false"></a-animation>
</a-entity>
<!-- top plasma -->
<a-entity obj-model="obj: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/plasmacell.obj); mtl: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/plasmacell.mtl)" position="-.7 2.476 -1.17" scale=".025 .025 .025" visible="false">
<a-animation attribute="visible" begin="37500" to="true"></a-animation>
<a-animation attribute="position" begin="38500" from="-.8 2.476 -1.17"  to="-.81 2.704 -1.17" for="1000"></a-animation>
<a-animation attribute="visible" begin="40000" to="false"></a-animation>
</a-entity> 
<!-- bottom plasma -->
<a-entity obj-model="obj: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/plasmacell.obj); mtl: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/plasmacell.mtl)" position="-.8 2.502 -1.17" scale=".025 .025 .025" visible="false">
<a-animation attribute="visible" begin="37500" to="true"></a-animation>
<a-animation attribute="position" begin="38500" from="-.8 2.502 -1.17" to="-.81 2.650 -1.17" for="200"></a-animation>
<a-animation attribute="visible" begin="40000" to="false"></a-animation>
</a-entity>
<a-entity obj-model="obj: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/memorycell.obj); mtl: url(https://raw.githubusercontent.com/immunesystemvr/Immune-System-VR/master/memorycell.mtl)" position="-.7 2.476 -1.5" scale=".2 .2 .2" visible="false">
<a-animation attribute="visible" begin="40000" to="true"></a-animation>
<a-animation attribute="position" begin="41000" from="-.7 2.476 -1.5" to="-.7 1.602 -1.5" for="2000"></a-animation>
<a-animation attribute="position" begin="43000" from="-.7 1.602 -1.5" to="-.64 1.514 -1.5" for="500"></a-animation>
<a-animation attribute="position" begin="43500" from="-.64 1.514 -1.5" to="-.64 .955 -1.5" for="500"></a-animation>
<a-animation attribute="position" begin="44000" from="-.64 .955 -1.5" to="-.59 .895 -1.5" for="500"></a-animation>
<a-animation attribute="position" begin="44500" from="-.59 .895 -1.5" to="-.59 -.18 -1.5" for="500"></a-animation>
<a-animation attribute="visible" begin="45000" to="false"></a-animation>
</a-entity>
<a-text value="b cell notified, goes to site of pathogen" color="#0000ff" visible="false" position="-1.85 3.541 -1.33" scale=".5 .5 .5">
<a-animation attribute="visible" begin="28000" to="true"></a-animation>
<a-animation attribute="visible" begin="31000" to="false"></a-animation> 
</a-text>
<a-text value="b cell replicates itself and creates plasma cells to kill the pathogen" color="#0000ff" visible="false" position="-1.85 3.541 -1.33" scale=".5 .5 .5">
<a-animation attribute="visible" begin="38000" to="true"></a-animation>
<a-animation attribute="visible" begin="40000" to="false"></a-animation> 
</a-text>
<a-text value="pathogen killed, memory cells stay in bloodstream, to remove pathogen quickly when exposed to it again" color="#0000ff" visible="false" position="-1.85 3.541 -1.33" scale=".5 .5 .5">
<a-animation attribute="visible" begin="42000" to="true"></a-animation>
<a-animation attribute="visible" begin="52000" to="false"></a-animation> 
</a-text>
</a-sky> 
</a-scene>
  </body>
</html>
