3/1/26

Learned the hardway that the initial configuration of parts and their positions relative to the origin as well as their rotations relative to the default planes are extremely important when trying to create assemblies and subassemblies that are easy to work with and that need to be properly constrained. Instead of creating unnecessary reference objects, see if the coordinate axes and planes that are part of a Solidworks part can be used instead.

Setting parts and assemblies to Flexible tells Solidworks to not treat the included subassemblies as rigid bodies. Flexible must be set from the top-level subassemblies to the bottom-level subassemblies for this to work.