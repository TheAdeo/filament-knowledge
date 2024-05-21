# ***Work In Progress!!!***
</br>

---

# Filament knowledge
A list and guide for all kinds of 3D printing filaments

<details>
<summary>Quick links to sections</summary>
List with links to sections
</details>

<!-------------------------------------------------------------------------------------------------->
</br>

---

## General Layout
This guide lists separately traditional polymers, fills found in polymeric filaments, support materials and sintering filaments.  
For each filament there is a description of its properties and for what it is used, then a printing subsections with a range of reccommended temperatures (*Hotend* / *Bed* / *Chamber*) and some general printing reccomendations.  
Other sections at the bottom describe pre or post processing actions in general, with additional specific informations under each polymer subsection that requires them.

<!-------------------------------------------------------------------------------------------------->
</br>

---

## Thermoplastic Polymers

These are the traditional plastic filaments used in 3D printing, spanning from the common ones used by hobbyists to engineering materials used in industrial settings, including also niche polymers rarely seen.  
Plastic filaments can be commonly found with a lot of different options, them being different blends of the original polymer or different non meltable fills added to give different properties to the final material.

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

### PETG
>Polyethylene Terephthalate - Glycole modified

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-cf-glow-metal

<!-------------------------------------------->
### PCTG
>Polycyclohexylenedimethylene Terephthalate

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-cf-gf

<!-------------------------------------------->
### PET
>Polyethylene Terephthalate

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-cf-gf-ht

<!-------------------------------------------->
### PETG-PTFE
>Polyethylene Terephthalate - Glycole modified - Polytetrafluoroethylene 

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### OBC
>Olefin block Copolymers

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### TPU
>Thermoplastic Polyurethane

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-cf-gf-silk-lw

<!-------------------------------------------->
### TPE
>Thermoplastic Elastomers

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-pctpe

<!-------------------------------------------->
### TPC
>Thermoplastic Copolyester Elastomers 

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### PEBA
>Polyether block Amide 

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### TPS/SEBS
>Styrene - Ethylene - Butylene - Styrene

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### EVA
>Ethylene - Vinyl Acetate

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### PP
>Polypropylene

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-cf-gf-hgs-lw

<!-------------------------------------------->
### PP-PE
>Polypropylene - Polyethylene

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### PHA
>Polyhydroxyalkanoates

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### PHB
>Polyhydroxybutyrate

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### LCP
>Liquid Crystal Polymers

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### SBC
>Styrene Butadiene Copolymer

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### ABS
>Acrylonitrile Butadiene Styrene

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-cf-gf-kf-blend-glow

<!-------------------------------------------->
### ASA
>Acrylonitrile Styrene Acrylate

-cf-gf-kf-lw

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### HIPS
>High Impact Polystyrene

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### HDPE
>High-density Polyethylene

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### LDPE
>Low-density Polyethylene

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### PMMA
>Poly(Methyl Methacrylate)

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### PVA
>Polyvinyl Alcohol

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### PVB
>Polyvinyl Butyral

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### PVC
>Polyvinyl Chloride

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### PVDF
>Polyvinyl Fluoride

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### PPS
>Polyphenylene Sulfide

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-cf-gf

<!-------------------------------------------->
### PA
>Polyamides

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-6-66-11-12-cf-gf

<!-------------------------------------------->
### PPA
>Polyphthalamide

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-cf-gf

<!-------------------------------------------->
### PC-ABS
>Polycarbonate - Acrylonitrile Butadiene Styrene

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### PC
>Polycarbonate

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-cf-gf-blend

<!-------------------------------------------->
### PC-PBT
>Polycarbonate - Polybutylene Terephthalate 

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-cf-gf-bn

<!-------------------------------------------->
### PC-PTFE
>Polycarbonate - Polytetrafluoroethylene

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### PBT
>Polybutylene Terephthalate

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### PPE
>Polyphenylene Ether

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### PPE-PS
>Polyphenylene Ether - Polystyrene

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### PPE-PA
>Polyphenylene Ether - Polyamide

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### PSU
>Polysulfones

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### PPSU/PPSF
>Polyphenylsulfone

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### PES/PESU
>Polyethersulfone

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### POM
>Polyoxymethylene

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### PEKK
>Polyetherketoneketone

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-a-c-cf-ceramic

<!-------------------------------------------->
### PEEK
>Polyetheretherketone

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-cf-gf

<!-------------------------------------------->
### PEEK-PTFE
>Polyetheretherketone - Polytetrafluoroethylene

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### Ultem 9085/PEI
>Polyetherimide

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-cf-gf-bn

<!-------------------------------------------->
### Ultem 1010/PEI
>Polyetherimide

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

#### - Variants:
- todo vars  
  &nbsp;&nbsp;&nbsp;todo vars
-cf-gf

<!-------------------------------------------->
### TPI
>Thermoplastic Polyimide

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### PAI
>Polyamide-Imides

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
### BVOH
>Butenediol Vinyl Alcohol Copolymer

#### - Characteristics:
todo char

#### - Printing: (-° / -° / - )
todo printing

<!-------------------------------------------->
<!-------------------------------------------------------------------------------------------------->
</br>

---

## Variants
### Silk

### Rainbow

### Dual Extrusion

### Architectural Visualization

### Glow in the Dark

### Color Changing

### Foaming/Lightweight - LW

### ESD Safe - ESD

### Fire Resistant - FR/V0

<!-------------------------------------------------------------------------------------------------->
</br>

---

## Fills
### Wood

### Stone

### Glitter

### Metal

### Carbon Fibers - CF

### Glass Fibers - GF

### Aramid/Kevlar Fibers

### Hollow Glass Spheres

### Ceramic

<!-------------------------------------------------------------------------------------------------->
</br>

---

## Support Materials
### 3DXtech Aquatek X1

### 3DXtech LTS

### 3DXtech MTS

### 3DXtech HTS1

### 3DXtech HTS2

### IMS Aquasys 120

### IMS Aquasys 180

### PPprint P-support 279

### Iglidur stuff

TBD how to add igus filaments

<!-------------------------------------------------------------------------------------------------->
</br>

---

## Sintering (ceramics and metals)
### Silicone carbide

### Silicone nitride

### Zirconium 

### Alumina

### Boron Carbide

### Stainless steel 316L

### Stainless steel 17-4

<!-------------------------------------------------------------------------------------------------->
</br>

---

## Drying
Description

<!-------------------------------------------------------------------------------------------------->
</br>

---

## Annealing
Description
