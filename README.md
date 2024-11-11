<img border="2" src="textures/images/fsim_240824.jpg" style="float: center">

<h2>My Aviation Resources Repository (rev. 11 Nov 2024)</h2>
<p>
This repository contains aviation-related resources designed to simulate 3D flight in three.js.
</p><p>
This includes a flight simulation module (FlightW3), an ocean simulation module (Ocean3 through Ocean 4t2), and a fully animated WWII fighter airplane (FM2).
</p><p>
The repository includes several sample programs that show how to use these resources.
</p><ul>
	<li>The fdem programs show a basic airplane flying over the ocean and land (using the applicable modules).</li>
	<li>The fmod programs show detailed airplane models flying over an animated ocean.</li>
	<li>The fsim programs are basic flight simulation which use the flight, grid and ocean simulation modules.</li>
</ul><p>
You can run these programs and load these resources using the following syntax:
<pre>https://philcrowther.github.io/Aviation/file_name</pre>

For example:<br>
https://philcrowther.github.io/Aviation/fmod_FM2_ocean_gpu_gh.html<br>
https://philcrowther.github.io/Aviation/fsim_FM2_ocean_gpu_gh.html

NOTE:
<p>
When we started this Repo a few months ago, you could use NodeMaterials with WebGL2. This ended with r165. Effective with r166, you could use NodeMatgerials only with WebGPU. And r167 made significant changes to the three.js WebGPU modules. Smaller changes were made by subsequent versions through r170. The modules that work with WebGPU and Node materials are AnimFM2, FlightW4a, GrdMap3a. GrdWtr4a and Ocean4t2. The modules that should work with the current WebGL2 and standard materials are: AnimFM2, FlightW3, GrdMap3a, GrdWtr3 and Ocean3. 
</p><p>
The remaining files are archive files which are retained to avoid breaking programs written using older versions of three.js. The AnimFM2, FlightW3 and GrdMap3 modules should work with older versions of WebGL2 and WebGPU. The Ocean3 and GrdWtr3 modules work with WebGL2 and standard materials. The Ocean3 and GrdWtr3N modules work with NodeMaterials and WebGL2 up to r165. The Ocean4 and GrdWtr4 modules work with NodMaterials and WebGPU up to r166. The GrdWtr4a, Ocean4a and Ocean4t modules work with WebGPU and NodeMaterials for r167 to r169. We recommend that you upgrade to the latest versions of these modules.
</p><p>
Special thanks to Attila Schroeder for his encouragement and assistance in converting everything to NodeMaterials and WebGPU. And to all the volunteers at three.js who took on the daunting task of modifying three.js to work with NodeMaterials and WebGPU.
</p>
