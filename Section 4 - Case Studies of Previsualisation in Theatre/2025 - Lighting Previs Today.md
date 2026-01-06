Instead of confiding this data within an appendix to be referred to in passing, the state of Lighting Previs is being treated as a Case Study due to it being significantly advanced compared to other areas.

Leading previs solutions for stage lighting are propagating throughout the industry, with asset libraries for different fixtures and integrations with existing hardware. Vendor lock is present with many parallel ecosystems, likely due to existing value models.

Regardless, lighting designers and their teams can now simulate complex lighting setups, program cues, getting a first look at rigs and setups within virtual environments before stepping into the physical venue, saving time and resources if used effectively.

---

#### Contents
- [[#Introduction|Introduction]]
- [[#Terms|Terms]]
	- [[#Terms#Digital Control Protocols|Digital Control Protocols]]
	- [[#Terms#Show Design File Standards|Show Design File Standards]]
	- [[#Terms#3D File Standards|3D File Standards]]
- [[#The Lighting Previs Landscape|The Lighting Previs Landscape]]
	- [[#The Lighting Previs Landscape#WYSIWYG|WYSIWYG]]
	- [[#The Lighting Previs Landscape#Vectorworks Spotlight and Vision|Vectorworks Spotlight and Vision]]
	- [[#The Lighting Previs Landscape#Capture|Capture]]
	- [[#The Lighting Previs Landscape#Depence2|Depence2]]
	- [[#The Lighting Previs Landscape#Console-Specific Tools|Console-Specific Tools]]
- [[#Analysis|Analysis]]
	- [[#Analysis#Digital Twins terminology|Digital Twins terminology]]
	- [[#Analysis#Addressing Pain Points|Addressing Pain Points]]
		- [[#Addressing Pain Points#Late-stage integration|Late-stage integration]]
		- [[#Addressing Pain Points#Managing Complexity|Managing Complexity]]
		- [[#Addressing Pain Points#Communication & Coordination|Communication & Coordination]]
		- [[#Addressing Pain Points#Resource Scarcity|Resource Scarcity]]
- [[#Conclusion|Conclusion]]



---

## Introduction

Established platforms like WYSIWYG and Vectorworks Spotlight continue to be industry mainstays, while newer competitors such as Capture and Depence2 are introducing alternative approaches and challenging the status quo. 

These platforms indicate in interest for lighting designers to engage in previsualisation with digital asset libraries from many lighting manufacturers. However rendering integrations today still means that we are not seeing complete photorealism - and a lack of open standards mean that designers are tied to the rendering their vendor is capable of.

No major lighting previs platform currently supports OpenUSD, with GLB and MVR being the preferred standards for lighting previs at present. GLB and MVR have emerged as a valuable common standard between major platforms. 

> At LDI 2022, GDTF & MVR originators – Vectorworks, MA Lighting and Robe – put aside their competitive differences to provide TPi with an exclusive update on these developments and how this unifying open-source format is impacting the entertainment industry.
> - GDTF and MVR: Unlocking the potential of data driven design [>](https://www.tpimagazine.com/gdtf-and-mvr-unlocking-the-potential-of-data-driven-design/)

## Terms

The following fact sheets detail file types supported by different software and hardware platforms. While full documentation can be found online or in the [Glossary](Glossary.md), a short reference for these terms is below

### Digital Control Protocols

- DMX (aka DMX512-A or historically DMX512) 
	- a basic control protocol which was created in 1986 and subsequently became standard across industry
- Art-Net 
	- A way of transmitting multiple DMX signals across a network. 
	- It is proprietary, but royalty-free, being owned and operated by Artistic License Inc.


### Show Design File Standards

- GDTF
	- General Device Type Format
	- "a unified way of listing and describing the hierarchical and logical structure and controls of any type of controllable device (e.g. luminaires, fog machines, etc.) in the lighting and entertainment industry."[^5]
	- Developed by the GTDF Group[^4] 
	- It is possible to attach sidecar files to define the fixture when creating the GDTF file
		- PNG for a photograph of the fixture
		- SVG for a 2D vector projection of the fixture 
		- GLB (binary gITF) files define the fixture's 3D geometry in low, mid, and high resolution
	- This standard has also been adopted by the film industry, by manufacturers like Arri[^2] and Aputure[^3]
- MVR
	- My Virtual Rig
	- Developed by the GDTF Group
	- Container file that holds CAD geometry and fixtures, in the form of GDTF files 

Both GDTF and MVR are recognised by ANSI (DIN spec 15800 2022)[^6]

### 3D File Standards

- gITF
	- Referred to as 'the JPG of 3D'
	- GLB is an efficient, binary form
- OpenUSD
	- Interchange format developed by Pixar
	- Various 'flavours' of delivery encoding, including usdz (uncompressed) or usdc (binary)
- Legacy formats (Alembic, OBJ, FBX)

See also[^7]


## The Lighting Previs Landscape

The market offers a range of tools with a dynamic of established leaders and new challengers.

### WYSIWYG
A long-standing industry benchmark since 1994, WYSIWYG by CAST Software offers an integrated suite combining CAD, plotting, documentation, and real-time animation with visualisation, that is translatable to DMX control. [^2]

* Extensive fixture library (>25,000 items) in GDTF and MVR mainly, supports import
* Robust console connectivity
* VR capabilities 
* Lacks raytraced lighting
* WYSIWYG Design: CAD Software
* WYSIWYG Perform: Cue programming, previsualisation, 1:1 programming to DMX universes
* Previs capability touted as a 'powerful sales tool' for designers
* Limited export functionality via FBX, Alembic, or Collada
* High cost


![](wysiwig.jpg)
*wysiwyg's realtime rendering engine showcasing volumetric effects*

### Vectorworks Spotlight and Vision

Vectorworks Spotlight (first launched 1996) is a CAD tool that incorporates previs features, like its 'Showcase' real-time visualization engine. 

* No cue programming
* Extensive internal fixture library, and import via GDTF 
* Integration with Architecture platform Enscape - enhances realism through raytraced lighting and HDR display support. 
* Various 3D export formats (FBX, OBJ).
* MVR support
* Vectorworks Spotlight: CAD Software for theatre
* Vectorworks Vision: Cue programming, previsualisation, 1:1 programming to DMX universes
* Limited export functionality via FBX or Alembic
* High cost

### Capture

Positioned as a more accessible, user-friendly alternative, Capture is popular for its intuitive object-oriented drafting, quick rendering, and reliable DMX/Art-Net support at a considerably lower price point. 

* Basic CAD tools, High visual fidelity
* GDTF, MVR
* Realtime engine supports HDR, reflections, PBR
* Supported model export formats as **DWG/DXF, glTF (.gltf, .glb), and My Virtual Rig (.mvr)**. No mention of OpenUSD support.
* Supports animation and sequencing via DMX/ArtNet


### Depence2
Windows-only visualizer distinguishes itself with a focus on high-fidelity, physics-based rendering, delivering superior photorealism for lighting visualization. 

* It is gaining recognition for its visual quality but is less suited for comprehensive drafting or plot creation tasks.
* Basic CAD
* No native GDTF support, uses proprietary format. Supports MVR
* Cinema4D and Sketchu DWG import
* Excels in cue creation multimedia sequencing
* High visual fidelity
* Supports animation and sequencing via DMX

### Console-Specific Tools

*(Light Converse, GrandMA 3D)*
These tools prioritize seamless integration with specific lighting control consoles
- Light Converse offers support for DWG imports
- GrandMA 3D provides tight integration for pre-programming MA systems
- Both are primarily focused on visualization for programming rather than broader design and drafting capabilities.



## Analysis
### Digital Twins terminology

The concept of accurate "digital twins" for lighting fixtures is becoming more concrete. Initiatives like GDTF aim to standardize fixture data, allowing simulation of real-world fixture behaviour (photometrics, colour, gobo parameters) with greater accuracy. 

Film lighting firm ARRI recently released digital twins of their lights in Unreal Engine.[^8]


### Addressing Pain Points

#### Late-stage integration
Previs is beginning to designers and programmers to identify and resolve cueing issues, fixture conflicts, or undesirable looks before entering the venue - though ease of use, and communication make in-person development preferable.
#### Managing Complexity
Extensive libraries, clear imagery and 1:1 programming allows designers to get ahead with complex systems.
#### Communication & Coordination
Visualizations provide a clear, shared reference point for discussion between the lighting designer, director, other designers, and programmers. VR features promise to further enhance collaborative understanding of spatial lighting effects. 

However, **interoperability issues** between different software packages can still create communication barriers between departments using disparate tools.
#### Resource Scarcity
Previs aims to save valuable **time** (especially during tech rehearsals) and potentially **physical resources** (less need for physical mock-ups). 

However, the high **cost** of leading software packages and the demanding **hardware** required for photorealistic rendering create significant resource barriers, particularly for smaller productions. 

The considerable **learning curve** also represents a time/training resource investment.


## Conclusion

Theatre lighting previsualization in 2025 is a sophisticated field, essential for modern productions. WYSIWYG and Vectorworks Spotlight continue to offer comprehensive, albeit costly, solutions. Several parallel software solutions exist, that have recently taken steps to establish common standards.




[^1]: 

[^2]: https://www.arri.com/en/lighting/led-spotlights/l-series-plus/downloads

[^3]: https://gdtf.eu/blog/sidus-link-pro-with-gdtf-import/

[^4]: a group comprising of Vectorworks, MA Lighting, and ROBE

[^5]: https://gdtf.eu/gdtf/file-spec/scope/

[^6]: https://webstore.ansi.org/standards/DIN/dinspec158002022

[^7]: Read more in the appendix [5. 3D File Formats - USD, gITF, Others](5.%203D%20File%20Formats%20-%20USD,%20gITF,%20Others.md)

[^8]: https://www.ibc.org/virtual-production/news/arri-skypanel-offers-unreal-improvements/20467
