Program constants in Landscape.h and Utility.cpp.

MAPS:
  Default map is read from HeghtXXX.raw where XXX is the MAP_SIZE
(as defined in Landscape.h).  If this map is not found, the program
attempts to open "Map.ved", a Tread Marks map file.  Tread Marks maps
will only work for MAP_SIZE == 1024.  Also, the MULT_SCALE to view
Tread Marks maps correctly is "0.25f". (www.TreadMarks.com)


CONTROLS:
MOUSE - Hold Left Mouse Button to Rotate View Angle

Q - Change Rendering Mode (Wireframe, Lit, Fill, Texture)
O - Change View Mode (Observe, Follow, Drive, Fly)

W/S - Move forward/back
A/D - Rotate left/right (in Observe Mode only)

F - Stop Animation
R - Toggle Frustum Drawing

0/9 - More/Less Triangles per frame
1/2 - Adjust FOV

