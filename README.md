# Comparison of Rhino's 3D export formats
 
File size comparison of 12 export formats from two simple Rhino extrusions

Even though ACIS SAT came out as the largest format is at the moment the only viable solution for Rhino-Revit workflow. It is recommended to use it in BIM workflows for accurate display and graphics. However, it does come at a cost of file size.

---

Size in bytes. Highlighted optimal solutions for Rhino-Revit workflows:

![Chart](Chart.png)

Table:

|Format|Size                         |isText|canImportBack                                |isPolysurface|isMesh|Setting              |
|------|-----------------------------|------|---------------------------------------------|-------------|------|---------------------|
|STL   |1284 B                       |no    |yes                                          |no           |yes   |Binary               |
|3DS   |2254 B                       |no    |yes                                          |no           |yes   |Default              |
|RIB   |4353 B                       |yes   |no                                           |no           |yes   |Default              |
|STL   |5502 B                       |yes   |yes                                          |no           |yes   |Ascii                |
|XAML  |5179 B                       |yes   |no                                           |no           |yes   |Default              |
|SKP   |8873 B                       |no    |yes                                          |no           |yes   |SketchUp 2013        |
|IGS   |11316 B                      |yes   |yes                                          |no           |no    |Default              |
|STP   |16511 B                      |yes   |yes                                          |yes          |no    |AP214AutomotiveDesign|
|FBX   |22846 B                      |yes   |yes                                          |no           |no    |v7 ascii             |
|3DM   |25966 B                      |no    |yes                                          |yes          |no    |Default              |
|DWG   |32128 B                      |no    |yes                                          |yes          |no    |Solids               |
|FBX   |36128 B                      |no    |yes                                          |no           |no    |v7 binary            |
|SAT   |37671 B                      |yes   |no                                           |yes          |no    |Default              |

Rhino Render:

![scene](scene.png)
