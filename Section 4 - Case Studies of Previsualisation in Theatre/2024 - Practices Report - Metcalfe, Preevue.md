The "Optimising Visualisation Practices" report, authored by Ryan Metcalfe (Preevue Ltd) for the RSC, examines why potential of visualisation is unrealised, and proposes a structured framework for improvement. 

Core issues discussed: 
- A lack of dedicated roles and resources, with visualisation tasks often falling to designers or programmers as an added burden, perceived merely as a cost rather than a cost-saving investment. 
- While the increasing availability of 3D venue models provides a foundation, awareness gaps and departmental silos hinder effective use, leading to duplicated efforts. 

The report argues that visualisation must become an essential, integrated component of production - a unique view from an industry insider, to where previsualisation responsibilities currently sit with creative teams.

Read here: [OptimisingVisPractices-Metcalfe.pdf](OptimisingVisPractices-Metcalfe.pdf)


---

- [[#Current Tools & Workflow Challenges|Current Tools & Workflow Challenges]]
	- [[#Current Tools & Workflow Challenges#CAD|CAD]]
	- [[#Current Tools & Workflow Challenges#Lighting|Lighting]]
- [[#Proposed Solutions & Best Practices|Proposed Solutions & Best Practices]]
	- [[#Proposed Solutions & Best Practices#Dedicated "Production Visualiser" Role|Dedicated "Production Visualiser" Role]]
	- [[#Proposed Solutions & Best Practices#"Visual Twin" vs. "Digital Twin"|"Visual Twin" vs. "Digital Twin"]]
	- [[#Proposed Solutions & Best Practices#Workflow & Data Management|Workflow & Data Management]]
	- [[#Proposed Solutions & Best Practices#Asset Capture & Archiving|Asset Capture & Archiving]]
	- [[#Proposed Solutions & Best Practices#"E-Tech" (Digital Tech Rehearsal)|"E-Tech" (Digital Tech Rehearsal)]]
- [[#Virtual Reality (VR) in Theatre: A Focused Tool|Virtual Reality (VR) in Theatre: A Focused Tool]]
- [[#Analysis|Analysis]]
	- [[#Analysis#Pain Points|Pain Points]]
		- [[#Pain Points#Communication & Coordination|Communication & Coordination]]
		- [[#Pain Points#Late-Stage Integration|Late-Stage Integration]]
		- [[#Pain Points#Resource Scarcity|Resource Scarcity]]
		- [[#Pain Points#Managing Complexity|Managing Complexity]]
- [[#Conclusion: A vision towards integrated Visualisation|Conclusion: A vision towards integrated Visualisation]]
	- [[#Conclusion: A vision towards integrated Visualisation#References|References]]


*Note: complexity of subject matter necessitates analysis being dispersed within generally commentary segments of this article.*


---

## Current Tools & Workflow Challenges

The report analyses common software tools, noting many weren't designed specifically for theatre, which in cur difficulties and workaround often swept under the rug by time-pressed technical freelancers, even as prominent as Lighting Designers and Set Designers. Looking at these particular software packages is important and speaks to larger issues that Metcalfe goes on to address

### CAD
AutoCAD is the current industry standard for set designers and draughtsmen exchanging DWGs, despite its AEC focus and 3D limitations requiring workarounds. 

Vectorworks, favoured by lighting designers, offers useful entertainment toolsets (like Spotlight), but its capabilities are often underused. 

SketchUp provides easier entry but is less robust, while Rhino's powerful modelling is gaining traction. A key challenge is exporting 'solid' or 'spline-based' models from CAD to 'polygonal mesh' formats used by common 3D rendering engines, which is often a one-way, data-losing process.

### Lighting
Tools like WYSIWYG, Capture, Depence, Augment3d, and GrandMA 3D exist, but often require significant, unbudgeted setup time practicioners, leading to duplicated effort as data is rebuilt. 

Import compatibility varies; game-engine-based tools like Augment3d handle imports better, while Capture is noted for photometric accuracy. No single tool dominates due to setup demands.

## Proposed Solutions & Best Practices

Metcalfe proposes a framework to overcome these issues of best practices across the industry moving forward:

### Dedicated "Production Visualiser" Role
A standalone role, acting as the central custodian for all digital visualisation assets, integrating departmental data, ensuring integrity, and managing distribution.

### "Visual Twin" vs. "Digital Twin"
Maintaining two complementary master files is recommended:
    * **Visual Twin:** A photorealistic representation (e.g., in UE5) for communication, sightline analysis, clash detection, and approvals.
    * **Digital Twin:** A CAD-accurate model preserving technical details and properties for departmental workflows and archiving.

It is possible that, like ArchViz/BIM tools, that there will come a single platform with the capability to hold one 'master twin' for the purposes of theatre production, that holds all assets associated with itself, for CAD, practical or rendering practices.

### Workflow & Data Management
Emphasis on **standardized file formats** (DWG, VWX, FBX, MVR, exploring USD/glTF) and **interoperability** over enforced single software solutions. Requires strict **version control**[^1], consistent **world space positioning**, and best practices for **3D modelling** (optimisation, clean topology, UV mapping). Data distribution should be tailored to each role's needs (e.g., specific file formats, pixel streaming, executables).

This may be remedied by future cloud platforms. Industry standard, next-gen file type are beginning to emerge across industry now that will aid standardisation.

### Asset Capture & Archiving
Utilizing **LiDAR or photogrammetry** to capture sets/venues is vital for digital twins and reuse. Archiving **raw scan data** is advised.  A centralized system is needed to avoid data siloing between departments. Consider **compression** (Draco, 7zip) for large datasets.

Future ML tools may automate the currently laborious point-cloud-to-CAD conversion. In the time between the writing of this report and now, these ML tools have started to emerge, with machine-learning libraries being utilised by Artec 3D for traditional photogrammetry, or new startups like Luma Labs and technologies like Gaussian Splatting, along with MCP technology beginning to use AI to build detailed models from scratch.

### "E-Tech" (Digital Tech Rehearsal)
This future scenario envisions formal virtual tech rehearsals led by a stage manager, bringing all departments together in the Digital Twin environment for early, cost-effective, collaborative problem-solving before entering the physical venue. 

A thorough study and simulation of the technology to develop workable 'E-Tech' is highly exciting and highly ambitious. The prototype would require enhanced interoperability layers built between typical theatre platforms and protocols (Artnet, OSC, DANTE), along with cross conversion, virtualisation or re-creation of commonly used sequencing software, on top of improved standards in 3D file formats, and online streaming & rendering.


## Virtual Reality (VR) in Theatre: A Focused Tool

Metcalfe views VR as powerful but with specific, limited applications. Its key strength lies in **bridging the understanding gap** for non-technical stakeholders (e.g., producers) and enabling intuitive, accurate **sightline assessment**, overcoming the distortions inherent in flat-screen representations. 

Successful use cases (like *Harry Potter and the Cursed Child*) involved VR for communication and approvals, not as a primary design tool, as designers prefer existing software. Practical implementation demands **simplicity and speed** for busy stakeholders, often requiring an operator's assistance. 

While VR integration exists in some lighting software, its benefits for typical proscenium setups are debatable and are beyond the performance expectations of current systems; poor implementation of VR especially is unacceptable for user comfort levels. VR is valuable when used strategically for communication and spatial analysis.

It may be possible that further down the line of e-tech capabilities - i.e. once sequencing, audio, lighting, and movement capabilities are more possible to tangibly display, the limited value offered by this format at present may be vastly extended.

## Analysis

### Pain Points

Metcalfe's proposed framework directly targets key production pain points:
#### Communication & Coordination
Addressed by the central Production Visualiser role, shared twin models, data standards, and conjectured to be assisted in future by collaborative E-Tech sessions.
#### Late-Stage Integration
Mitigated by early, accurate visualization, clash detection within the Visual Twin, and VR sightline reviews
#### Resource Scarcity
Improved by reducing errors, eliminating duplicated work, saving travel time, and making physical tech time more efficient via E-Tech prep.
#### Managing Complexity
Handled by providing intuitive visual tools (Visual Twin, VR) for holistic understanding and precise technical data (Digital Twin) for specialists.


## Conclusion: A vision towards integrated Visualisation

The Metcalfe report advocates strongly for elevating theatre visualisation from a fragmented, undervalued task to an integrated, essential production discipline. 

It argues that realizing its potential requires dedicated **Production Visualiser** roles, structured **Visual/Digital Twin** workflows, a focus on **interoperability** and data standards, and strategic, appropriate use of tools like **VR** and **E-Tech**. 

While necessitating cultural shifts and investment, this integrated framework offers a clear path towards more efficient, collaborative, and visually sophisticated theatre production.

Interviews in Metcalfe's report confirm that visualisation is often an 'extra-mile' addition to workloads from certain team members, hampered by time constraints and lack of dedicated personnel or streamlined processes. This argument rings true with our overall picture of things.

3 scenarios utilising previs seem to emerge, taking all of this into account:

1. Previsualisation responsibilities shared throughout the team
2. A dedicated Production Visualizer, or previs artist
3. A sidecar contractor, like Preevue, with a dedicated team to provide this service.

Each of these scenarios have their own associated costs and capabilities, and different applicable uses-- all of which will morph and develop in the next decade on technological development.

The key thesis of Viz Academy is that the theatre community of practitioners and key stakeholders should realise their role in shaping this future, and in influencing future innovators of previsualisation. We examine this in detail in the next section, in particular [4. Roles, Impact on Process](4.%20Roles,%20Impact%20on%20Process.md).

---

### References

[^1]: Similar to practices in the software and technology industry.
