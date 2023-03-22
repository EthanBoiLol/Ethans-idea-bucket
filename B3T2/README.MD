# B3T2

## What is B3T2?

B3T2, (name subject to change) is a fork of Blender that translate a 3D scene into a 2D dimentional scene in real time. Unlike existing shaders like cel, this engine will be comparable to hand-drawn and digital 2D animation, rather than flattening shaders to make an illusion of 2D, but can still easily tell that it's 3D.


here are mockup examples of the idea:

![3D -> 2D example 1](https://github.com/EthanBoiLol/Ethans-idea-bucket/blob/main/B3T2/Res/Example1.jpg)


![3D -> 2D example 2](https://github.com/EthanBoiLol/Ethans-idea-bucket/blob/main/B3T2/Res/example2.png)

## Why a fork?

The main reason why I'm planning on a fork instead of an addon is because:

- More freedom to extend and include additional tweaks to make B3T2
- Remove unwanted content to reduce project size
- (possible) rework on the .blend system
- additional programming languages besides python may or may not be included


## What are planned features?

- (100%) Digital 2D renderer
- (100%) 2D format support
- (70%) convert cartoon character/asthetic -> blender model/asthetic config (useful for fan-projects)
- (70%) better AI voice (also useful for fan-projects)
- (50%) revamped layout
- (20%) new project format exclusive to B3T2
- (0%) your mom

## how will this be done?

### Digital 2D renderer

This can be done using a custom renderer, for now, it's called "2D renderer" however this name is subject to change

this renderer will utilize multiple techs, such as shading and AI, to make a rendering algorithm that uses simulations and Math/AI to utilize lighting, shading, and textures, and then further effects set by the Asthetic Config will modify both the renderer and the after effects.

a "Asthetic config" is a very long, JSON-like, config that includes int, float, and many other datasets that when modify, will change how the processing 
works to set an Asthetic to the scene. For example, one config can make the scene look like a modern 2020's children cartoon, while another config may make the scene look like an 80's anime.

The Asthetic config is currently planned to be modified using a text editor, however custom GUI like a panel or a node-based system isn't out of the question. It is also planned to have a saving feature to keep your own or share it with others as templates.

### 2D format support

(rest is WIP for tomorrow)
