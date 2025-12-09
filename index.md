---
layout: default
---

# Hi I'm Anton Hörig

I became fascinated with the creative possibilities of code early on. During my bachelor's degree in Media Computer Science, I learned a lot about 3D rendering, graphics programming, and their use in artistic contexts from theater stages and museums to video games. This is knowledge I continue to build on and apply in personal projects and experiments.

Key skills: Computer Graphics • C++ • OpenGL • Unity • Unreal • Godot • problem solving • teamwork

# Featured Projects

## [GPU Texture Painter](https://github.com/maantho/gpu-texture-painter)

<div style="display:flex; width:100%; gap:5px; flex-wrap:wrap;">
    <a href="https://github.com/maantho/gpu-texture-painter"><img src="media/TexPaint-Icon.png" height="150"></a>
    <a href="https://github.com/maantho/gpu-texture-painter"><img src="media/TexPaint-Preview.gif" height="150"></a>
    <a href="https://github.com/maantho/gpu-texture-painter"><img src="media/TexPaint-UV.png" height="150"></a>
</div>

A plugin for the Godot-Engine, that allows runtime, scene-wide texture painting on the GPU. 
Achieves an accurate brush/spray effect by painting individual atlas texels. 
Those coordinates are gathered by rendering the scene in a second pass to an offline framebuffer with the UV coordinates as the color. The actual coloring of the atlas is handled by a custom compute shader.
With this technique quality and performance is improved significantly compared to methods utilizing the physics engine.

Skills: 3D Rendering • Tool Programming • Godot

## [Multi-Projector Calibration & Projection Mapping](https://github.com/maantho/InACTually-Engine)

<div style="display:flex; width:100%; gap:5px; flex-wrap:wrap;">
    <a href="https://github.com/maantho/InACTually-Engine"><img src="media/ProjCalib-Outside.png" height="150"></a>
    <a href="https://github.com/maantho/InACTually-Engine"><img src="media/ProjCalib-Inside.png" height="150"></a>
    <a href="https://github.com/maantho/InACTually-Engine"><img src="media/ProjCalib-Result.png" height="150"></a>
</div>

Bachelors thesis with the goal to find a projector calibration method, that can be used for dynamic spatial projection mapping in a wide variety of artistic contexts. Out of existing methods a novel multi-projector calibration method was developed to support projection-mapping onto arbitrary dynamic surfaces. This is achieved in a user-friendly way, utilizing a mixed reality headset. It mitigates restriction on the surface and calibration targets, that are common with other projector calibration methods.
It was merged into InACTually.

Skills: Computer Graphics • C++ • OpenGL • WebXR 

## [Entry to Mini Jame Gam #36](https://github.com/maantho/running-makes-thirsty)

<div style="display:flex; width:100%; gap:5px; flex-wrap:wrap;">
    <a href="https://github.com/maantho/running-makes-thirsty"><img src="media/Jam-Cover.png" height="150"></a>
    <a href="https://github.com/maantho/running-makes-thirsty"><img src="media/Jam-Gameplay.gif" height="150"></a>
</div>

The theme was "Speedrun" and the special object "Bag". It features a fun mechanic, where the player has to produce enough water to hydrate a marathon runner and chase the highscore by picking and combining fruits, kitchen tools and bottles from the environment.

Skills: rapid prototyping • problem solving • Godot
