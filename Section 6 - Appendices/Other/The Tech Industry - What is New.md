
#### Contents
- [[#Introduction|Introduction]]
- [[#Recent Developments|Recent Developments]]
	- [[#Recent Developments#Smarter Software Creation|Smarter Software Creation]]
	- [[#Recent Developments#Chip Speed|Chip Speed]]
	- [[#Recent Developments#Open Source Creation|Open Source Creation]]
	- [[#Recent Developments#Generative Images|Generative Images]]
	- [[#Recent Developments#ML-Assisted Photogrammetry|ML-Assisted Photogrammetry]]
	- [[#Recent Developments#Raytracing|Raytracing]]
	- [[#Recent Developments#3D on the Web|3D on the Web]]
	- [[#Recent Developments#VR Getting Brighter in HDR|VR Getting Brighter in HDR]]
	- [[#Recent Developments#Easier Performance Capture|Easier Performance Capture]]
	- [[#Recent Developments#Volumetric Video - Hardware and Software|Volumetric Video - Hardware and Software]]
	- [[#Recent Developments#Audio Virtualisation|Audio Virtualisation]]
	- [[#Recent Developments#LiDAR|LiDAR]]
	- [[#Recent Developments#Digital Twins|Digital Twins]]
	- [[#Recent Developments#MCP Technology|MCP Technology]]
	- [[#Recent Developments#Advanced Haptics?|Advanced Haptics?]]
- [[#Conclusion|Conclusion]]
	- [[#Conclusion#*A Note on AI Concerns*|*A Note on AI Concerns*]]
	- [[#Conclusion#References|References]]


---

## Introduction

Technology isn't standing still, and while not every new gadget or line of code is relevant to us, some shifts offer genuinely exciting possibilities for how we create in theatre. Staying aware isn't about chasing trends, but about spotting opportunities – new ways to visualize, collaborate, or enhance our craft using tools that are becoming faster, smarter, and sometimes, surprisingly accessible. Let's look at a few areas worth keeping an eye on:

## Recent Developments
### Smarter Software Creation

How software gets made is changing, potentially speeding things up and making it easier for new players, and creative ideas to take centre stage.

**Agent Assisted Coding:** From AI suggesting code snippets (like ChatGPT, Manus, Github Copilot) to potentially handling more complex tasks based on plain English prompts, development could become faster.  

>“Code is just a tool; the real skill is thinking clearly,” - Naval Ravikant

### Chip Speed

Computers just keep getting faster. More powerful graphics cards (GPUs from NVIDIA and AMD) and specialized chips mean complex real-time rendering, simulations, and AI tasks that once required whole render farms, are becoming feasible on a single workstation.

### Open Source Creation

Powerful tools are becoming more accessible. **Blender**, the free, open-source 3D suite, has evolved dramatically. It now genuinely rivals expensive commercial software (like Maya or 3ds Max) for modelling, animation, rendering, and more [^1]. 

### Generative Images

AI image generation (Midjourney, Stable Diffusion, launched ~2022) has captured headlines and courted controversy [^2].

- **Visual Brainstorming:** For designers, these tools offer an incredibly fast way to generate mood boards, concept variations, or texture ideas from simple prompts. 
- **Inspiration, Not Replacement:** There has been no indication that AI agents rival the creativity or discernment of creatives. There have been some benefits to it automating mundane tasks. _(See AI Note below)_.

### ML-Assisted Photogrammetry

Platforms such as Artec 3D[^14]are building AI-assisted options on top of traditional photogrammetry workflows such as Agisoft Metashape.

### Raytracing

Simulating light accurately would be the holy grail of lighting previz. Recent developments in this technology

Raytracing offers vastly more realistic calculation of reflections, soft shadows, and complex light interactions than older methods [^3]. Thanks to modern GPUs, this is becoming usable within game engines (i.e. Lumen, MegaLights). With the right specialisation, tuning and testing, lighting designers may find they can test lighting digitally.

### 3D on the Web

Sharing interactive 3D models as easily as sending a web link.

- **Interactive Web 3D:** Three.js is a key technology enabling complex 3D graphics directly in web browsers [^4].
- **Sharing Potential:** This unlicks the development of new web-based viewers for sharing designs with collaborators, interactive costume or prop showcases, or even new forms of digital outreach, all without needing special software installs.

### VR Getting Brighter in HDR

New headsets like the Bigscreen 2 enable HDR, with significantly brighter highights, and darker shadows.

High Dynamic Range displays, now appearing in newer VR headsets (like Apple's Vision Pro, 2024, or high-end Varjo models) [^5].

With the right tools, this could finally make VR more accurate and true-to-life: accurately perceive the intensity and feel of stage lighting in a virtual environment.

### Easier Performance Capture

Capturing performer movement without complex suits or studios is becoming reality.

- **Just Use Cameras:** AI systems like Move.ai (founded 2019) or Rokoko Vision or Plask[^15], use software to analyze video from multiple standard cameras, extracting 3D motion data [^6] [^7].
- **Accessible Animation & Interaction:** This makes performance capture much more affordable for creating realistic digital doubles for previs, animating virtual characters, or potentially driving live interactive elements based on performer movement.

### Volumetric Video - Hardware and Software

Performance have begun to be captured in full 3D. This is powered by ai-accelerated point clouds.

- **Theatre Potential:** Movement or scenes can be captured in an immersive way, with more nuances being communicated for remote viewing.  Research projects like LongVolCap are pushing this to hours-long captures - incredibly impressive. [^8]
- The University of Bremen Lab, which we cite in our Case Studies, have released a report using similar technology to render volumetric video using pont clouds. [^9]
- **Viewing Holograms:** Devices like the Looking Glass display 3D objects in real life without headsets.[^10] Other hologram technology is in development.[^11]


### Audio Virtualisation

Products are consistently emerging in market that are seeing positive use by mix engineers, such as

- RealPhones
- Steven Slate Audio VSX
- Sonarworks
- Waves Nx

These devices use calibrated EQ curves and reverb modelling, to simulate physical speakers in physical rooms. Waves Nx for one, can be used with 3DOF head tracking devices to simulate this further. This is primed for a wave of mass adoption for live audio once cross compatibility has been established, with live proprietary tech such as d&b Soundscape, Dolby Atmos, or possibly Dante more generally.


### LiDAR 

For architects seeking affordable professional LiDAR tools to create 3D scans for raytraced assets, we have seen greater accessibility in recent years, delivering quality point clouds and textures.

**LiDAR-Equipped Smartphones** (e.g., iPhone 14 Pro) cost ~£0 if owned, or ~£400 for a used device. Apps like Polycam use built-in LiDAR for ~1-5cm accurate scans of rooms or objects, exporting OBJ/GLTF for raytracing in Blender. Beginner-friendly but needs texture cleanup.

**FJD Trion P1**, a handheld scanner, costs ~£2,400. With 0.3-1cm accuracy, it captures dense point clouds for buildings, exporting to Enscape for raytracing. It’s user-friendly for mid-scale projects.

**RPLIDAR A1** (~£80-£120) suits DIY scans with ~1cm accuracy, needing technical setup for Blender.

### Digital Twins
Global trends show the rise of the Digital Twin across industries. Check out this article exploring the impact of Digital Twins for lighting.[^16]

### MCP Technology
AI Copilots will help engineers operate their software. Cloud interoperability and huge potential will be unlocked with MCPs such as MecAgent[^17]

### Advanced Haptics?
Ongoing research an prototyping is occurring with VR haptic technology. Mass production or productisation has not happened yet[^13]


---

## Conclusion

This whirlwind tour highlights just some current tech shifts. 

By understanding what's becoming possible, we are better positioned to identify tools that could genuinely enhance a collaborative, creative process: asking better questions, make more informed choices, and hopefully, actively participating in guiding how technology serves the unique needs and enduring values of live performance.

### *A Note on AI Concerns*

The rapid rise of AI tools, especially image generation, has sparked important debates about copyright, ethics, and artistic integrity. The author believes that education is key, and that these tools can be empowering in the right hands.



[1. Rules & Conventions of Modern Theatre Production](1.%20Rules%20&%20Conventions%20of%20Modern%20Theatre%20Production.md)


---

### References 

[^1]: Blender Foundation. [https://www.blender.org/](https://www.blender.org/) 
[^2]: Examples: Midjourney [https://www.midjourney.com/](https://www.midjourney.com/), Stability AI (Stable Diffusion) [https://stability.ai/](https://stability.ai/) 
[^3]: NVIDIA RTX Technology. [https://www.nvidia.com/en-us/geforce/rtx/](https://www.nvidia.com/en-us/geforce/rtx/) 
[^4]: Three.js library. [https://threejs.org/](https://threejs.org/) 
[^5]: Information on specific HDR VR headsets from manufacturer websites or tech reviews (e.g., Varjo, Apple Vision Pro). 
[^6]: Move AI. [https://www.move.ai/](https://www.move.ai/) 
[^7]: Rokoko (specifically Rokoko Vision). [https://www.rokoko.com/products/vision](https://www.rokoko.com/products/vision)

[^8]: LongVolCap, featuring video demonstrations of 3d volumetric video.  https://zju3dv.github.io/longvolcap/

[^9]: Further Reading: BlendPCR: Seamless and Efficient Rendering of Dynamic Point Clouds captured by Multiple RGB-D Cameras on [UOB main website](https://cgvr.cs.uni-bremen.de/publications/) or the [project on GitHub](https://github.com/muehlenb/blendpcr)


[^10]: Looking Glass Factory https://lookingglassfactory.com

[^11]: Scientists grab 3D holograms mid-air like science fiction movies in a world-first https://interestingengineering.com/science/holograms-you-can-touch-created?group=test_b

[^12]: General reference to tech news covering GPU/NPU advancements (e.g., NVIDIA GTC keynotes, AMD announcements). 

[^13]: Academic blog https://blogs.ed.ac.uk/smartsense/2025/01/28/touching-the-future-exploring-haptics-and-multisensory-experiences-in-virtual-reality/
	Product https://nextbridge.com/tactile-virtual-reality-technology/
	Article https://biologyinsights.com/phantom-touch-vr-insights-on-tactile-illusions/
	Blog article https://news.northwestern.edu/stories/2025/03/feeling-the-future-new-wearable-device-mimics-the-complexity-of-human-touch/

[^14]: https://www.artec3d.com/3d-software/artec-studio/photogrammetry

[^15]: https://plask.ai/en-US/pricing

[^16]: https://www.lighting.philips.co.uk/oem-emea/stay-connected/digital-twins

[^17]:  https://mecagent.com
