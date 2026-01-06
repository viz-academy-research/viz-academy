The National Theatre (NT), a globally recognised leader in theatrical production, is renowned for its artistic innovation and technical excellence. Public evidence suggests prominent use of Autodesk AutoCAD and 3DS Max, capable of high fidelity textured and realistic, raytraced renders, to visualise set designs.

Visit: [nationaltheatre.org.uk](https://www.nationaltheatre.org.uk/home/)

---

#### Contents
- [[#AutoCAD Use|AutoCAD Use]]
- [[#3ds Max Use|3ds Max Use]]
	- [[#3ds Max Use#Where it falls short|Where it falls short]]
		- [[#Where it falls short#Screen-based|Screen-based]]
		- [[#Where it falls short#Pre-Rendered|Pre-Rendered]]
		- [[#Where it falls short#High Skill Floor|High Skill Floor]]
		- [[#Where it falls short#Lack of Cloud/Sharing/Interactivity/Feedback|Lack of Cloud/Sharing/Interactivity/Feedback]]
		- [[#Where it falls short#Colour Gamut|Colour Gamut]]
- [[#Additional remarks|Additional remarks]]
- [[#Pain Points addressed|Pain Points addressed]]
	- [[#Pain Points addressed#Late-stage Integration|Late-stage Integration]]
	- [[#Pain Points addressed#Communication & Coordination|Communication & Coordination]]
	- [[#Pain Points addressed#Resource Scarcity|Resource Scarcity]]
- [[#Conclusion|Conclusion]]


---

## AutoCAD Use

National Theatre is featured on Autodesk's website as a successful 'Customer Story' owing to the work of project draughtsman Oli Cooper[^1] . This is notable to us due to its profile and the light it sheds on AutoCAD as industry-standard practice in London Theatre for highly technically accurate design of functional staging. 

Cooper's role sits parallel to set designers, meaning that technical draughting of sets has a single point of accountability. With smaller or mid-level productions, technical draughting of set can be shared between in-house technical team and the set designer.

> “I take 1/25 scale models that designers have produced, or even just design concepts, and turn them into full design drawings, where they can edit and update their design based on budget, functionality, and material economy,”  he explains. 
> 
> “Then, from that, I take it to what we call a bench drawing, where we actually manufacture the piece in a carpentry or metal workshop for the stage. Alongside that, I also produce ground plans—what are essentially the architect’s drawings—of the theater with all these elements in and see how they coordinate together, essentially choreographing their dance around the stage.”
> 
> AutoCAD Customer Stories, Oli Cooper, 2019

![](autocad.png)
*AutoCAD drawings from National Theatre*


Online wording surrounding NT exhibitions like "Playing with Scale" (2018) suggest that while digital drafting was fully integrated into workflow at this time, production teams revolved around traditional model boxes to express ideas.


> "With AutoCAD as his foundation, Cooper and his peers are starting to branch out a bit, adding in other Autodesk programs such as 3ds Max to test sightlines."
>
>AutoCAD Customer Stories


## 3ds Max Use

Senior Digital Artist Daniel Radley Bennett's professional profiles and portfolio provide direct evidence of advanced 3D previs work with National Theatre using **3ds Max**, industry standard 3D software with realistic rendering capabilities similar to Maya or Blender.

His experience explicitly includes "Creating 3D Previs for shows in the Olivier, Lyttleton, Dorfman and Temporary Theatre Space" during his time as Digital Artist (2015-2018).[^2] Specific productions where 3ds Max previs was employed are cited across his various platforms, including:

* **Angels in America** (Lyttelton)
* **King Lear** (Olivier)
* **Jack Absolute Flies Again** (Olivier)
* **The Plough and the Stars** (Previs storyboarding using CAD models for set/cast movement)
* **The Silver Tassie**

>"using CAD models to assist stage management and the creative team with set and cast movement planning" 
> 
>"sightline verification"
>
>"integrating projection design"
>
> *Daniel Radley-Bennett, Portfolio, The Plough and the Stars*

Radley-Bennett appears as **"previs artist"** for the **National Theatre Live: Twelfth Night** broadcast in 2017. This may confirm the use of 3D assets to plan camera angles and visual sequences for broadcast. 

![](3ds%20max%20animation.webp)
*Image courtesy Daniel Radley-Bennett, National Theatre*


> "As much as possible I try to texture and light the models which help the creative teams really connect with the previs. All texturing in this case was made via Adobe Photoshop."
> - Daniel Radley-Bennett, Portfolio, The Plough and the Stars


The above instance in 2016 shows detailed texturing and raytraced rendering, performed in parallel to the set design team. This level of oversight undoubtedly provided a level of confidence and signoff for the creatives and key stakeholders. Radley-Bennett effectively performs the 'communication' responsibility of the previsualisation artist; this is closer to the vision that is in the set designer's mind than a traditional 'white-card' model box would be. In this instance, and at a period of early adoption, the expense in hiring a previsualisation professional was justified, which continues to this day evidenced by the NT's continued practice of it to this day.


## Additional remarks

Both Cooper and Radley-Bennett's positions (project draughtsman and previs artist) indicate parallel role positioning - i.e. this work occurs by dedicated technically-minded people separate to the creative team[^3].

This shows a successful case of a previs artist being a long-standing member of high-level theatre production.



## Analysis

### Pain Points addressed

#### Late-stage Integration
The use of AutoCAD for accurate drafting, combined with 3ds Max for photorealistic imagery, sightline studies, and sequence planning, directly addresses **Late-Stage Integration** challenges by allowing earlier, more detailed spatial and temporal validation. 
#### Communication & Coordination
Likely enhances **Communication & Coordination** by providing clearer visual references for complex sequences or designs.
#### Resource Scarcity
Potential **Resource Scarcity** is likely mitigated by reducing errors caught late in the process and enabling more efficient planning.


### Where it falls short

#### Screen-based
A level of abstraction is still needed to imagine and position sightlines, and overall visual impression to the audience. The option to view in stereoscopy or VR/mobile AR would be a plus, as this is closer to real expeirnce
#### Pre-Rendered
All decisions (e.g. set movements and sequencing, positioning of overhead view, lighting) will need to have been made ahead of time, with each revision incurring more time/cost.
#### High Skill Floor
Technical specialists required to produce this level of work in 3ds Max. Libraries and rendering tools are emerging[^5] with lower skill floors. This will only continue to enable accessibility by non-technical creatives. Imagine a lead designer could employ a previs artist but hand them over a working prototype first, or make changes to the previs artist's work after the fact. This fluidity and 'everyday use' aspect of the tools is important, and moves towards visionary ability and accountability (i.e. role) being the deciding factor of use, rather than technical ability.
#### Lack of Cloud/Sharing/Interactivity/Feedback
Platforms have since emerged for easy sharing and feedback of animated, interactive 3D assets, many featuring pre-baked raytraced lighting. [^4]
#### Colour Gamut
The 3D asset is seen above compressed to WEBP/GIF format from a source video (which has since been removed). Some further gamut  restrictions have taken place between the source video (rec709) and GIF (256-colour). Regardless of this, we can still see that the source material likely rendered raytracing in rec709 or sRGB natively, rather than in a Linear or ACES space, likely as a default option or to save processing time. This can be observed from the luminance range typically exhibited by this rendering method. A linear colour pipeline and HDR exhibition capability is far more preferable for asset, but is only now becoming viable and affordable. This dovetails with previous remarks [VR Getting Brighter in HDR](The%20Tech%20Industry%20-%20What%20is%20New.md#VR%20Getting%20Brighter%20in%20HDR)



## Conclusion

Evidence confirms the National Theatre employs advanced 3D previsualization, using 3ds Max for dynamic planning (including sightline studies, storyboarding, and broadcast integration) alongside established AutoCAD drafting and traditional physical models.

While the NT successfully leverages these sophisticated tools, demonstrating a practical model for a major institution, the reliance on specialist digital artists and complex software presents scalability challenges for the wider industry.

Currently, the interest in and application of such advanced previsualization appear concentrated in high-level productions; longer timelines on these larger shows perhaps make the significant effort involved, including detailed texturing and potentially duplicated modelling work, a worthwhile investment, contrasting to lack of historical adoption elsewhere.

Nonetheless, the National Theatre exemplifies how advanced digital visualization can be actively integrated into theatre production workflows.

---

### References

[^1]: [National Theatre London | AutoCAD Customer Story](https://www.autodesk.com/customer-stories/national-theatre-london)

[^2]: Source: LinkedIn

[^3]: Ryan Metcalfe's study highlighted 'scope creep' of tech responsibilities on the creative team, as capabilities of the technology expand.

[^4]: Sketchfab, p3d, RealityMAX, Nvidia Omniverse, Connector Suite, Vectary

[^5]: Blender, Twinmotion, Vectary, Lumion, Enscape, Unreal Engine, Unity
