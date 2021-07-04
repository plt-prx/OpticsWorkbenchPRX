# ![WorkbenchIcon](./icons/pyrate_logo_icon.svg) Optics Workbench
    
Geometrical optics for FreeCAD.  
Performs simple raytracing through your FreeCAD objects.

[![Total alerts](https://img.shields.io/lgtm/alerts/g/chbergmann/OpticsWorkbench.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/chbergmann/OpticsWorkbench/alerts/)

![screenshot](./examples/screenshot.jpg)

## Work in progress !
The current version only supports 2D objects


  
## Installation


### Manual Installation

```bash
cd ~/FreeCAD/Mod/ 
git clone https://github.com/chbergmann/OpticsWorkbench.git
```
When you restart FreeCAD, "Optics Workbench" workbench should now show up in the [workbench dropdown list](https://freecadweb.org/wiki/Std_Workbench).
  
## Getting started

## Tools
### ![RayIcon](./icons/ray.svg) Ray
A single ray for raytracing

### ![2D Beam](./icons/rayarray.svg) 2D Beam
A row of multiple rays for raytracing

### ![Optical Mirror](./icons/mirror.svg) Optical Mirror
The selected FreeCAD objects will act as mirrors

### ![Optical Absorber](./icons/absorber.svg) Optical Absorber
The selected FreeCAD objects will swallow the rays of light

### ![Off](./icons/Anonymous_Lightbulb_Off.svg) Switch off lights
Switches off all Rays and Beams

### ![On](./icons/Anonymous_Lightbulb_Lit.svg) (Re)start simulation
Switches on and recalculates all Rays and Beams

### ![Example](./icons/pyrate_logo_icon.svg) Example 1
generates the screenshot above

## Discussion
Please offer feedback or connect with the developer via the [dedicated FreeCAD forum thread](https://forum.freecadweb.org/viewtopic.php?f=8&t=59860).

## License
GNU Lesser General Public License v3.0
