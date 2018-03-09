# Datasmith 
As a part of the Unreal Studio offering, Datasmith for Unreal Engine 4 is a collection of tools and plugins designed to import scenes and 
assets created in offline rendering applications, like Autodesk 3DS Max and CAD software, into a real-time engine. Unreal Engine 4 
(UE4) enables you to render your scenes and assets in real-time and make changes dynamically. 
Currently, three main components make up Datasmith for Unreal Engine 4: 

1. Application specific export plugins capable of creating •.UDATASMITH files 

2. The Unreal Datasmith Importer for Unreal Datasmith ('.UDATASMITH) files 

3. The Unreal CAD Importer for native file types 

#### Supported Software and File Types 
Datasmith supports a variety of software and file types, which can either be imported natively or through an external plugin that enables 
the custom Datasmith ('.UDatasmith) file type to be used. For additional information about the software and file types that are supported, 
see the Datasmith Supported File Types and Software page. Datasmith Workflow 
There are a couple of ways that scenes and assets are imported for use with Datasmith; by using a custom exporter plugin written for 
specific software (like Autodesk 3DS Max) to create the Unreal Datasmith file type, or by supporting the native file type of some CAD 
software. 

Unlike traditional game design wor1<flows where assets are constructed and imported one by one as individual assets, your assets are 
imported as fully assembled scenes with geometry, lights, cameras, materials, and textures already applied and in their proper locations. 
Once this data is loaded into the Engine, the data created by the importer is ultimately tne same and all assets become standard Unreal 
Engine assets, like Actors in a level, Static Meshes, Materials, Textures, and Lights. 
When your scene is saved to an unreal Datasmith file or a supported CAD file type, the following asset information is converted to one 
that Unreal Engine 4 can use:
 
* Object Instances
* Pivot Locations 
* Scene Hierarchy and Layers 
* Material and Physical Based Rendering (PBR) Characteristics and Textures 
* Light Positions, Colors, Sizes, and Intensities 
* Camera Properties 
* Meta Information and Custom Attributes 
* Unit Conversion
 
#### The importer also automates the generation and translation of time-consuming tasks like:

* Generating and pacing a Lightmap UV 
* Converting image formats to ones supported by Unreal Engine 
* Converting Bump Maps to Normal Maps