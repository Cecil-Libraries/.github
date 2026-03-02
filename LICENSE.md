### Cecil Libraries License (1.1.0)
*An Open/Reserved-Source License, created by Cecil Libraries to handle legality related to Usage of Software and related Components to the Product.*

Copyright 2025 Cecil Libraries Organization and the Founder(s) Chaosyr
___
#### Definitions

This section goes over any Key Terms that may be unfamiliar to those reading this License. All **bolded** terms will refer back to this section 

* **Project** - A developer's own work or product that may incorporate this **Product**.
* **Product** - The project in which this License is applied onto.
* **Extension** - A **Project** in which is made for as a derivative work to the  **Product** by expanding API Coverage and the likes.
* **Founder** - One of the following definitions dependent on circumstance.
    * The person who originally made the **Product**, OR under the condition the **Product** does not come solely from them, Definition 2 applies.
    * The group behind the given **Product**, OR under the condition none of the prior two groups are available, Definition 3 applies.
    * The Organization behind the **Product**.
* **Organization** - The Organization that originally created or now maintains the **Product**.
* **Contributors** - One of the following definitions dependent on circumstance.
    * Developers who have contributed code into this **Product**.
    * Asset-Creators who have made assets for this **Product**.
    * Documenters who have created documentation based upon the **Product** to be bundled with the **Product**.
    * Anyone else who has contributed to the **Product** in any way, shape, and or form.
* **Developer** - A person in which is using this **Product** for purposes of developing their own **Project**. This includes the following but is not limited to,
    * **Mod-Makers** - A developer who is using this **Product** for purposes of making their own Mods.
    * **Game-Developers** - A developer who is using this **Product** for purposes of making their own Games.
    * **Software-Developers** - A developer who is using this **Product** for purposes of making their own Software.
**End User** - Anyone who is using this **Product** as a bi-product of it being shipped with another **Developer**'s **Project**.
**License** - This very license in which is being read right now.
**Sub-License** - A license bundled in the same **Product** that the **License** was applied.

#### 0.) Edge Cases

This section is meant to outline Edge cases of the license.

1. In the case where a **Sub-License** conflicts with the terms outlined in this **License**, the **Sub-License** is over-ruled by the **License**.
2. Any license bundled into the **Product** alongside this **License**, unless stated otherwise is considered a **Sub-License**.
3. If a dependency of the **Product** has its own licenses, this **License** does not over-rule it, as it only governs the **Product** itself.
4. In the case that a **Developer** breaks a **Sub-License**, it must be informed to the **Founder** of the **Product** for resolution.
5. In the case that a **Contributor** breaks a **Sub-License**, it must be informed to the **Founder** of the **Product** for resolution, if it can't be worked out between the two **Contributors**.
6. Any and all Rights which restrict or deny access to the **Product** are reactive.
7. The **Contributors Clause** only applies to **Contributors** contributing into the **Product** directly.
    * If they are *Pushing* to the **Product** repository then yes it applies, otherwise it does not.
    * While it would be ideal if a Fork carried this **License** along with **Sub-Licenses**, its not required.
8. What does *Reserved* sourcing mean in this context? That refers to the type of sourcing where the source is readily available on for example GitHub, and Decompilation is denied as its already available.
9. This is intended to be compatible with other Open-Source / Reserved-Source Licenses.
10. How can this **License** be referenced? It can be linked, placed in a text/md file by the **Product**, or you can include a reference to the **Project**'s page in some form of a credits document.
11. If this **Product** is to be included on another Website than already provided, contact the **Organization** to get it resolved.
12. The **Product** must not be decompiled, instead utilize the open source that the **Product** already has.
    * While Command Line Inspection like `dumpbin` to inspect the **Product** (especially for NativeAOT builds) is fine, do not utilize `DNSPY` or similar to inspect the internals.
13. **Extensions** must bear this **License** alongside any other License or **Sub-License** the **Developer** wishes to include on the **Extension**.
14. An **Extension** may be bundled into the direct **Product** or migrated onto the **Organization** if the **Organization** or **Founder** reaches out to the **Developer** that created it, and they consent.
    * If the **Extension** is migrated, the **Project** associated with the **Extension**, the **Extension's** **Developer** must at minimum be attributed to in some way shape, and or form.
15. When we say *Negatively Impact*, what does that mean? Well its meant for the case where a **Developer** would tamper with the code of this **Product** to tamper and in turn negatively impact the **Project** of another, this is not meant as a discrimination tactic, its a security note.
16. The source code of any **Product** utilizing this **License** must be open sourced, in some way that can be accessed at almost any time, for example a GitHub Repository.
17. The **End-Users** clause may be expanded upon by the **Organization** if seen necessary and reasonable.
    * In these cases the version number must change, add a `.X` at the end to indicate that its a minute change to the **End-Users Clause**. This does not retroactively apply.
    * Larger changes should modify in the Major-Minor-Patch system for the **License** version.

