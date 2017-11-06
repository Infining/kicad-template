# KiCAD Project Template

This is a template for KiCAD projects made with the help of Anool Mahidharia's [Hackaday Article](https://hackaday.com/2017/05/18/kicad-best-practises-library-management/).

## Project Structure

template
* 3d_models     // .STEP and .WRL model files for all footprints
* datasheets    // data sheets for components used
* gerber        // final production files
* images        // SVG images and 3D board renders
* lib_sch       // schematic symbols
* lib_fp.pretty // footprints
* pdf           // schematics, board layouts, dimension drawings (in pdf format)
* template.pro
* template.sch
* template.kicad_pcb

## Use as a new project

1. Fork repository
2. Rename the template.pro, .sch and .kicad_pcb files to your desired project name

## Modifying/New Schematic Symbols

This blank library is specific to the project

1. Start Schematic library editor
2. Goto File>Current Library
3. Search for the "project" library
4. Create a new or load an old component

## Modifying/New Device Footprints

This blank library is specific to the project

1. Start PCB footprint editor
2. Goto File>Set Active Library
3. Search for the "lib_fp" library
4. Create a new or load an old footprint