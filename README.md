# pvtrace-aj

Modifications were made to Shomik Verma's pvtrace (https://github.com/shomikverma/pvtrace-sv) to allow light to come in at incident angles and to simulate ray-tracing for unique geometries.

To use, replace the contents of the installed pvtrace (i.e. for MacOS under ~/opt/anaconda3/envs/pvtrace-env/lib/python3/site-packages/pvtrace/) with the contents of this repository.

Sample Example how to Run (Specific to my Laptop which is a Mac with Homebrew):
1. conda activate pvtrace-env3
2. cd /Users/ENTER MAC USER HERE/PycharmProjects/PythonProject/pvtrace-sv-master/LSC_scripts
3. export SPATIALINDEX_C_LIBRARY='/opt/homebrew/Cellar/spatialindex/2.1.0/lib'
4. python LSC_scriptv2.py


LSC_scriptv2.py is for angles normal to the surface. LSC_scriptv3.py is for incident angles of your choice. LSC_scriptv4.py allows your computer to run ray-tracing on files stored on your computer (must be organized into folders and subfolders as shown in the code) one-by-one continuously, so that you do not need to run LSC_scriptv3.py several times again and again.

The GUI folder is still under development and does not work well.


The data of my simulations can be found in the csv files in this repository. There is one file for each of the 4 shapes (cones, mounds, pyramids, and cylinders) that I tested.

The solar pattern csv file is specific to my project and it is how I determined the value of my results. Contact me if you desire more information for this.
