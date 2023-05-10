# DATCH Features List

> ## Summary
> Details on all available features in the most updated version of DATCH.
>
>
> Sections:
>
> [Main Menu](#main-menu)
>
> [Drawing Modes](#drawing-modes)
>
> [Tools and Settings](#tools-and-settings)
>
> [Voice Commands](#voice-commands)
>
> [Menu Buttons Quick Reference](#menu-buttons-quick-reference)


## Main Menu
<img src="images/menu_full.jpg" width="250"> <img src="images/menu_with_dock.gif" width="250"> 

### Primary Buttons

<img src="images/diagram_main_menu.png" width="500"> 

- This section of the menu is comprised of two semicircles made up of buttons.
	- Inner Semicircle - Drawing mode buttons
	- Outer Semicircle - Tools and Settings buttons

### Attributes Panel

<img src="images/diagram_attributes_panel.png" width="500"> 

- Displays additional settings for the drawing mode or tool that is currently in use. 
- Panel Dock
	- Hide the Attributes Panel by tapping the dock button.
	- Undock the Attributes Panel by grabbing it and dragging it away from the dock.
	- Dock the Attributes Panel by grabbing it and placing it near the dock button (panel will snap back into place).

### Pin Menu
- Pins the menu in space in front of the user 

### Pen Distance Slider
- Changes the length of the pen tip for drawing along the surfaces of objects and structures that should not be disturbed

### Pen
- A pen appears in hand while pinching to visually indicate when the user is drawing.

<br></br>
## Drawing Modes 
<img src="images/drawing_modes_new_menu.gif" width="500"> 

### Free Draw
- Draw unrestricted freehand shapes

	<img src="images/drawing_freedraw.gif" width="500"> 
		
		Steps:
		1. Tap the Free Draw button
		2. Pinch and drag in midair to draw
		
		Note: Close a shape by bringing the starting point (white) near the end point (blue).


### Line
- Draw polyagonal shapes by creating points connected by straight lines.

	<img src="images/drawing_line.gif" width="500"> 
		
		Steps:
		1. Tap the Line button
		2. Pinch in midair to create a point, then pinch another area in space to create an additional connected point
		3. Pinch and drag any of the grab points to reposition them 
		
		Note: Close the shape by bringing a point near another point.

### Curve
- Draw curved shapes using floating splines

	<img src="images/drawing_curve.gif" width="500"> 

		Steps:
		1. Tap the Curve button
		2. Pinch in midair to create a curve with 4 points
		3. Pinch and drag any of the points to reshape the curve 
		
		Note: Close the shape by bringing a point near another point.
<br></br>

### *Drawing Attributes Panel*
<img src="images/line_weight_and_color.gif" width="500"> 

- ### Color Picker
	- Before drawing, drag finger along the color picker gradient or tap one of the color swatches to select a color for the next drawn line.
- ### Line Weight Slider
	- Drag the slider up or down to increase or decrease the width of the next drawn line.
- ### Close Shape
	- Automatically close a partially-drawn shape and fill it with a color

		<img src="images/auto_close_shape.gif" width="500"> 

			Steps:
			1. Select an unclosed shape
			2. Tap the "Close Shape" button

<br></br>
## Tools and Settings
### File
- Opens the File Attributes Panel

<br></br>

### *File Attributes Panel:*
- ### New
	- Create a new empty DATCH file with no drawings or tools present in the space

- ### Open
	- Open a previously created DATCH file

- ### Save
	- Save a DATCH file of the current space

- ### Accessibility
	- Opens the Accessibility menu, which includes settings for ease of use settings for the application
	- ### Handedness
		- Change the menu orientation for left-handed or right-handed use 
		
			<img src="images/handedness_new_menu.gif" width="500"> 

	- ### Theme
		- Change color palette of application for easier viewing 
			
			<img src="images/theme_switching.gif" width="500"> 

				Steps: 
				1. Tap the Accessibility button
				2. Tap the Theme button in the Attributes panel
				2. Tap preferred theme
- ### Import Image
	- Import an image into the space from HoloLens 2 internal storage.
		- Manipulation: The image can be manipulated (moved, rotated, scaled) similarly to a shape
		- Opacity Slider: Make the image more or less translucent
		- Hide/Show Background Checkbox: Remove or display the background of the image

		<img src="images/importing_image_planes.gif" width="500"> 

			Steps: 
			1. Tap the Import Image button
			2. Navigate through folders and tap an image to select it 
			3. Tap Open to display the image in space	

- ### Toggle Mesh
	- Show the spatial mesh a wireframe outline of the environment calculated by the headset
	
		<img src="images/mesh_spatial.gif" width="500"> 


- ### Precision Settings
	- Opens Precision Attributes Panel


	- ### *Precision Attributes Panel:*
		- ### Rotation Snapping Checkbox
			- Toggle rotation snapping, which makes shapes and tools rotate by specific degree increments
			- Select a specific degree value (10, 15, or 45) by which shapes and tools should snap when rotating 

- ### Log
	- Add text to a log file (.txt) to be viewed later for future reference.

		<img src="images/improved_log.gif" width="500"> 

			Steps: 
			1. Tap the Log button
			2. Select a save location for the log file (create a new log file or overwrite existing log file)
			3. Type text using the system keyboard, then close the keyboard
			4. After use, connect the HoloLens 2 to a PC and locate the log file inside the previously-selected folder

<br></br>

### Clear All
- Erase all shapes and tools in the space 

### Delete
- Delete selected shape (highlighted by a blue box)

### Undo
- Undo previous action 

### Fill
- Fill a closed shape with a color 

	<img src="images/fill.gif" width="500"> 

		Steps:
		1. Select a shape by touching it or hovering over it
		2. Tap the Fill button to fill the selected shape with current fill color

### Drawing Plane
- Display a 2D grid in front of user for drawing on flat surfaces

- ### Drawing Plane Attributes Panel:
	- ### Draw On Plane Checkbox
		- Toggle on to draw on the surface of the drawing plane
		- Toggle off to activate drawing plane manipulation handles
	- ### GridPoint Snapping Checkbox	
		- Allow lines on drawing plane to snap to the grid's intersection points for more precise drawings

	<img src="images/gridpoint_snapping.gif" width="500"> 

		Steps:
		1. Tap the Gridpoint Snapping checkbox (ensure that the Draw on Plane checkbox is toggled on)
		2. Drawings will snap to the intersection points of the drawing plane

	- ### Perpendicular Button
		- Automatically rotate the drawing plane to be situated perpendicular to the ground
	- ### Parallel Button
		- Automatically rotate the drawing plane to be situated parallel to the ground

		<img src="images/drawing_plane_auto_orientation.gif" width="500"> 
		
			Steps:
			1. Tap the Drawing Plane button to create a drawing plane
			2. Aim near the surface of the drawing plane, pinch, and drag to draw along its surface

### Tag
- Leave a physical note at a specific location or on a drawing
	- Keyboard Button
		- Open a keyboard to change the text inside the tag 
	- Link/Unlink
		- Make the anchor point of the tag snap or detach from a shape it is currently touching
	- Delete
		- Delete tag from the space

	<img src="images/tagging.gif" width="500"> 

		Steps:
		1. Tap the "Tag" button
		2. Grab empty space near the tag to move the entire tag or position the label or anchor individually
		3. Tap the keyboard button to enter a short message on the tag

### Peg Grid
Create a grid of marker pegs with specific dimensions

<img src="images/peg_markers.gif" width="500"> 
<img src="images/peg_grid_panel_revised.png" width="500"> 

	Steps:
	1. Tap the Peg Grid button
	2. Tap the up or down arrow buttons on either side of the Length or Width sections to enter the desired number of pegs on each row and column.
	3. Tap the '+' or '-' buttons on either side of the Peg Spacing section to adjust the distance between each peg within the selected dimensions. 
	4. Tap the Create button to generate a grid in space
	5. Edit the position and rotation of the peg grid using manipulation handles
	6. Touch a peg in the grid to mark it for future reference (indicated by a change in color)

### *Peg Grid Attributes Panel*
- ### Length Buttons
	- Tap either button to increase or decrease the length of the grid
- ### Width Buttons
	- Tap either button to increase or decrease the width of the grid
- ### Peg Spacing Buttons
	- Tap either button to set the distance between each peg in a grid
- ### Create Grid Button
	- When grid dimensions are set, create a grid in place of the preview grid

<br></br>

### Measuring Tools
- Open the Measuring Tools Attributes Panel
### *Measuring Tools Attributes Panel*
- ### Measuring Cube
	- Generate a tool for measuring 3D (height, width, depth) shapes and structures 
		<img src="images/measuring_cube.gif" width="500"> 

			Steps:
			1. Tap the Measuring Cube button
			2. Resize and manipulate the measuring cube by pinching its handles; move it by grabbing and dragging it from its center
- ### Measuring Tape
	- Generate a tool for measuring 2D (height, width) shapes and distances
		<img src="images/measuring_tape.gif" width="500"> 

			Steps: 
			1. Tap Measuring Tape button
			2. Change the length of the measuring tape by grabbing one of its endpoints; move it by grabbing and dragging it from its center

### GPS
- Open GPS Attributes Panel and activate GPS functionality if available (rover and base must be powered on)
<br>
<img src="images/gps_map_coords_demo.gif" width="500"> 


### *GPS Attributes Panel*
- ### Map
	- Display a floating map panel that displays icons for the objects present in space
<br></br>

## Voice Commands
### Clear All
- Remove all shapes and tools from the space
### Pin Menu
- Pins the menu in space in front of the user  
### Unpin Menu
- Lock menu to palm
### Switch Hand 
- Change the menu to left-handed or right-handed use (right-handed use, with menu constrained to left palm, is default)
### Toggle Mesh
- Toggle the wireframe spatial mesh on or off
### Undo
- Undo a previous action 
### Call Menu
- Bring menu into view
### Take a Picture
- Take a screenshot of the current view
	- Button shortcut: Press the two buttons on the right-hand side of the HoloLens 2
	- Voice command: "Take a picture"

<br></br>

---

<br></br>

## Menu Buttons Quick Reference
| Button                  | Description |
| --------------------------- | ----------- | 
| Accessibility <br> <img src="images/icon_Accessibility.png" width="50">              | Show attributes panel containing accessiblity settings        |
| Clear All <br> <img src="images/icon_ClearAll.png" width="50">                  | Remove all tools and drawings from current scene        |
| Close Shape <br> <img src="images/icon_CloseShape.png" width="50">                | Automatically close and fill shape        |
| Communicate <br> <img src="images/icon_Comms.png" width="50">               | (Disabled) Communicate with other DATCH users        |
| Create Peg Grid <br> <img src="images/icon_CreatePegGrid.png" width="50">             | Create a grid of marker pegs based on  selected settings       |
| Default Theme <br> <img src="images/icon_Theme.png" width="50">             | Set application color theme to default      |
| Delete <br> <img src="images/icon_Delete.png" width="50">                     | Delete selected shape or tool        |
| Dock <br> <img src="images/icon_Dock.png" width="50">                        | Dock, undock, and hide the attributes panel         |
| Drawing Plane <br> <img src="images/icon_DrawingPlane.png" width="50">              | Create a surface for 2D drawing        |
| File <br> <img src="images/icon_File.png" width="50">                       | Open attributes panel for file settings        |
| Fill <br> <img src="images/icon_Fill.png" width="50">                       | Fill selected shape with a color        |
| GPS <br> <img src="images/icon_GPS.png" width="50">                       | Show coordinates, altitude, and satellites in GPS attributes panel        |
| Handedness <br> <img src="images/icon_Handedness.png" width="50">                 | Change dominant hand for application use        |
| Import Image <br> <img src="images/icon_ImportImage.png" width="50">                | Import an image saved on the headset        |
| Indoor Theme <br> <img src="images/icon_Indoor.png" width="50">                | Set application color theme to indoor        |
| Log <br> <img src="images/icon_Log.png" width="50">                        | Add text to log file        |
| Map <br> <img src="images/icon_Map.png" width="50">                        | Show map                    |
| Measuring Cube <br> <img src="images/icon_MeasuringCube.png" width="50">             | Create a measuring cube for measuring in three dimensions        |
| Measuring Tape <br> <img src="images/icon_MeasuringTape.png" width="50">             | Create measuring tape for measuring two dimensions      |
| Measuring Tools <br> <img src="images/icon_MeasuringTools.png" width="50">            | Open measuring tools panel        |
| New File <br> <img src="images/icon_NewFile.png" width="50">                        | Open a blank, new file        |
| Open File <br> <img src="images/icon_Open.png" width="50">                      | Open an existing file        |
| Outdoor Theme <br> <img src="images/icon_Outdoor.png" width="50">              | Set application color theme to outdoor        |
| Parallel Drawing Plane <br> <img src="images/icon_ParallelDrawingPlane.png" width="50">     | Reposition drawing plane to be parallel to the floor        |
| Peg Grid <br> <img src="images/icon_PegGrid.png" width="50">                   | Open peg grid attributes panel        |
| Peg Grid Dimensions <br> <img src="images/icon_PegGridDimensions.png" width="50">         | Set the dimensions of a peg grid        |
| Perpendicular Drawing Plane <br> <img src="images/icon_PerpendicularDrawingPlane.png" width="50"> | Reposition drawing plane to be perpendicular to the floor        |
| Pin Menu <br> <img src="images/icon_Pin.png" width="50">                   | Pin the menu to a point in space        |
| Precision <br> <img src="images/icon_Precision.png" width="50">                  | Open attributes panel for precision settings (e.g. rotation snapping)       |
| Save File <br> <img src="images/icon_SaveFile.png" width="50">                      | Save current file        |
| Tag <br> <img src="images/icon_Tag.png" width="50">                        | Create a tag for leaving a note in space        |
| Theme <br> <img src="images/icon_Theme.png" width="50">                      | Open attributes panel for application color theme settings        |
| Toggle Mesh <br> <img src="images/icon_ToggleMesh.png" width="50">                | Show/Hide the spatial mesh       |
| Undo <br> <img src="images/icon_Undo.png" width="50">                       | Undo last action performed on selected shape        |
