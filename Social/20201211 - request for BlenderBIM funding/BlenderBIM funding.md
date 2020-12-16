  

*Go [here](https://www.bountysource.com/issues/95048565-make-construction-drawing-generation-like-really-really-awesome) to help fund this project.*

## A call for Funding

It appears the general sentiment in the AEC industry, brought to the fore most recently by the [open letter to Autodesk](https://www.archpaper.com/2020/08/open-letter-to-autodesk-swells-over-100-signatories-and-supporters/), is that design professionals feel that the value they receive from their current tools does not align with what they pay for them.

Development is too slow. Interoperability is broken, and not prioritized.

Luckily there are improving [open source alternatives](https://wiki.osarch.org/index.php?title=AEC_Free_Software_directory) and growing [movements](https://osarch.org/) to help change the course.

One such open source alternative is [Blender](https://www.blender.org/).  For those unfamiliar, Blender is very similar to [Sketchup](https://www.sketchup.com/) and some would argue, an even more robust solution. It is currently being used by a growing number of A/E firms.

In an effort to extend Blender to be more useful for our industry, Dion Moult (@Moult),  Thomas Krijnen(@aothms) and others have created [BlenderBIM](https://blenderbim.org/), which as the name implies, is creating BIM functionality inside Blender. 

The backbone behind BlenderBIM, which makes it exciting for our industry, is the [IFC](https://www.buildingsmart.org/standards/bsi-standards/industry-foundation-classes/) standard.

For those unfamiliar, IFC is like the HTML of our BIM universe.  Similar to how HTML is the underlying infrastructure for the internet, the IFC standard is looking to be the underlying standard for exchanging BIM data. 

Currently, however, as is witnessed by the growing [dissatisfaction](https://www.archpaper.com/2020/08/open-letter-to-autodesk-swells-over-100-signatories-and-supporters/), these predominate BIM programs don't necessarily prioritize the adoption of the standard to the level they could, or should. 

Simply put, it's not in their best interest to do so.  The more you can move content outsider their ecosystem, the less potential they have for lock-in.  Their benefit, is our loss, as an industry.

The general roadmap behind BlenderBIM, having followed this project since its inception, has been to couch its development, as thoroughly as possible, in the IFC standard.  With the ultimate intent to realize full IFC roundtripping.

Even though only started a year ago, BlenderBIM's development has been impressive--considering the main developer has only worked on it part time. 

Although BlenderBIM has many burgeoning tools, the call for funding here is to improve, specifically, the current 2D documentation functionality.

At present, BlenderBIM does provide functionality to [compose and produce 2D documentation](https://wiki.osarch.org/index.php?title=BlenderBIM_Add-on_exporting_2D_documentation), but as Dion hints in the thread above, the current process and UI is painful--as is normal for alpha software development.

Simply put, the funding for this project, will go to help improve the interface for composing a typical construction document set inside Blender.

To summarize, Dion's list above, the funding would go to.

- Improve 'paper space' layouts
- Provide intelligent section and elevations tags that reference drawing numbers and sheet names
- Provide a [WYSIWYG](https://en.wikipedia.org/wiki/WYSIWYG) interface for  intelligent, parametric dimensions, tags, etc.
- Capture this annotation within the IFC file itself so other BIM programs could use and modify without data lose. There has been discussion about roundtripping this annotation with other open source BIM programs like  [FreeCAD](https://wiki.freecadweb.org/Manual:BIM_modeling).
- The current functionality, and indented roadmap, is that the final 'printed documents' are SVG files.  This has huge and exciting implications.  As SVG is a very robust web standard for viewing vector based drawings within the browser.  With such an approach, drawings can be dynamic, giving the end user the ability to turn on/off annotation, and/or switch between drawing contexts. Imagine cycling between a ARCH view and the STRUCT view within one drawing. The drawing can also be queried, similar to how a BIM model can be queried.
- Have the print (the SVG file) be all vector based. Currently only those items crossed by the 'cut plane' are vector based and those 'beyond' are rasterized.
- Improving the back end 'guts' behind how these drawings are processed.  Currently it's rather slow and memory intensive.

Your funding, as well, probably could not go to a more qualified team.

Navigating the IFC standard is difficult and Dion Moult (@Moult),  Thomas Krijnen(@aothms) are leaders in the field. 

Thomas has a doctorate and has centered his dissertation around creating [IFCOpenShell](http://ifcopenshell.org/), which is basically the backbone behind BlenderBIM, and other programs as well. 

Dion, in addition to being the main developer behind BlenderBIM, has also demonstrated, over the years, a thorough grasp of the IFC standard and has provided the key leadership in the founding and continued development of the [OSArch](https://osarch.org/) community.

Dion and Thomas, among others, had recently won a [BuildingSmart](https://www.buildingsmart.org/) award for [their work](https://vimeo.com/479924151) centered around BlenderBIM and IFCOpenShell.

Although open source software is typically free, its development is not.  It takes time and effort.  At the end of the day, it's health depends on us, as an industry, funding these types of initiatives.

I am confident, if A/E/C firms spent a tenth of their technology budget on open source tool development, like this one, that we, as an industry, would have comparable tools in a relative short time.  Tools furthermore, that since open, that can be modified and tailored to a particular A/E practice.  Tools, ultimately, that allow firms to forefront their knowledge and expertise--which is a design professional's real value.

To help fund this initiative, please go [here](https://www.bountysource.com/issues/95048565-make-construction-drawing-generation-like-really-really-awesome).

*[Bountysource](https://www.bountysource.com/), is similar to [GoFundMe](https://www.gofundme.com/), but more centered around software development.* 

---


Hi @_SW_News

Having recently signed the open letter to Autodesk we were wondering if you would consider funding @BlenderBIM—an open source project to create CD's in @Blender.

Details:
https://github.com/IfcOpenShell/IfcOpenShell/issues/1153#issuecomment-743405481

Please consider retweeting this to help spread the word.

#OSArch

---

For those that resonated with the recent open letter to Autodesk and are looking for a BIM alternative, please consider funding BlenderBIM project—an open source project to create CD's in @Blender.

https://github.com/IfcOpenShell/IfcOpenShell/issues/1153#issuecomment-743405481
























<!--stackedit_data:
eyJoaXN0b3J5IjpbLTgxMzIxMTQ2MSwtMTAwNDMxNzA0LDMzND
U1Nzc0MywtOTYwNjIwMDk4LDE0ODI0MDg4NSwzODk5MTgyNDAs
MTU1MDM5MTk3MSwtMTc2Mjc4MTc2LC01Mjk4MjQ0MTQsLTEyNT
kzMTQ3MTUsMTkyMDM0NzU2MSwtMTM1NTcwOTA4MSwxNDY2ODQ2
Njg1LC0xNzMzMzc4NjU3LDE1NDA4ODUxMzAsLTkzMzI0MjY4Mi
wtNTY0Njk3MDg1LDE5MDM0OTczNzQsLTExNzc3MTQ4NSwtMTQ1
MDU5NjQ5MF19
-->