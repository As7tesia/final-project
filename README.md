# Design Doc

## Goal
I want to continue detailing my gothic building, and create a cool interior environment for it.

## Inspiration/References:
![1.jpg](Media/1.jpg)
![2.jpg](Media/2.jpg)
![3.jpg](Media/3.jpg)

## Specifications:
Some features I would like to recreate from the concept art:
- Procedural Staircase
- Vegetation (flowers, veins)
- butterfly flocking animation (if I have time)
- lighting scenario
- Book shelves
- (maybe) character statues
I also want to add in an idea I had from before. The building will be in 2 parts. Bottom floor is going to be bookshelves underneath the staircase. Then above it are the pretty windows.

## Techniques:
- Lot of procedural modeling
- curve based vegetation tool
- procedural flocking animation

## Design:
Seems quite straight forward so I don't think there's a need for diagrams.

# Milestone 1 & 2

### Overview
![MS2_1.jpg](Media/MS2_1.jpg)

### Converted from Regular Polygon Based -> Arbitrary Curve Based
![Curve1.jpg](Media/MS3_1.jpg)
![Curve2.jpg](Media/MS3_2.jpg)

### Pinnacle
![MS2_4.jpg](Media/MS2_4.jpg)

Automatically adapt to the polygon shape of the pillar

### Fence
![MS2_5.jpg](Media/MS2_5.jpg)

### Border Decoration
![MS2_6.jpg](Media/MS2_6.jpg)

Automatically adapt to the shape of the building, with custom curve profile.

# Final Submission

### Final Render
![Render1.jpg](Media/UERender2.png)
Rendered in UE5, used existing materials and foliages, but I compiled the landscape and did the lighting myself.


### Divided Roof
![Roof1.jpg](Media/MS3_Roof_1.jpg)
![Roof2.jpg](Media/MS3_Roof_2.jpg)
![Roof3.jpg](Media/MS3_Roof_3.jpg)


### Window Decoration
![Window1.jpg](Media/MS3_Window_Decor_1.jpg)

### Update Parameter Interface
![Window1.jpg](Media/MS3_Interface.jpg)

### Post mortem

I was actually really far away from what I wanted to achieve at first, the complexity of the building just made me work really slow. Even though I feel like I've spent decent amount of hours into working on this in the last milestonie but the difference in the overall look is just really little.

Also I wanted to get Houdini Engine in Unreal working so the parameters could be adjusted realtime, however, Houdini Engine turned out to be really buggy and slow that the geometry would be broken and iteration speed would be even slower compared to just simply importing and almebic file.

