<!--
Hey, thanks for using the awesome-readme-template template.  
If you have any enhancements, then fork this project and create a pull request 
or just open an issue with the label "enhancement".

Don't forget to give this project a star for additional support ;)
Maybe you can mention me or this repo in the acknowledgements too
-->
<div align="center">
  <img src="README-Assets/mob-psycho-aura-unity.gif" alt="Mob Psycho aura - Unity example GIF" width=auto height="270"/>
  <img src="README-Assets/mob-psycho-aura-anime.gif" alt="Mob Psycho aura - anime example GIF" width=auto height="270" />
  <h1>Mob Psycho Aura (Unity/Shader Graph)</h1>
</div>
  
## About

This is my attempt at recreating the aura effect from the anime Mob Psycho 100. Made with Shader Graph and Unity 2022.2.19f1.

### Details

<div align="center"> 
  <img src="README-Assets/process.png" alt="Process of creating the effect" width="800" height=auto/>
</div>
<br />

The implementation involves a mixture of the following:
- Vertex displacement to expand the aura's volume
- Creating a tileable 'spinning disk' texture to emulate the original design
- Screen space texture mapping
- Fresnel effect to soften the edges of the aura volume
- Fresnel effect to simulate reflective lighting onto the object itself
- Two-pass render to render the aura before the object in order to create an outline effect

The final result looks like this:
<div align="center"> 
  <img src="README-Assets/mob-psycho-aura-unity.gif" alt="Mob Psycho aura - Unity example GIF" width="300" height=auto/>
</div>
<br />

And for fun, I decided to make a sample cinematic with the effect applied onto Unity-chan.
<div align="center"> 
  <img src="README-Assets/unity-chan-with-aura.gif" alt="Unity-chan aura sample cinematic" width="480" height=auto/>
</div>
