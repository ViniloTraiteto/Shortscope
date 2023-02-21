# Shortscope
Unity files for shortscope, in case anyone wants to gaze upon my wretched creation. Deathly afraid of pushing assets I may not be allowed to so I self contained everything I made on it's own folder.

### What's in here

Main map file, which has both Sandbox logic AND Take&Hold logic on it, disable the one you don't need and use the proper Build Profile.

### Requirements (and other assets used)
- Meatkit (https://github.com/H3VR-Modding/MeatKit)
- Atlas (https://github.com/H3VR-Modding/Atlas)
- Bakery (https://assetstore.unity.com/packages/tools/level-design/bakery-gpu-lightmapper-122218)
- RealtimeCSG (https://assetstore.unity.com/packages/tools/modeling/realtime-csg-69542)
- NavMeshCleaner (https://assetstore.unity.com/packages/tools/ai/navmesh-cleaner-151501)
- Mesh Combiner (https://assetstore.unity.com/packages/tools/modeling/mesh-combiner-157192)
- Paint.NET for the icon and thumbnail (https://getpaint.net/)

### How to Use
Drop the "VT" folder on your own Unity project. I made sure everything I actually made (map, meshes, references, etc.) would be on it.

Follow Atlas and Meatkit's documentation on how to set up your Unity project. You don't NEED Bakery these days (was required for WurstMod if you wanted baked lighting) so you can skip that if you want (you'll have to relight the map though, as it uses Bakery lights).

Change the build profiles' Build Action before building, as it's set to my r2modman testing profile and that'll probably break on your end!

There's a disabled object that has all the unexported CSG meshes so you can fiddle with those to your heart's content.
