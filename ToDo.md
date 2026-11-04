# To Do:

- Explore different transform spaces (especially for restricting xform ops to axes/planes)
- Consider temporary pivots for rotation and scale ops in case pivot is not at object
  - Use obj centre captured in proc getXforms?
- Clean up Dialogs
  - Condense to single dialog
  - Expose constraint interpolation setting
  - Add cancel/dismiss checks
  - Allow user to select which operations to include/ignore (translations, rotations, scaling)
  - Consider a more compact UI approach for the axis restriction akin to a dropdown/enum 
- Errors:
  - Missing second selection
- Warnings:
  - Locked channels (would return list of locked channels in script editor)
- For use on larger numbers of copies:
  - Would it be more performant to calculate xform values on a locator each iteration, then write them to the copy instead of creating/deleting constraints multiple times?
  - How much performance would be gained/is it worth it?
- Consider switching to python for quaternion rotations
