# ***Work In Progress!!!***
</br>

---

# Filament knowledge
A list and guide for all kinds of filaments usable with a FFF/FDM (Fused Filament Fabrication / Fused Deposition Modeling) 3D printer

<details open>
<summary><h4>Quick links to sections</h4></summary>
  
1. [General Layout](https://github.com/TheAdeo/filament-knowledge#1-general-layout)
2. [Thermoplastic Polymers](https://github.com/TheAdeo/filament-knowledge#2-thermoplastic-polymers)
3. [Variants](https://github.com/TheAdeo/filament-knowledge#3-variants)
4. [Fills](https://github.com/TheAdeo/filament-knowledge#4-fills)
5. [Support Materials and Specialty Filaments](https://github.com/TheAdeo/filament-knowledge#5-support-materials-and-specialty-filaments)
6. [Sintering Ceramics and Metals](https://github.com/TheAdeo/filament-knowledge#6-sintering-ceramics-and-metals)
7. [Drying](https://github.com/TheAdeo/filament-knowledge#7-drying)
8. [Annealing](https://github.com/TheAdeo/filament-knowledge#8-annealing)

</details>

<!-------------------------------------------------------------------------------------------------->
</br>

---

## 1. General Layout
This guide lists separately traditional polymers, fills found in polymeric filaments, support materials, and sintering filaments.  
For each filament there is a description of its properties and for what it is used, then a printing subsections with a range of reccommended temperatures (*Hotend* / *Bed* / *Chamber*) and some general printing reccomendations.  
Other sections at the bottom describe pre or post processing actions in general, with additional specific informations under each polymer subsection that requires them.

<!-------------------------------------------------------------------------------------------------->
</br>

---

## 2. Thermoplastic Polymers

These are the traditional plastic filaments used in 3D printing, spanning from the common ones used by hobbyists to engineering materials used in industrial settings, including also niche polymers rarely seen.  
Plastic filaments can be commonly found with a lot of different options, them being different blends of the original polymer or different non meltable fills added to give different properties to the final material.

</br>

<!-------------------------------------------->
### • PCL
>Polycaprolactone

#### - Characteristics:
It's a biodegradable semi-crystalline polymer that has a very low glass transition temperature and melting point (60°), meaning you can shape it and model it in hot water.  
It is commonly used on 3D pens, but it's also used in the research world as it is biocompatile. It also is semi flexible.
> [!CAUTION]  
> Even though PCL is biocompatible, your printer isn't, so the parts you will print won't be biocompatible, because of the contaminants absorbed during the printing process due to the non sterilized printer.
#### - Printing: (130° / 40° / - )
Requires a firmware modification/setting change to allow extrusion at low temperatures. Very bad at bridging.

</br>

<!-------------------------------------------->
### • PLA
>Polylactic Acid

#### - Characteristics:
It's the most common choice of filament in the DIY 3D printing space, mainly because it's easy to print, but also because it's very stiff. The stiffness is also a drawback, as it can't take impacts well.  
The good mechanical properties are compensated by its very low temperature resistance: if you leave PLA parts in your car under the sun they will deform, the maximum operating temperature is about 40°.
Being semi-crystalline, annealing it would increase it's temperature resistance, but standard PLA is very prone to deforming while annealing.  
It's compostable in industial composter, but not biodegradable.

#### - Printing: (230° / 60° / - )
It's one of the easiest material to print. The only thing that can limit you is the amount of part cooling: PLA wants to be cooled a lot, otherwise overhangs will fail and the print could fail due to zones too soft to print on top.

#### - Variants:
- Blends  
  &nbsp;&nbsp;&nbsp;PLA "pro" or "plus" or "meta" are blends that usually make PLA more impact resistant and more ductile, with the downside of slightly less stiffness.
- Flexible  
  &nbsp;&nbsp;&nbsp;A flexible version, some can even stretch more than other traditional flexible filaments.
- High Temperature  
  &nbsp;&nbsp;&nbsp;HTPLA are blends that increase the temperature resistance to over 100°, most require annealing.
- Silk
- Rainbow
- Dual Extrusion
- Architectural Visualization
- Glow in the Dark
- Color Changing
- Foaming/Lightweight - LW
- Wood
- Stone
- Glitter
- Metal
- Carbon Fibers - CF
- Glass Fibers - GF

</br>

<!-------------------------------------------->
### • PETG
>Polyethylene Terephthalate - Glycole modified

#### - Characteristics:
PETG is a very common amorphous filament, made by substituting the glycole with CHDM during the production of PET, and it's useful for its flexibility and increased temperature resistance compared to PLA. It's very good for living hinges and for parts that will be left outside or in the sun.

#### - Printing: (240° / 60° / - )
It doesn't flow a lot, so it has to be printed a bit slower than PLA, and requires to be dried as it is very hygroscopic.
> [!WARNING]
> PETG has very high adhesion to smooth PEI and glass beds and can damage them, so a release agent (glue or hairspray) is reccommended, textured PEI is also a good choice.

#### - Variants:
- Glow in the Dark
- Color Changing
- Glitter
- Metal
- Carbon Fibers - CF
- Glass Fibers - GF

</br>

<!-------------------------------------------->
### • PCTG
>Polycyclohexylenedimethylene Terephthalate

#### - Characteristics:
A new amorphous polymer that is slowly emerging and putting aside PETG. It is basically the same as its cousin but it has slightly better mechanical properties, but can creep if continuously loaded at higher temps.
Transparent PCTG is one of the clearest filament on the market, perfect for printing translucent pieces.

#### - Printing: (260° / 70° / 45°)
It prints a bit hotter than PETG, but it behaves similarly. If achieving maximum transparency is the goal it should be printed extremely slowly (20 mm/s), very hot (even 280°) and without fan.

#### - Variants:
- Carbon Fibers - CF
- Glass Fibers - GF

</br>

<!-------------------------------------------->
### • PET
>Polyethylene Terephthalate

#### - Characteristics:
One of the most used plastic in the entire world, plastic bottles are made of PET. Not to be confused with PETG, it has a semi-crystalline structure, giving it increased mechanical and thermal properties compared to other polymers of the family. It's stiff, and can be annealed to increase this property even more, while also making it capable of resisting upwards of 100°.

#### - Printing: (290° / 80° / 45°)
PET prints fairly hot, and can even be crystallized while printing in the right conditions. A heated chamber helps, but at 55° and over it starts to strip in the extruder.
Annealing is required to achieve all the properties of this polymer.

#### - Variants:
- Carbon Fibers - CF
- Glass Fibers - GF

</br>

<!-------------------------------------------->
### • PETG-PTFE
>Polyethylene Terephthalate - Glycole modified - Polytetrafluoroethylene 

#### - Characteristics:
PTFE can be added to PETG to decrease its friction, making it ideal to use for gears and sliding parts under 70°.

#### - Printing: (240° / 60° / - )
Printing it slower than regular PETG can prevent warping.
> [!CAUTION]  
> PTFE starts to degrade and offgass at temperatures higher than 250°, but it has been shown to be harmful to birds already at 210°. You should only print filaments that contain PTFE in well ventilated environments and not breathe in any fumes.

</br>

<!-------------------------------------------->
### • OBC
>Olefin block Copolymers

#### - Characteristics:
A copolymer of the polyethylene family, OBC is a semi-crystalline polymer that has low density, good chemical resistance, toughness and some flexibility. It's non-wetting and not hygroscopic.

#### - Printing: (200° / 70° / - )
Requires much lower temperatures than other polyethylene copolymers. Might not require drying as it repels water.

</br>

<!-------------------------------------------->
### • TPE
>Thermoplastic Elastomers

#### - Characteristics:
TPE is the generic name associated with any thermoplastic that behaves like elastic rubber (more specifically, like elastomers). It's a broad term that can be used to describe very different polymers, so it's only used when there isn't a more specific name. Properties will vary, the only common denominator for TPE is that they are flexible and tough.
The hardness is measured with the Shore A or Shore D scale, where higher numbers mean harder. Filaments can be found with hardness spanning from 60A (tyre rubber) to 105A - 60D, with 95A being the most common.

#### - Printing: ( -° / -° / - )
They are tricky to print as the flexibility can easily cause jams in the extruder gears if trying to go too fast. A direct drive extruder is extremely recommended, and due to the low flowability the general rule is to print them as slow as possible. The softer the material the harder it is to print.

</br>

<!-------------------------------------------->
### • TPU
>Thermoplastic Polyurethane

#### - Characteristics:
The most common TPE, it has an extreme durability. You can hammer it or try to cut it with a blade, but TPU will resist that easily. It is highly recommended as a material for tough stuff around the house.
Another advantage is that it's more temperature resistant than other common filaments such as PLA and PETG.

#### - Printing: (240° / 60° / - )
General TPE suggestions still apply.
> [!WARNING]
> TPU has very high adhesion to smooth PEI and glass beds and can damage them, so a release agent (glue or hairspray) is recommended, textured PEI is also a good choice.

#### - Variants:
- Silk
- Foaming/Lightweight - LW  
  &nbsp;&nbsp;&nbsp;Foaming TPU is special because the foaming not only change the density, but also change the hardness of the material: The more the material is foamed, the softer it is.
- Carbon Fibers - CF
- Glass Fibers - GF

</br>

<!-------------------------------------------->
### • TPC
>Thermoplastic Copolyester Elastomers 

#### - Characteristics:
Another TPE, TPC has fairly chemical resistance, being nearly immune to oils and greases, and resistant to some acids. It also has good UV and temperature resistance (in some cases over 130°).

#### - Printing: (240° / 80° / - )

</br>

<!-------------------------------------------->
### • PEBA
>Polyether block Amide 

#### - Characteristics:
PEBA is one of the highest performance TPE. It has low density, superior flexibility, impact resistance and fatigue resistance, and keeps these properties even at -40°, but it's sensible to UV degradation.
The main selling point of PEBA is the high energy return: a PEBA ball will bounce much higher than a ball made from some other TPE.

#### - Printing: (240° / 80° / - )
It is recommended to use brim around the printed object. The best adhesion is achieved on a glass surface with glue, but PEI can also be an option.

</br>

<!-------------------------------------------->
### • SEBS
>Styrene - Ethylene - Butylene - Styrene

#### - Characteristics:
SEBS shines for its resistance to any ambient condition. It has great chemical resistance, UV resistance, low water absorption coupled to being sligtly water repellant.

#### - Printing: (260° / 60° / - )
It is recommended to use brim around the printed object. The best adhesion is achieved on a glass surface with glue, but PEI can also be an option.

</br>

<!-------------------------------------------->
### • EVA
>Ethylene - Vinyl Acetate

#### - Characteristics:
Bio based alternative to the other flexible filaments, EVA has good chemical resistance and low water absorption.

#### - Printing: (240° / 40° / - )
PP-GF adhesive is recommended instead of the typical PVA/PVB glue

</br>

<!-------------------------------------------->
### • PP
>Polypropylene

#### - Characteristics:
Polypropylene is an amorphous thermoplastic that excels in toughness and chemical resistance, its high temperature resistance makes it sterilisable in an autoclave. It's the perfect material for mechanically demanding applications, its lower than average rigidity can be easily improved by fiber fills.
It has a very low density, meaning that a 1 kg spool will contain more material than a similar PLA spool.
A very good choice for everyday household objects, its only downsides are price and printability.

#### - Printing: (250° / 60° / - )
It is atypically hard to print for a plastic that doesn't require an heated chamber. It doesn't flow well, requiring low speeds to prevent tears in the print, and its chemical resistance makes it harder to print. Polypropylene only likes to stick to itself: PP packing tape is the recommended bed surface, for other beds PP specific glues are a must because normal PVA/PVB glue doesn't stick.

#### - Variants:
- Carbon Fibers - CF
- Glass Fibers - GF  
  &nbsp;&nbsp;&nbsp;Glass Fibers reinforced PP is notable because it sticks to the bed even less than regular PP, so a specific PP-GF adhesive must be used.
- Hollow Glass Spheres  

</br>

<!-------------------------------------------->
### • PHA / PHB
>Polyhydroxyalkanoates / Polyhydroxybutyrate

#### - Characteristics:
PHA are a big family of semi-crystalline polymers that are biologically syntetized from bacteria, and are 100% biodegradable, so they are one of the most "green" filaments available. They are easy to print and can be considered a PLA replacement with generally better properties. The biggest drawbacks is the slightly higher cost that's caused by the limited availability on the market, due to low customer knowledge about them. PHA can also be found blended with PLA. PHB is one member of the PHA family.
PHA usually have a higher thermal resistance than PLA, while being slightly less stiff but less brittle.

#### - Printing: (210° / 60° / - )
Just as printable as PLA, so really easy materials to work with.

</br>

<!-------------------------------------------->
### • SBC
>Styrene Butadiene Copolymer

#### - Characteristics:
SBC is a family of elastomers that offers high clarity and transparency with high toughness. It is flexible, but with a high shore D hardness.

#### - Printing: (260° / 100° / 60°)
The usual flexible caveats apply, but less than usual due to the higher shore hardness.
Being similar to ABS makes it also easier to print with an heated chamber.

</br>

<!-------------------------------------------->
### • ABS
>Acrylonitrile Butadiene Styrene

#### - Characteristics:
One of the oldest 3D printing filaments, ABS is an amorphous polymer with a high thermal resistance and toughness, but not great stiffness. It is very easy to sand, cut, and post process in general, and can be smoothed with acetone, so it's perfect for prototypes and cosplay items. A lot of ABS are blended for easier printability, so to determine the real properties of the filament one has to first find out if the filament they're considering is similar to injection molding abs ("""pure""") or if it's reformulated with additives to make it more printable (PETG can be used for that).
Injection molding ABS has been available for the longest as it's just IM pellets extruded into filement. It has a nasty small during printing due to the styrene fumes, is very needy of high temperatures, and has the best thermal properties (around 90°).
Blended ABS is much easier to print but loses in thermal resistance (as low as 60°), acting like just a more flowable PETG.

#### - Printing: (280° / 100° / 80°)
ABS has a bad reputation of being very hard to print due to the requirement of a heated chamber, ideally around 80°. Considering that no common consumer 3D printer can reach that temperature, everyone prints it in suboptimal conditions and suffers from high warping.
In general the hotter the chamber is the better ABS will print, requiring more and more cooling and warping less and less the higher you go. Some very blended ABS can be barely printable with just a cardboard box over the printer, reaching around 40°, while at temperatures reached by insulated Vorons (around 60°) "pure" abs starts to be tamable, but only at lower speeds, really low fan, and high bed temperatures (110°+) to compensate.
The same applies to hotend temperature: blended abs can be printed even at 240°, while "pure" ABS is barely able to extrude that cold, reaching ideal layer adhesion at 270°-280° (under the hypotesis of good chamber temperature).

#### - Variants:
- Blends  
  &nbsp;&nbsp;&nbsp;The names "pro" or "plus" are indicative of blends, but unfortunately a lot of manufacturers blend their ABS a lot without saying it explicitly. Some ways to be sure that a generic ABS is blended is to look at the marketing material and see if "low smell", "low warp", "easier to print" are mentioned.
- Architectural Visualization
- Glow in the Dark
- Stone
- Glitter
- Carbon Fibers - CF
- Glass Fibers - GF
- Aramid/Kevlar Fibers

</br>

<!-------------------------------------------->
### • ASA
>Acrylonitrile Styrene Acrylate

#### - Characteristics:
ASA is an amorphous polymer that is one monomer away from ABS, so it shares most of its characteristics with it. One notable difference is that ASA offers UV resistance, so it's more suitable for outdoor environments and parts that will be exposed to the sun.

#### - Printing: (280° / 100° / 80°)
Same printing characteristics as ABS. One notable thing is that ASA is one of the polymers with the highest melt flow rate, making it especially suitable for achieving max volumetric flow rate and fast printing.

#### - Variants:
- Lightweight - LW
- Carbon Fibers - CF
- Glass Fibers - GF
- Aramid/Kevlar Fibers

</br>

<!-------------------------------------------->
### • HIPS
>High Impact Polystyrene

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • BVOH
>Butenediol Vinyl Alcohol Copolymer

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • HDPE
>High-density Polyethylene

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • LDPE
>Low-density Polyethylene

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • PMMA
>Poly(Methyl Methacrylate)

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • PVA
>Polyvinyl Alcohol

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • PVB
>Polyvinyl Butyral

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • PVC
>Polyvinyl Chloride

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • PVDF
>Polyvinyl Fluoride

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • FEP
>Please no

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • PPS
>Polyphenylene Sulfide

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-cf-gf

</br>

<!-------------------------------------------->
### • PA
>Polyamides

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-6-66-11-12-cf-gf-hgs

</br>

<!-------------------------------------------->
### • PPA
>Polyphthalamide

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-cf-gf

</br>

<!-------------------------------------------->
### • PC-ABS
>Polycarbonate - Acrylonitrile Butadiene Styrene

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • PC
>Polycarbonate

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-cf-gf-blend

</br>

<!-------------------------------------------->
### • PC-PBT
>Polycarbonate - Polybutylene Terephthalate 

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-cf-gf-bn

</br>

<!-------------------------------------------->
### • PC-PTFE
>Polycarbonate - Polytetrafluoroethylene

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • PBT
>Polybutylene Terephthalate

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • PPE
>Polyphenylene Ether

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • PPE-PS
>Polyphenylene Ether - Polystyrene

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • PPE-PA
>Polyphenylene Ether - Polyamide

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • PSU
>Polysulfones

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • PPSU/PPSF
>Polyphenylsulfone

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • PES/PESU
>Polyethersulfone

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • POM
>Polyoxymethylene

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • FEP
>Fluorinated Ethylene Propylene

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • PEKK
>Polyetherketoneketone

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-a-c-cf-ceramic

</br>

<!-------------------------------------------->
### • PEEK
>Polyetheretherketone

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-cf-gf

</br>

<!-------------------------------------------->
### • PEEK-PTFE
>Polyetheretherketone - Polytetrafluoroethylene

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • Polyketone
>Polyeketone

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • Ultem 9085/PEI
>Polyetherimide

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-cf-gf-bn

</br>

<!-------------------------------------------->
### • Ultem 1010/PEI
>Polyetherimide

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-cf-gf

</br>

<!-------------------------------------------->
### • TPI
>Thermoplastic Polyimide

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • LCP
>Liquid Crystal Polymers

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
<!-------------------------------------------------------------------------------------------------->
---



## 3. Variants

Polymeric filaments can be modified, usually with additives, to change their properties with a specific objective in mind. These variants of the traditional raw polymers can be only aesthetic or they can serve useful functions.

</br>

<!-------------------------------------------->
### • Silk
Some people like shiny stuff, so to get a shiny look for your printed part some additives are used to give the desired look to the filament.
An effect on the mechanical properties is that the material loses layer adhesion and absorbs moisture faster. A good tip is to increase the hotend temperature compared to the pure filament.

### • Rainbow
Raimbow filaments are just spools where the pigments are dumped one after the other during extrusion, to achieve a gradual transition between a lot of different colors.

### • Dual Extrusion
Different colors can be extruded at the same time to achieve a filament that has two, three, or even four sides, makind the printed part look like it's a different color depending from where you look.

### • Architectural Visualization
Archiviz filaments are usually made by adding powder and colorants to achieve a stone/sand/plaster/etc. look, perfect for showing off architectural pieces with a more true to life appearance.
> [!WARNING]  
> The powders used are abrasive and will wear down brass and copper nozzles. A hardened steel or tungsten carbide nozzle is recommended.

### • Glow in the Dark
Glow in the dark pigments can show throug the base polymer, absorbing UV light during the day and releasing it once dark. Usually green/blue, sometimes red can also be found.
> [!WARNING]
> The pigments used are abrasive and will wear down brass and copper nozzles. A hardened steel or tungsten carbide nozzle is recommended.

### • Color Changing
Pigments that change color when heat is applied are used to give this property to the printed parts.

### • Foaming/Lightweight - LW
Lightweight filaments are modified to foam at high temperatures, releasing gases that form microbubbles make the plastic exiting the nozzle expand upwards of 50%. After tuning the temperature to achieve the desired level of expansion, lowering the extrusion multiplier is needed to combat the overextrusion. This results in much lighter parts, with the caveat of extremely reduced rigidity and strenght, these filaments are perfect for RC aircrafts. Foaming TPU also to change its hardness when expanding.

### • ESD Safe - ESD
Carbon in various forms (carbon black powder, carbon nanotubes, etc...) can be added to lower significantly the surface resistivity of the printed parts, making them suitable for not accumulating electric charges and preventing electic shocks, perfect for electronic enclosures.
> [!CAUTION]
> Carbon Nanotubes (CNT, not to be confused with carbon fibers) are extremely dangerous to the human body, the safe level set by the CDC is only 1µg/m³, 10 times less than arsenic, 50 times less than lead and 10000 times less than hidrogen cyanide.
>
> "Occupational exposure to CNTs is associated with biomarkers of early effect for fibrosis, inflammation, oxidative stress, and cardiovascular responses in workers [Beard et al. 2018]."
>
> Printing, sanding, cutting, and in generatl working with CNT containing filaments *will* result in some paricles becoming airborne, posing an extreme health risk.
> It is ***strongly advised*** to ***never*** use CNT containing filaments, and instead use ESD safe filaments that use safer additives.
> Known CNT containing filaments are the ESD safe products from 3DXTech and Polymaker.
>
> https://www.cdc.gov/niosh/docs/2013-145/pdfs/2013-145.pdf
>
> https://www.cdc.gov/niosh/docs/2022-153/2022-153.pdf?id=10.26616/NIOSHPUB2022153
>
> https://link.springer.com/article/10.1007/s11051-020-4750-8

### • Fire Resistant - FR/V0
For some use cases fire resistant materials are needed. These polymers are modified to meet the UL94 V0 specification, or if a standardized test has not been made they are just labeled as "Fire Resistant (FR)".
This does not mean that the part will not burn and melt in a fire, but it means that a flame will not propagate. More specifically the UL94 V0 spec requires burning to stop within 10 seconds on a vertical specimen, and drips are allowed as long as they are not inflamed.

<!-------------------------------------------------------------------------------------------------->
</br>

---



## 4. Fills

Particles can be mixed inside the polymeric matrix to change the feel or the properties of the printed parts. As with variants (discussed above) the effect can be aesthetic or functional.
Fills will significantly increase the moisture absorption of the filament as they provide a path for water to the core of the filament, so careful drying is mandatory.
> [!WARNING]  
> Nearly all fills are abrasive and will ruin copper and brass nozzles, hardened steel or tungsten carbide nozzles are recommended.
> CHT or other flow enhancing geometries are also more prone to clogs so they should be avoided.
> Long fiber fills are especially prone to clogs, so a 0.5mm or bigger nozzles are recommended.

</br>

<!-------------------------------------------->
### • Wood
Wood fibers are a decorative fill used to mimic the effect of wooden parts, it can be enhanced by painting the final parts with wood stains to bring out the fake wood grain.
It creates various printing artifacts that can actually improve the "wooden" look.

#### - Physical effects:
- Lower flow rate
- Lower layer adhesion and part strenght


### • Stone
Powdered stone usually used to mimic real stones in archviz, available in almost all kinds of finishes.

#### - Physical effects:
- Lower layer adhesion and part strenght


### • Glitter
Very fine glitter is mixed in the filament to give a "sparkly" look. It can help reduce the visibility of printing artifacts.

#### - Physical effects:
- None.
> [!NOTE]  
> Glitter is one of the lower abrasion fills, so it can usually be printed with any nozzle, but faster wear is still expected.


### • Metal
High concentrations by weight (60%+) of metal powder are used to give a metal look to the parts and increase the weight. Side effects are increased electrical conductivity and the ability to oxidize the parts for a rusted and worn look, perfect for cosplay items, replicas, and to hide the 3D printed look.

#### - Physical effects:
- Significantly higher weight
- Rusting
- Electrical conductivity
- Lower layer adhesion and part strenght
- In some cases radiation shielding


### • Carbon Fibers - CF
Short milled/powdered carbon fibers can improve the look of the printed parts with a premium fuzzy external look, while long chopped carbon fibers can also dramatically change the physical properties of the printed parts.

#### - Physical effects:
- Higher crystallization rates for semi-crystalline polymers
- Higher thermal resistance (elastic and flextural modulus loss are compensated by the stiff fibers, bringing the failure temps higher)
- Increased stiffness
- Significantly lower layer adhesion
- Increased brittleness
- Significantly reduced warping during printing
- Higher dimensional accuracy
> [!TIP]  
> The longer the fibers are the more the effects will be felt. Cheap CF filled filaments will have fibers so short that they will not give any physical benefit, but just the fuzzy look.


### • Glass Fibers - GF
Glass fibers are very similar to carbon fibers, just with a higher density that usually results in a higher total density of the filament. Compared to CF manufacurers use fibers long enough to give physical benefits.

#### - Physical effects:
- Higher crystallization rates for semi-crystalline polymers
- Higher thermal resistance (elastic and flextural modulus loss are compensated by the stiff fibers, bringing the failure temps higher)
- Increased stiffness, but less than CF
- Significantly lower layer adhesion
- Increased brittleness, but tougher than CF, so they are an alternative to consider for parts subject to impacts
- Significantly reduced warping during printing
- Higher dimensional accuracy


### • Aramid/Kevlar Fibers
Aramid fibers have a low friction coefficient and high wear resistance, so they can ba used for parts that will be subject to sliding action like gears.

#### - Physical effects:
- Low friction coefficient
- Reduced wear
- Lower layer adhesion
- Reduced warping during printing
- Higher dimensional accuracy


### • Hollow Glass Spheres
Hollow glass micro-spheres are used to decrease the density of the filament, for a light and stiff alternative to the base polymer.

#### - Physical effects:
- Lower density
- Reduced wear
- Increased stiffness
- Lower layer adhesion
- Reduced warping during printing
- Higher dimensional accuracy


### • Ceramic
Ceramic filled filament must not be confused with ceramic filament for sintering, that is explored in a [following section](https://github.com/TheAdeo/filament-knowledge#6-sintering-ceramics-and-metals).
Ceramic powder is used to increase the surface hardness and increase the machinability of the parts as a post processing step. Usually used in electronics assembly and fabrication facilities.

#### - Physical effects:
- Increased surface hardness
- Reduced thermal expansion
- Increased stiffness
- Increased thermal resistance
- Lower layer adhesion
- Reduced warping during printing
- Higher dimensional accuracy


<!-------------------------------------------------------------------------------------------------->
</br>

---



## 5. Support Materials and Specialty Filaments

Specialty filaments formulated by manufacturerts to cater to be used as a support for other filaments, or other niche uses.

</br>

<!-------------------------------------------->
### • Dissolvable Supports
Filaments that after printing can be dissolved in water or a solvent (usually limonene), really useful to achieve complex geometries that would require supports normally impossible to remove.
> [!IMPORTANT]  
> A printer with multiple hotends is mandatory (toolchanger/idex/dual hotend...) to avoid contamination of the part that would result in a catastophical failure when dissolving the supports.

### • High Temp Supports
Support filaments compatible with the extremely high chamber and nozzle temperatures required for HT polymers. Useful to avoid the fusing issues of same material supports.

### • Polypropylene Supports
Support materials specifically formulated to bond enough with Polypropylene, as it is a very inert material that usually doesn't like sticking to other materials.

### • Iglidur Low Friction Polymers
Special class of polymers developed by German manufacturer Igus to have an especially low coefficient of friction, available in different temperature ranges. 

### • Conductive Filaments
Filaments with enough filler (usually carbon based) to let the final printed parts to conduct electricity. Conductive enough to trigger circuits, but too resistive to carry a significant amount of current.

<!-------------------------------------------------------------------------------------------------->
</br>

---



## 6. Sintering (ceramics and metals)

FDM printing can be used not only for creating finished parts, but it can be used to deposit materials in the desired shape, to then sinter to achieve bonding and the final characteristics of the piece. Metals or ceramics can be dispersed in powdered form in very large quantities (50%-95%) inside a polymeric filament that is used just to hold the shape of the part before sintering. The rest of the process is done in a furnace, usually with a first step to burn the plastic away and a second hotter step to sinter (cook and bind) the particles togheter. This requires extremely high temps, between 500° and 1500°, depending on the material.

</br>

<!-------------------------------------------->
### • Clay

### • Basalt

### • Silicone Carbide

### • Silicone Nitride

### • Zirconium Silicate

### • Alumina

### • Boron Carbide

### • Borosilicate Glass

### • Aluminium 6061

### • Bronze

### • Copper

### • Iron

### • Tool Steel

### • Stainless steel 316L

### • Stainless steel 17-4 PH

### • Tungsten

### • Titanium 64-5

### • Inconel 718

<!-------------------------------------------------------------------------------------------------->
</br>

---



## 7. Drying
Wet filament causes oozing and stringing while printing, producing also rough surfaces and messing the extrusion multiplier calibration, to combat this it's best to always print dry filament.

During the manufacturing process filament is cooled in water baths after being extruded, and never dried again. Even if the spool came in a "sealed" bag with some dessicant it's probably wet.
Moisture can and does pass through plastic bags, that's why industrial filaments come in bags with a metallic liner.
A lot of commonly printed filaments are hygroscopic (like PETG, PA, PC), so it's highly recommended to dry every spool in a filament dryer / airfryer / convection oven at a temperature slightly below (5-10°) the glass transition temperature (Tg) of the filament for some hours.
Vacuum drying doesn't work well without heat, as the water molecules attach themselves to the polymer chains, requiring energy to separate.

Fiber fills are extremely bad in this regard, they make even the least hygroscopic filament very prone to taking moisture. This is because the fibers create channels in the material through which the water can penetrate deeply, so for filled filaments drying is a must.

A cheap solution if you don't have the money for an airfryer or a dedicated oven is to put the spool on the printer bed covered with a cardboard box with some holes on top. Set the bed 5-10° below the Tg of the material and close the chamber if possible. This can help for most materials, but for the more hygroscopic ones proper drying can be still needed.

The worst offenders, like PA, filled PC, and most high temperature polymers, can absorb water so quickly that printing from a dry box (possibly heated) is required, as they can become extremely wet even during a short print.

<!-------------------------------------------------------------------------------------------------->
</br>

---

## 8. Annealing
Description TODO
