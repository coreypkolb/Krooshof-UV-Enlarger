# Krooshof-UV-Enlarger
Open source UV enlarger for alternative photographic processes that depend on UV exposure.
## Warning
UV light is dangerous and could lead to permanent eye damage. Wear appropriate eye protection when using this enlarger. Parts of this build will involve potential risk of electrick shock. Exercise caution and know your limits.
## Introduction
The Krooshnof UV Enlarger is an open source enlarger design that will enable you to enlarge black and white film negatives into cyanotype prints, platinum palladium prints, and prints for other alternative photographic processes that depend on UV light. This repository and the accompanying resources serve as a starting point for you to modify the standard design and build your own enlarger based on Douwe Krooshof's original design.
### Who is this for?
If you are an analogue photographer who is interested in alternative photographic processes and you would like to enlarge your film negatives without making digital negatives, then this project is for you. You must be comfortable with DIY. Maybe you know your way around a soldering iron or you are willing to learn.
### How much will it cost?
This depends on a number of factors like what tools or materials you have already. The price can be as low as $300 USD for the most basic setup. 
## Basic design and components
![Illustration of the Krooshnof UV Enlarger](https://github.com/coreypkolb/Krooshnof-UV-Enlarger/blob/main/images/uv-enlarger-verticle-simple.svg?raw=true)
The Krooshof UV Enlarger is a point source enlarger. UV light, ideally 385nm, starts at the UV LED. The light travels through a collimating fresnel lens, a condensing fresnel lens, the negative, and finally the printing surface.
### Design principles
Until recently photographic texts would state that it is not possible to design a UV enlarger because the glass in enlarger lenses and condenser lenses attenuates too much UV light and available light sources for UV, such as arc lamps, create too much heat to be of any practical use. Now that powerful UV LEDs have become available to the public this is no longer true. The Krooshof UV Enlarger is designed to deliver as much UV light on the photographic paper as possible. With an optical design focused on efficiency and careful material choices it is possible to create a practical UV enlarger with simple tools. There are two guiding principles for the UV enlarger. Firstly the UV enlarger is designed for optical efficiency. The UV enlarger is designed as a point source enlarger to guide as much UV light as possible from the light source into the enlarger lens. Other enlarger designs such as regular condenser enlargers or diffuser enlargers are far less efficient and deliver less light (of any wavelength) to the paper. Secondly the design is optimised for maximum transmission of UV light. The main innovation is the use of thin acrylic fresnel lenses instead of glass condender lenses. Also the choice of enlarger lens, negative holder, and film base play a role in maximising transmission. 
### Components in the light path
#### UV LED
The UV LED is a critical part of the system. For a point source enlarger to work efficiently, the light source must be as small as possible. The light source must be smaller then the rear diameter of the lens. At the same time we need the light source to be very powerful. For this reason a quartz-domed power LED is the best choice. The wavelength of the LED is a compromise between the peak sensitivity of your process (likely shorter, around 365nm for cyanotype) and the transmission of your enlarger lens (this drops off below 400nm). We recommend a wavelength of 385nm. The Learnew LED company produces 100W power LEDs in his wavelength.
#### Collimating and condensing fresnel lenses
The most suitable lenses for the collimating lens and the condenser lens are 2mm think acrylic fresnel lenses. These lenses are readily available online in various focal lengths and diameters and at a reasonable price. Make sure that you buy PMMA acrylic lenses that are not coated to block UV. 
#### Negative holder
When a glass negative carrier is used the glass will block some of the UV light. For the sake of film flatness it can still be helpful to use a glass negative carrier nonetheless.
#### Film base
The film negative is as much part of the optical path as the condensor or the enlarging lens. Film base can block a lot of UV light depending on the base thickness, material and base fog. Films with less base fog en a thinner base transmit more UV light. Negatives that are developed to a lower density also transmit more UV light, but it is not always desireable to develop for less density. Examples of suitable films are Rollei RPX 400 and Rollei Retro 80s. Due to its thick film base Kodak Tmax is less suitable. 
#### Enlarging Lens
The enlargeing lens should be chosen for both its optical quality and its UV transmission. You need to choose the compromise that you are most comfortable with. In general the following factors reduce UV transmission: The total thickness of the glass, the presence of multi-coating designed to block UV light, cemented elements in the design, more elements in the design. For these reasons a modern muti-coated plasmat lens design is not a great choice. For the standard design we can recommend a 4 element dialyte lens, the Kodak Enlarging Ektar 100mm f/4.5 from the early 50s. This lens has 4 air-spaced elements that are relatively thin through the use of lanthanum glass. Single-coated tessar designs are suitable as well. Anecdotally, single-coated 6 element lenses transmit at least 1/3 less UV light than a signle-coated dialyte.
## Choosing a design
The standard design for the Krooshof UV Enlarger is an enlarger that will print up to 6x7 negatives and can make prints from approximately 15cm to 60cm on the short side of the print. You can follow the standard build plan is these parameters meet your needs. If you want to optimise your enlarger for other film formats you can use the Excel calculator to fine tune the design.
## Materials needed

## Tools needed

## Resources
### Excel calculator
### LED 
### PCB design
### Construction of frame

