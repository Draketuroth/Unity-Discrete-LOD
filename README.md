# A Study on Discrete LOD in Unity Game Engine

[![alt tag](https://i0.wp.com/draketuroth.files.wordpress.com/2018/03/lod2018-2-19-17h-38min.png?ssl=1&w=900)](https://vimeo.com/257578120)

A study of the built-in LOD Group component in Unity carried out by students Ludvig Arlebrink and Fredrik Linde at Blekinge Institute of Technology. This is supplementary material to the full report. 

Click the image to view the demonstration on Vimeo.

The Unity version used at the time was 2017.3.0f3 (64-bit). We use the Stanford bunny with LODs ranging from 0 to 4 for the experiment. We define five tests: LOD, Crossfade, Dither, No LOD and Empty. Where LOD, is a standard LOD test using the unity LOD group component, without any transitions. Both crossfade and dither also uses the LOD group component but with transitions enabled and set to crossfade. The no LOD does not use the LOD group component and renders the bunny on its maximum LOD. Finally, the empty test is just for reference and is a completely empty scene with a black clear color.
