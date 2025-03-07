The cs_voyager.blend is the latest file.
The 3D files are symetric about the y-axis [xz-plane] and the origin of the 3D object is at the center of mass [If you asume uniformely distributed mass across the entire volume]


Blender has some strange scaling when importing and exporting. The modell is most likely on a factor of 1/1000 of the wanted size. If that is the case for you. The easiest solution is to set and apply a new scale, then export in blender:
Scaling:
    NB: Make sure you are in the layout window [Top row, on the same line as file, edit, render, etc], and that the **3D Viewport** is in **object mode**
    Option 1:
        - Select object [left click in 3D Viewport]
        - click on 's' on the keyboard to scale the object 
        - Expand the resize action that now appeared in the left bottom corner of the viewport and set the scale to 1000 or whatever you prefere
        
    Option 2:
        - Select object [left click in 3D Viewport]
        - Press 'n' on the keyboard to open the object menu in the **sidepanel** in the **3D Viewport** [Right top edge of the 3D viewport] and in the **Item** tab under **Transform** set a new scale (1000) 
    
    - Select the object in the 3D Viewport again (Should have an orange outline)
    - Press 'ctrl'+'a' and select scale to apply the scale.

Exporting:
    - Click on 'file' > 'Eport' > '<your_prefered_file_format.frmt>'