# roadelevation
v1.0 11/12/2019 
This is an ArcGIS Pro/Jupyter Notebook data processing workflow. ArcGIS Pro 2.4 used with the 3D analyst extension, and the out of the box Jupyter notebook environment with ArcGIS Pro. This shows how to create elevation points and 3D roads from 2d roads. Refer to the video and the comments in the notebook.

This takes an elevation raster and 2d road lines as input and uses a python script (Jupyter notebook) to:
- generalize and then insert vertices every X meters
- derive elevation values at those vertices
- create 3d points from the 2d points
- add the x, y, and z values as attributes
- used those 3d points to create 3d roads
- split the 3d roads into 3d segments at the vertices
- add the x, y, and z start and end values as attributes to the 3d segments

An Mp4 video with audio also shows the process. Open source data street from Falls Church City, VA website is used and a clip of downsampled elevation data from the ArcGIS Online living atlas.