#### 1.) The Founders Clause

This section is meant to outline the rights in which the **Founder** is given over the **Product** that this **License** governs.

* The **Founder** may request reasonable alterations to how the **Product** is used, within another **Project**, for the case that the **Product** could be utilized better within that **Project**.
* If this **License**'s terms were broken by another **Project**, the **Founder** may request modification of its usage within the **Project** that broke its terms, to uphold the terms stated within the **License** 
    * After modification request, if the **Developer** still has not complied within a reasonable timeframe, a formal takedown may be requested or if serious enough instated.
* The **Founder** reserves the right to restrict any usage of content related to the **Product**, if created by the **Founder** of the **Product**, including but not limited to;
    * Mascots or Characters representing the **Product**.
    * Visual or Audio assets distributed with or alongside the **Product**.
    * Custom Fonts, Screenshots, Example Code, which were created by the **Founder** for demonstration in the Documentation, or for Branding/Marketing purposes.
    * If a Commission occurred, and the Artist who created the asset set out their own restrictions.
* Usage restrictions in terms of Assets, relate directly to assets created by the **Founders**, if there are assets from **Contributors**, then their **Sub-License**, if they have one will apply.
    * If the **Contributor** does not have a **Sub-License** for the asset, reach out to the respective **Contributor**, for what you can or cannot do with the asset.

#### 2.) The Contributors Clause

This section is meant to outline the rights in which the **Contributor** is given over the **Product** that this **License** governs. It is split into two sections, **Rights** and **Responsibilities**.

##### Rights of the Contributor

* The **Contributor** may include their own **Sub-License** upon this **Product**, given that it does *not* violate any terms within this **License**, and given that it does *not* violate the nature of Open-Source or Reserved-Source.
* The **Contributors** **Sub-License**, will only be applied to where the **Contributor** was attributed, either in the Codebase, on the Asset, or in the Credits.
* The **Contributors** **Sub-License** must be reviewed by the **Organization** before inclusion, this is to make sure that the **Sub-License** meets the standards the **Organization** has set out.

##### Responsibilities of the Contributor

* If the **Contributor** makes a fork of this **Product**, it must remain Open-Source or Reserved-Source, as long as this **License** governs it.
    * Within that fork, the **License** and any **Sub-Licenses** must remain with it, the fork also must be kept as up to date as possible. This does not prevent branching off of the **Product**, it ensures that the **Contributor** keeps all Licensing and the **Product** are up to date, if they are contributing to the **Product**.
* All code in which a **Contributor** may create must be fully documented in a C# XML adjacent manner.
    * It must include the following to be properly followed;
        * Summary of the Function/Class/Var
        * Param description for each parameter if its a function. (Including what it is, and the variable type)
        * Returns of the Function, including the Type and how.
        * Remarks containing credits that lead back to the given **Contributor**, this goes with the Licensing, alongside attribution this can be used for any last statements about the functionality as well.
* Any code a **Contributor** deems to be Obsolete, should be marked with a sign saying the functionality is *Obsolete and another function should be used instead*, in some way, shape or form. For example C# has `[Obsolete("This is Obsolete please use Y instead")]` as a tag that can be placed with the function, just modify the text in the Obsolete to be appropriate.
* If the **Contributor** is to commit any changes, make sure the Commit has a proper naming convention, and has a bullet point list of changes that the commit makes, try and bundle the changes into one commit.
* The **Contributor** should ensure that the README.md & Wiki documentation is up to date with what was added to the library with a version denoted for when it was added, when pushing out an update.

#### 3.) The Developers Clause

This section is meant to outline the rights in which the **Developer** is given over the **Product** that this **License** governs.

* A **Developer** may request additional functionality to be added, if necessary contact the **Founder** of the **Product**.
    * Check if the **Organization** has another product covering the Functionality your seeking.
        * If not, and the **Founder** is unable to work on it, you may become a **Contributor** to add that function yourself, or create an **Extension** to the **Product**.
* Any **Developer** may contribute to the **Product** as long as they follow the **Contributors Clause**.
* A **Developer** may not modify this **Product** to negatively impact another **Project**.
* The **Product** may be shipped with a **Developers** **Project** given they link back to this **License** in some way shape, and or form.

#### 4.) End-Users Clause

This section is meant to outline the rights in which the **End-User** is given over the **Product** that this **License** governs.

1. If the **End-User** finds any Security Vulneribilities and or Bugs in the **Product**, they must be reported to the **Founder** or **Organization** so it can be resolved as soon as possible.
---
* Copyright 2025 Cecil Libraries Organization and Founder(s) Chaosyr
* Licensed under the Cecil Libraries License (1.1.0)
