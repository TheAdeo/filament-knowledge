# ***Work In Progress!!!***
</br>

---

# Filament knowledge
A list and guide for all kinds of 3D printing filaments

<details open>
<summary><h4>Quick links to sections</h4></summary>
  
1. [General Layout](https://github.com/TheAdeo/filament-knowledge/edit/main/README.md#1-general-layout)
2. [Thermoplastic Polymers](https://github.com/TheAdeo/filament-knowledge#2-thermoplastic-polymers)
3. [Variants](https://github.com/TheAdeo/filament-knowledge/edit/main/README.md#3-variants)
4. [Fills](https://github.com/TheAdeo/filament-knowledge/edit/main/README.md#4-fills)
5. [Support Materials and Specialty Filaments](https://github.com/TheAdeo/filament-knowledge/edit/main/README.md#5-support-materials-and-specialty-filaments)
6. [Sintering Ceramics and Metals](https://github.com/TheAdeo/filament-knowledge/edit/main/README.md#6-sintering-ceramics-and-metals)
7. [Drying](https://github.com/TheAdeo/filament-knowledge/edit/main/README.md#7-drying)
8. [Annealing](https://github.com/TheAdeo/filament-knowledge/edit/main/README.md#8-annealing)

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
It's a biodegradable semy-crystalline polymer that has a very low glass transition temperature and melting point (60°), meaning you can shape it and model it in hot water.  
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
### • PHA
>Polyhydroxyalkanoates

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • PHB
>Polyhydroxybutyrate

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • CP
>Liquid Crystal Polymers

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • BC
>Styrene Butadiene Copolymer

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
### • ABS
>Acrylonitrile Butadiene Styrene

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-cf-gf-kf-blend-glow

</br>

<!-------------------------------------------->
### • ASA
>Acrylonitrile Styrene Acrylate

-cf-gf-kf-lw

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

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
-6-66-11-12-cf-gf

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
### • BVOH
>Butenediol Vinyl Alcohol Copolymer

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

</br>

<!-------------------------------------------->
<!-------------------------------------------------------------------------------------------------->
---



## 3. Variants

Variants here

</br>

<!-------------------------------------------->
### • Silk

### • Rainbow

### • Dual Extrusion

### • Architectural Visualization

### • Glow in the Dark

### • Color Changing

### • Foaming/Lightweight - LW

### • ESD Safe - ESD

### • Fire Resistant - FR/V0

<!-------------------------------------------------------------------------------------------------->
</br>

---



## 4. Fills

Fills here

</br>

<!-------------------------------------------->
### • Wood

### • Stone

### • Glitter

### • Metal

### • Carbon Fibers - CF

### • Glass Fibers - GF

### • Aramid/Kevlar Fibers

### • Hollow Glass Spheres

### • Ceramic

<!-------------------------------------------------------------------------------------------------->
</br>

---



## 5. Support Materials and Specialty Filaments

Specialty stuff here

</br>

<!-------------------------------------------->
### • 3DXtech Aquatek X1

### • 3DXtech LTS

### • 3DXtech MTS

### • 3DXtech HTS1

### • 3DXtech HTS2

### • IMS Aquasys 120

### • IMS Aquasys 180

### • PPprint P-support 279

### • Iglidur stuff

### • Multi3D Electrifi

<!-------------------------------------------------------------------------------------------------->
</br>

---



## 6. Sintering (ceramics and metals)

Sintering stuff
</br>

<!-------------------------------------------->
### • Silicone carbide

### • Silicone nitride

### • Zirconium 

### • Alumina

### • Boron Carbide

### • Borosilicate Glass

### • Stainless steel 316L

### • Stainless steel 17-4

<!-------------------------------------------------------------------------------------------------->
</br>

---



## 7. Drying
Wet filament causes oozing and stringing while printing, producing also rough surfaces and messing the extrusion multiplier calibration, to combat this it's best to always print dry filament.

During the manufacturing process filament is cooled in water baths after being extruded, and never dried again. Even if the spool came in a "sealed" bag with some dessicant it's probably wet.
Moisture can and does pass through plastic bags, that's why industrial filaments come in bags with a metallic liner.
A lot of commonly printed filaments are hygroscopic (like PETG, PA, PC), so it's highly recommended to dry every spool in a filament dryer / airfryer / convection oven at a temperature slightly below (5-10°) the glass transition temperature (Tg) of the filament for some hours.
Vacuum drying doesn't work without heat, as the water molecules attach themselves to the polymer chains, requiring energy to separate.

Fiber fills are extremely bad in this regard, they make even the least hygroscopic filament very prone to taking moisture. This is because the fibers create channels in the material through which the water can penetrate deeply, so for filled filaments drying is a must.

A cheap solution if you don't have the money for an airfryer or a dedicated oven is to put the spool on the printer bed covered with a cardboard box with some holes on top. Set the bed 5-10° below the Tg of the material and close the chamber if possible. This can help for most materials, but for the more hygroscopic ones proper drying can be still needed.

The worst offenders, like PA, filled PC, and most high temperature polymers, can absorb water so quickly that printing from a dry box (possibly heated) is required, as they can become extremely wet even during a short print.

<!-------------------------------------------------------------------------------------------------->
</br>

---

## 8. Annealing
Description
