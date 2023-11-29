# Ex. No. 7 - SIMULATION OF PRE PROCESSING IN ADDITIVE MANUFACTURING
### DATE: 
## AIM:
### To simulate the Pre Processing for 3D printing.

## REQUIREMENTS:
### System - Windows 7 or higher, 1 GB RAM.

## PROCEDURE:
### Pre-processing encompasses the steps between design and printing. Process of 3D printing starts with designing in CAD. Then printer software slices 3D CAD file into layers. For each slice, the software converts the data into machine code that determines tool paths for the machine to follow. The various steps in pre-processing from design to printing are as follows:

### 1)	CAD File
### 2)	Conversion to STL a. Orientation b. Support Structure c. Slicing d. Path Planning

### 1. CAD File
### Every manufacturing process starts with the process of designing and as in any type of manufacturing, there are certain limitations to the materials and manufacturing processes that dictate how the product should be designed, 3D printing is no different. In 3d printing, characteristics of hardware, software, temperature, filament and many other factors play an important role in how a digital model translates into a printed object. Some of them are designed with a strong base, grain direction, overhung, wall thickness, round corners and tolerances.

### 2. Conversion to STL
### In order to check the interface of the object and make it reliable to 3d printers, conversion to STL file is required. It also facilitates other features like quick error check, bridging the gap between CAD platforms, exhibition purposes and 3D digitizer extension.

### a. Orientation:
### Orientation plays a vital role in the final product of 3d printing as it affects the part accuracy, manufacturing time, strength and surface finish. There are various orientations by which we can print the object such as vertically upward, vertically downward and in horizontal plane.

### b. Support Structure:
### Support structures are required where the objects are unable to get printed directly. Support structures help to guarantee the printability of a section during the 3D printing measure and also it can assist with forestalling part twisting, secure a section to the printing bed and guarantee that parts are joined to the fundamental body of the printed part.

### c. Slicing:
### The motive behind slicing a 3D model is to transform the model into guidelines for the 3D printer. To play out this errand, the slicing software isolates the item into numerous layers. It's classified "slicing" since it "slices" the 3D model to make numerous layers. After the layers have been made, the slicing software applies different qualities to every one of them.

### d. Path Planning:
### Path planning helps to improve the printed surface quality, shape accuracy and infill distribution quality. There are various ways for path planning which can be used to print the objects which may affect the following factors in objects like raster path, grid path, spiral path and zigzag path.

![image](https://github.com/Sellakumar1987/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/113594316/baef8515-67d7-4c96-accc-4ee88035c9e7)

### ●	All the processes related to pre-processing will be shown on the screen.
### ●	Select CAD file preparation from the visible list.
### ●	When the first process is selected then it will open in the blank space in the left side of the screen.
### ●	Select the options of process of pre-processing in the sequence in which they are shown.
### ●	If the user follows an incorrect sequence then a pop-up will appear on the screen showing the name of the process to be selected.

## OUTPUT:
![123_1](https://github.com/Sellakumar1987/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/113594316/ec8dafd7-cb7c-4a5b-936c-41e86a32a9da)
![123_2](https://github.com/Sellakumar1987/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/113594316/c071a941-e5b4-4b31-af63-5f9fe08cd0fb)
![123_3](https://github.com/Sellakumar1987/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/113594316/ebb3a944-eeb0-45e8-9841-d58997840c54)

## Output:
![image 1](https://github.com/vishnukayyala/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/151489368/cf2d6d7f-f1ec-4731-b2d0-1d4d1e654851)
typically involves preparing the CAD data for further analysis or manufacturing processes. This can include tasks such as cleaning up the geometry, simplifying complex models, and organizing the data for efficient processing.

Here are some common preprocessing steps in CAD:

Importing CAD Files:

Import CAD files into the software you're using. Different CAD software may support different file formats, so make sure your files are compatible.
Geometry Cleanup:

Remove unnecessary details and features that are not relevant to the analysis or manufacturing process.
Repairing Geometry:

Check and repair any errors or inconsistencies in the geometry, such as gaps, overlaps, or self-intersections.
Meshing:

If the CAD data will be used for simulations or analysis, it may need to be converted into a mesh. This involves dividing the geometry into small elements for numerical analysis.
Simplification:

Simplify complex models to reduce the computational resources required for analysis. This can involve reducing the number of vertices, edges, and faces while preserving the overall shape.
Organizing Components:

If your CAD model consists of multiple components or parts, organize them in a way that makes sense for your project. This could involve grouping related parts or assemblies together.
Coordinate Systems:

Ensure that the CAD model is aligned with the appropriate coordinate system for your project.
Material Assignment:

Assign materials to different parts of the model if your analysis requires material properties.
Boundary Conditions:

Define any necessary boundary conditions for simulations, such as fixed points or applied loads.
Units and Scale:

Check and set the correct units and scale for your project to ensure accurate analysis or manufacturing.
![image 2](https://github.com/vishnukayyala/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/151489368/5dfb57e1-4fc3-4c73-a1e3-d785659931ed)
The process of converting a CAD model to an STL file involves several steps:

Exporting from CAD Software:

Open your CAD model in the software you are using (e.g., SolidWorks, AutoCAD, Rhino).
Find the export option and select STL as the output file format.
Setting Export Options:

Most CAD software allows you to specify settings for the STL export. Common options include the level of tessellation (fineness of the mesh) and whether to export only the visible geometry.
Meshing the Model:

The CAD software will convert the solid geometry into a mesh of triangles. This process is known as meshing. You may have options to control the density of the mesh.
Checking for Errors:

Before exporting, check for any errors in the mesh, such as non-manifold geometry or gaps. These issues can cause problems during manufacturing or simulations.
Exporting as STL:

Once the mesh is ready, export the model as an STL file. You may be prompted to choose a file name and location.
Unit Conversion:

Ensure that the units of your STL file match the units expected by the downstream application (e.g., 3D printer, simulation software). Some applications may have specific unit requirements.
Verification:

It's a good practice to import the STL file back into your CAD software or another viewer to verify that the exported model looks correct and retains the necessary details.
Quality Control:

Depending on the application, you may need to perform additional quality control checks, especially if the STL file is intended for 3D printing. Check for water-tightness and overall model integrity.
![image 3](https://github.com/vishnukayyala/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/151489368/0535e638-7ae6-431e-bbc7-94540758fad7)

![image 4](https://github.com/vishnukayyala/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/151489368/8e14703e-a87b-48a1-9d55-42c68b407905)
![image 5](https://github.com/vishnukayyala/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/151489368/061a4467-e3c9-4b1e-a93e-e901d13a599c)
![image 6](https://github.com/vishnukayyala/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/151489368/e686aec5-1f6e-44ae-ae62-0f6277488c03)





### Name:
### Register Number:

## Result: 
### Thus the simulation on the Preprocessing in additive manufacturing is completed.
