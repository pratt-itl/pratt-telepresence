---
layout: process
title: 2. Record & Archive
category: Technical
subcategory: 
description: Kaltura, Big Blue Button
order: 3
---

<hr class="homebreak">

## 2. Record & Archive
**Learning Time : Approx. 15min**.

------



<strong id="introduction">Introduction</strong>

Automatization and efficiency with unparalleled precision are the cornerstones of the Zund Digital Cutting system. Its multi axis, conveyor belt hold down system, with seven different tooling options with a range of various blades and bits allow for a variety of different materials spanning from soft to hard, in a range of various sizes - most notably large format!

At first glance the Zund Digital Cutter can be thought of as being located in the middle ground between a laser cutter and a CNC mill, but it's this middle zone and the material offerings, stock sizes and precision that renders this a unique and powerful tooling option.



------

<strong id="material">Material</strong>

The Zund can handle a range of materials but principally should be utilized as a tool for those materials that are not suitable for a laser cutter or a CNC mill. Broadly speaking this may cover materials with an aerated interior, materials that react or break down with heat, materials that exceed a laser bed or those that would be too difficult to clamp down to a CNC mill. 

The benefits of the Zund Blade system is that the tooling operation does not introduce heat or burn to the material resulting in no off gassing, burn mark, loss of precision or other unintended negatives that heat introduction to materials produces. 

The larger list of *only some* of the suitable materials for use on the Zund are as follows:

- Fabrics
- Films
- Meshes
- Open Cell Foams
- Felt
- Vinyl
- Thick Stock Papers
- Closed Cell Foams
- Cardboard
- Foam Board
- Corrugated Plastic Boards
- Honeycomb Sandwich
- Plastics
- Styrene
- Rubbers
- Acrylic
- Expanded PVC Board
- Plywood
- Metal Composites
- Soft Metals



------

<strong id="capabilities">Capabilities</strong>

Printing & Cutting 

Expanding the offering beyond precision cutting the Zund workflow works in concert with 2D printing allowing for graphic artwork to be output on 2 ply and 4 ply Bristol as well as all of the fabrics and papers currently offered within the 2D output center. Integration of printing and cutting as a folded workflow should include registration dots in order to sync the printed artwork with the vector cut file.

Roll Cutting

The G3 Zund 3200 Digital Cutting system has the feature for roll stock cutting allowing for a theoretical infinite y-axis cutting dimension. Utilizing roll stock goods with either edge or dot registration in conjunction with the conveyor bed and vacuum hold down provides precision continuous cutting over greater than 12’ lengths or maximizes efficiency by only having to load one material good and continuously feeding new, to cut multiples. 

Registration Dots

On board cameras allow for the recognition of registration dots from printed materials in order to sync printed, physical content, to digital vector cut files. The registration dots must be 1/4" diameter in width, solid black, at least 5 on the sheet good and asymmetrically placed. These dots will automatically sync the digital file to the physical ensuring the correct orientation. 

Border Recognition

On board cameras allow for the recognition of edge conditions of sheet goods in order to align digital cut file jobs to the physical material orientations and edges. Border Recognition is also utilized in flip cutting operations. 

Flip Cutting

There are a number of automated procedures that have been configured with the Zund software, one of which is the implementation of flip cutting operations for tooling on the front and back sides of material.

V-Cutting and Beveling

Producing angular cuts, edges or grooves utilizes the v-cutting tool allowing for a range of precision angles to be achieved - Chamfering, beveling, groove cutting or mitering. 







> *\* The Zund is not a laser cutter and it's not a CNC mill. As such, it should never be used for production output that could be done on these machines.* 



------

<strong id="submission">Submission</strong>

The Zund handles Vector format files and recognized layers for tool path operations. In order to submit files to the Zund, use the google form template located here. 

Ensure when submitting files to the Zund that you are producing a PDF via Save As opposed to Print to PDF. A Save As PDF from Illustrator or the like will preserve layer structure and organization, while a Print to PDF will collapse all layer structure and produce a single, collapsed, PDF which will not be printable.

Depending on the material stock selected, ensure that your scale is correct and the desired material dimensions are adhered to. As follows are the stock dimensions for the base material offerings within the ITL. 

