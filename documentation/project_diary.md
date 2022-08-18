# Project Diary


### Day 1 - 05.08.22: 
* set up new branch for git
* updated vvvv and Vl.Fuse versions
* implemented basic point cloud sampling based on Keijiro's Bibcam Format

### Day 2 - 06.08.22: 
* achieved bar code reading
* FIXME: problem with compression and color channels
* FIXME: need to figure out how to rotate properly
* FIXME: Fix projection for particle positions & coloring

### Day 3 - 07.08.22: 
* fixed color channel glitch in BarCode
* fixed rotation
* fixed projection
* FIXME: struggled to replace kinect position input with Bibcam input in Kinesis System

### Day 4 - 08.08.22: 
* fixed kinect replacement, probability emitter now working with Bibcam (Problem was new VL.Fuse version)
* cleaned patch to be ready for contribution
* FIXME: replace buffer with texcoord patching to be compatible with newest VL.Fuse version

### Day 5 - 09.08.22: 
* fixed buffer issue (FIXME: Still not running with Fuse newer than 0.1.8)
* added example patches (glowing Spheres, Lines, distance-based NoiseRipple, Boxes(InstancedRenderer is broken))
* added alembic points to Fuse reader
* added ply reader
* need new footage for proper documentation (no Iphone yet)

### Day 6 - 10.08.22: 
* added alembic model to Fuse reader
* created an example project in Blender
* issue with reading animation from Blender export -> made vvvv forum post
* added Vl.Stride.3dtext to fuse reading
* made an example patch for a text transition effect

### Day 7 - 11.08.22: 
* achieved 4/5 of the planned next Steps
    * Explore Point Clouds -> done
    * Find a way to use animated meshes (alemebic, obj, VAT) -> done
    * Find a way to use real footage (Runway Depth Estimation, Keijiro's Bibcam) -> done
    * See VL.Stride.Text3D , or text to SDF -> done
    * Setup non-realtime rendering pipeline -> NOT DONE

### Day 8 - 12.08.22: 
* achieved 45/5 of the planned next Steps
    * Explore Point Clouds -> done
    * Find a way to use animated meshes (alemebic, obj, VAT) -> done
    * Find a way to use real footage (Runway Depth Estimation, Keijiro's Bibcam) -> done
    * See VL.Stride.Text3D , or text to SDF -> done
    * Setup non-realtime rendering pipeline -> done

### Day 9 - 17.08.22: 
* got apple devices from Angela
* try to build and run Bibcam on iPad