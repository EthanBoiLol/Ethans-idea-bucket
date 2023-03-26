# B3T2

## What is B3T2?

B3T2, (name subject to change) is a fork of Blender that translate a 3D scene into a 2D dimentional scene in real time. Unlike existing shaders like cel, this engine will be comparable to hand-drawn and digital 2D animation, rather than flattening shaders to make an illusion of 2D, but can still easily tell that it's 3D.


here are mockup examples of the idea:

![3D -> 2D example 1](https://github.com/EthanBoiLol/Ethans-idea-bucket/blob/main/B3T2/Res/Example1.jpg)


![3D -> 2D example 2](https://github.com/EthanBoiLol/Ethans-idea-bucket/blob/main/B3T2/Res/example2.png)

## Why a fork?

The main reason why I'm planning on a fork instead of an addon is because:

- More freedom to extend and include additional tweaks to make B3T2 better
- Remove unwanted content to reduce project size
- (possible) rework on the .blend system
- additional programming languages besides python may or may not be included


## What are planned features?

- (100%) Digital 2D renderer
- (100%) 2D format import support
- (70%) convert cartoon character/asthetic images -> blender model/asthetic config (useful for fan-projects)
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
This software is made with 3D and 2D artists in mind. This means that some artists may want to import 2D animation from other software into this engine. This can easily be done by simply adding built-in addons that allows users to easily insert 2D project animations

once imported, the animation by default will be a 2D plane object, however can be configured to stick as a layer for the scene. Furthermore, an idea is to add 'materials' to certain colors or lines in order to make realistic lighting effects.

### convert Cartoon image --> Scene

While there isn't plans to convert all poses and 2D scenes, we do have some plans to add an astethic and models into B3T2.

#### Astethic --> B3T2

This may be done by using an AI to detect patterns of an image (such as lighting and lines) and list all details (like is it anime for example)then, compare them from all data feed into the dataset.

The dataset might be an input like a 'cartoon' or 'anime' and the output may contain the values needed

![Astethic -> B3T2](https://github.com/EthanBoiLol/Ethans-idea-bucket/blob/main/B3T2/Res/ast_to_2d.jpg)

#### Model --> B3T2

for fan projects, recreating characters from scratch using reference images may be time-consuming, especially when working with the envornment, which is why our idea is to also include a model support

this may work by taking a 'turnaround' image and using AI to check the astethic, then, after that, any color that it detects is a constant change will be added to the model, other stuff like bumps, height, and width will also be done by the AI based on the turnaround

the downside is that while this may look good for flat, 2D astethic, this might not look good for lighting or converting it into a normal 3D blender models, and thus may have to be manually edited. Additional manual editing such as placements of eyes, mouth, body, etc will also be availiable for complex models.

![Model -> B3T2](https://github.com/EthanBoiLol/Ethans-idea-bucket/blob/main/B3T2/Res/model-to-3d.jpg)

### better AI voice
Also made with fan projects in mind, this AI will convert your voice recordings with that to the data you feed (such as spongebob's voice)

to ensure that it doesn't sound robot-like, we will use a function called masking, this will take your voice and changing the voice by using stuff like pitch. If it sounds robot-like, the AI will attempt to fix those issues until the voice nearly match that of the original voice.

Unfortunately, due to this, unlike other AI voice where it takes seconds or minutes, this may take hours depending on the AI's power


### revamped layout
Since 2D animatiors are in mind, we may cange the layout to make it easier and less complex. Such as reducing the tabs and reordinizing buttons.

### new project format exclusive to B3T2
while .blend files may be fine for most, in case of huge modifications we may change the project file to something else

## Why can't I do this project right now

I can't start it right now because:
- I still need to get used to blender and how it works
- this 100% requires a group effort, and I have no group
- I am not an expert on deep-learning and AI yet

I expect me to work on this project in a year or two, however things can easily change.