| Thickness | Material Type            | Dimensions |
| --------- | ------------------------ | ---------- |
| 2 ply     | Bristol Board, White     | 32 x 40"   |
| 4 ply     | Bristol Board, White     | 32 x 40"   |
| 5/32"     | Corrugated Cardboard     | 48 x 96"   |
| 1/2"      | Honeycomb Sandwich Board | 48 x 96"   |
| 1"        | Honeycomb Sandwich Board | 48 x 96"   |
| 1/8"      | Foam Board, White        | 48 x 96"   |
| 3/16"     | Foam Board, White        | 48 x 96"   |
| 1/2"      | Foam Board, White        | 48 x 96"   |
| 3/16"     | Foam Board, Black        | 48 x 96"   |
| 1/2"      | Foam Board, Black        | 48 x 96"   |

Setting up layers for a Zund Job should follow the order listed below, from top to bottom, depending upon the desired material and tooling path operations. 

All Modules / Tools (Except Routing)

1. Registration - dots or board edges
2. Kiss Cut
3. Score
4. V-cut 
5. Bevel cut
6. Thru-cut
7. Reference layer

Routing Module

1. Registration - dots or boarder
2. Engrave
3. Drill
4. Route
5. Reference layer



> **If a particular layer is not desired, simply omit this layer, but maintain the order hierarchy.* 

When setting up a cut job with interior and exterior cuts, be sure to separate out and create multiple through cut layers for interior and exterior. 

EX. 

1. Registration Dots
2. Score - Blue line
3. Thru-cut Interior 01 - Green line
4. Thru-cut Exterior 01 - Red line

<img src=".\images\2020.02.20-PRINT-AND-CUT-GIF-SMALL.gif"  />



> **Note that the 1/4" Dia. registration dots are in the exact same location in both the print and cut files.* 

This is to mitigate the situation where an exterior or perimeter cut is made first and an interior cut is desired within this already cut piece which now will have less vacuum hold down surface area and increase the likelihood of errors occurring. Apart of this, it is recommended to provide approximately 1/4" spacing around profiles in order to address the same situation or to become increasingly aware of interior and exterior cuts, producing multiple layers and forcing an order of operations to the production routine. 

Submission for printing on 2ply or 4ply bristol and cutting on the Zund should be sent on the same submission form with a PDF for Printing labeled and a Save As PDF for cutting. Ensure that the correct stock size is used and maintain a half inch safety margin all around the stock perimeter. 

Inclusion of registration dots within both the print and cut files (in the same exact location) will allow for syncing the cut vectors to the printed content once the printed material arrives to the Digital Cutter. The registration dots should be in the amount of 5 or more, located asymmetrically around the artwork with a 1/4" Diameter (this is crucial). Note that the printed content need not have the cut outlines, it may simply have artwork and the cut vectors can be separate onto themselves depending upon the desired outcome. 

Once the job is submitted and verified from the user, the following charges will be applied and the job processed. For the Spring 2020, a flat fee will be applied to all jobs tied to the material selected. Printing will incur an additional flat fee price onto any job that utilizes this process. 



| Digital Cutting Operations    | Cost   |
| ----------------------------- | ------ |
| 2 ply Bristol Board           | $15.50 |
| 4 ply Bristol Board           | $21.00 |
| 5/32" Cardboard               | $15.50 |
| 1/2" Honeycomb Sandwich Board | $26.50 |
| 1” Honeycomb Sandwich Board   | $38.50 |
| 1/8" Foam Board, White        | $23.50 |
| 3/16” Foam Board, White       | $23.50 |
| 1/2" Foam Board, White        | $37.50 |
| 3/16” Foam Board, Black       | $28.50 |
| 1/2" Foam Board, Black        | $47.00 |

| Printing and Cutting Operations | Cost   |
| ------------------------------- | ------ |
| 2 ply Bristol Board             | $19.00 |
| 4 ply Bristol Board             | $25.50 |

| Print Only Operations | Cost   |
| --------------------- | ------ |
| 2 ply Bristol Board   | $9.00  |
| 4 ply Bristol Board   | $15.50 |



Upon completion of any one job an email notification will be sent out for pickup from the Zund Project Storage unit. A board number will be issued in order to track job collection. 



<img src=".\images\ZUND HOUSE COMPLETE SMALL.jpg" style="zoom: 67%;" />

------

**Created by ITL**

**ITL Website : [itl.pratt.edu](https://itl.pratt.edu/)**

**DFG Website : [pratt.digitalfutures.info](http://www.pratt.digitalfutures.info/)**

**Instagram : @pratt.itl**

**ITL Email : [itl@pratt.edu](mailto:itl@pratt.edu)** 

**ITL Zund Email : [itlzund@pratt.edu](mailto:itlzund@pratt.edu)**

**Location : Pratt Institute, Engineering Bld. 002-006**

