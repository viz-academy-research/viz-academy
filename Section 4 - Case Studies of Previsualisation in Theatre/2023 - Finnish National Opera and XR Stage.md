Finnish National Opera (FNO) in Helsinki has emerged as a distinct leader in advanced previsualization techniques, drawing inspiration initially from practices in film & TV. 

Their innovative approach included the development of '**XR Stage**' began a greater reshaping of complex opera productions, moving from an open-source Unreal Engine based tool to closed source USD-based, in a partnership deal with [next-gen tech startup **Younite**](2025-01%20-%20Younite%20and%20Virtual%20Stage.md). XR Stage was then renamed as '**Virtual Stage**', and this is chronicled in its own article later on.

XR Stage was developed as an open source software project by Finnish National Opera and Ballet, after receiving a FEDORA Next Stage grant of €60,000.

[Read more here.](https://oopperabaletti.fi/en/news/the-finnish-national-opera-and-ballets-xr-stage-project-receives-an-international-grant/)


---

#### Contents
- [[#Developing XR Stage|Developing XR Stage]]
- [[#"Turandot" proof of concept|"Turandot" proof of concept]]
- [[#Benefits beyond design|Benefits beyond design]]
- [[#Analysis|Analysis]]
	- [[#Analysis#Pain Points|Pain Points]]
		- [[#Pain Points#Communication & Coordination:|Communication & Coordination:]]
		- [[#Pain Points#Late-Stage Integration:|Late-Stage Integration:]]
		- [[#Pain Points#Resource Scarcity:|Resource Scarcity:]]
		- [[#Pain Points#Managing Complexity:|Managing Complexity:]]
- [[#Conclusion|Conclusion]]
	- [[#Conclusion#References|References]]


---

## Developing XR Stage

Recognizing the challenges of planning large-scale opera productions, the FNO invested in creating its own previsualization tool. XR Stage, built within Unreal Engine (likely as a set of **plugins**), this system allowed the building of digital twins of their stage sets long before any physical construction begins [^1]. 

It is worth saying that descriptions at the time of developement, including marketing material, state the previsualisation to be 'photorealistic'. In can be argued that in the present day, the quality bar is considerably higher. Unreal Engine 5 (XR Stage likely used UE4) has since integrated new technologies like Lumen and Megalights, with Nvidia RTX bringing true real-time raytracing to the market. XR Stage does not observably exhibit this level of realitme quality, instead resembling typical interactive VR experiences of the time, complete with user interfaces tracked to handheld wand controllers. 

Users of XR Stage, observed in many videos documenting this process[^8], are equipped with Varjo Aero[^7] headsets, dubbed best VR headset of 2022. Varjo Aero support 200Hz refresh rate and 115 degree visibility, which is on par with today's best hardware. Pixel density would just fall short of Apple Vision Pro, though on par with modern headsets like Bigscreen Beyond 2. Varjo Aero lacks HDR support.

XR Stage requires a PC and SteamVR to operate.

Users can navigate stage and sets, assess sightlines, and interacting with digital props and scenery as if they were physically present [^2].


## "Turandot" proof of concept

The FNO first deployed the XR Stage comprehensively for their ambitious production of Puccini's "Turandot," which premiered in January 2023. This marked a significant milestone, making them reportedly the first opera house globally to utilize immersive XR/VR technology throughout the entire production lifecycle [^2]. 

Designers, directors, technicians, and performers could inhabit the virtual set from the earliest stages, testing staging ideas, refining lighting concepts, and identifying potential issues months in advance [^3]. This early, shared virtual access was touted to enable a deeper, more intuitive understanding of the final production's look and feel.

## Benefits beyond design

It is reported that the implementation of XR Stage for "Turandot" yielded significant practical advantages beyond traditional creative planning. As a co-production with Malmö Opera in Sweden, the digital twin facilitated seamless collaboration between the international teams. 

Virtual meetings and reviews within the shared digital environment drastically reduced the need for international travel and associated costs [^1] [^2]. 

Furthermore, planning complex technical elements and safety procedures within the virtual space contributed to improved workplace safety, and **more efficient use of materials and labour** once physical construction began.

It is probable that the FNO used XR Stage for subsequent productions. Their 2024-2025 season features a complex new opera, Alexander Raskatov's "Animal Farm," another international co-production. [^4] [^5]


## Analysis

### Pain Points

The FNO's XR Stage initiative, and implementation documented for "Turandot," directly tackled several core production pain points:
#### Communication & Coordination:
The shared virtual environment provided a crucial platform for the international co-production team, enabling "seamless collaboration" and reducing reliance on travel. Allowing diverse team members (designers, directors, technicians, performers) to inhabit the virtual set fostered a unified understanding from early stages.
#### Late-Stage Integration:
By allowing teams to test ideas, refine lighting, assess sightlines, and identify potential issues "months in advance" within the virtual replica, XR Stage aimed squarely at preventing the spatial and technical conflicts that often emerge only during physical tech rehearsals.
#### Resource Scarcity: 
The project demonstrated clear resource efficiencies by reducing costly international travel for the co-production team. Furthermore, enhanced planning for technical elements and safety was reported to lead to more efficient use of materials and labour during the physical build phase. Early identification of problems also prevents expensive late-stage fixes.
#### Managing Complexity: 
XR Stage provided an interactive, immersive tool to help the large, dispersed team grapple with the inherent complexity of a large-scale opera production and international co-production logistics.

## Conclusion

The Finnish National Opera's approach mirrors the dynamic, sequence-based previsualization common in film [^6], moving beyond static 3D models to create immersive, interactive planning environments.

This contrasts with many other major houses, which might use digital tools more for archival, streaming, or specific design elements rather than comprehensive production previs. 


---


### References

[^1]: XR Stage - Finnish National Opera and Ballet: [https://oopperabaletti.fi/en/xr-stage/](https://oopperabaletti.fi/en/xr-stage/)
[^2]: Finnish National Opera and Ballet’s Turandot Becomes the First Production to Utilize Varjo’s XR Technology - Varjo Press Release: [https://varjo.com/press-release/finnish-national-opera-and-ballets-turandot-becomes-the-first-production-to-utilize-varjos-xr-technology/](https://varjo.com/press-release/finnish-national-opera-and-ballets-turandot-becomes-the-first-production-to-utilize-varjos-xr-technology/)
[^3]: A symphony of technology: Finnish National Opera creates entire set in VR - MIXED News: [https://mixed-news.com/en/finnish-national-opera-uses-virtual-reality-for-stage-production/](https://mixed-news.com/en/finnish-national-opera-uses-virtual-reality-for-stage-production/)
[^4]: Animal Farm - Finnish National Opera and Ballet: [https://oopperabaletti.fi/en/repertoire/animal-farm/](https://oopperabaletti.fi/en/repertoire/animal-farm/)
[^5]: Governance - The Finnish National Opera and Ballet: [https://oopperabaletti.fi/en/governance/](https://oopperabaletti.fi/en/governance/)
[^6]: Previsualization - Wikipedia: [https://en.wikipedia.org/wiki/Previsualization](https://en.wikipedia.org/wiki/Previsualization)

[^7]: https://varjo.com/products/aero/

[^8]: 
	<iframe width="560" height="315" src="https://www.youtube.com/embed/XldXAcMLSII?si=5xvUkrd0uOT3qgwD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
	XR STAGE by the Finnish National Opera and Ballet
	https://www.youtube.com/watch?v=XldXAcMLSII
