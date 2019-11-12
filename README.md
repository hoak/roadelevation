# roadelevation
Create elevation points and 3D roads from 2d roads

This takes an elevation raster and 2d road lines as input and uses a python script (Jupyter notebook) to:
- smooth and then insert vertices every X meters
- derive elevation values at those vertices, turning them into 3d points
- used those 3d points to create 3d roads
- slit the 3d roads into 3d segments
- add the ending a starting elevation and XY values as attributes to the segments
