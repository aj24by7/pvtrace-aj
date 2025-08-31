# pvtrace-aj

Modifications were made to Shomik Verma's pvtrace (https://github.com/shomikverma/pvtrace-sv) to allow light to come in at incident angles and to simulate ray-tracing for unique geometries.

To use, replace the contents of the installed pvtrace (i.e. for MacOS under ~/opt/anaconda3/envs/pvtrace-env/lib/python3/site-packages/pvtrace/) with the contents of this repository.

LSC_scriptv2.py is for angles normal to the surface. LSC_scriptv3.py is for incident angles of your choice. LSC_scriptv4.py allows your computer to run ray-tracing on files stored on your computer (must be organized into folders and subfolders as shown in the code) one-by-one continuously, so that you do not need to run LSC_scriptv3.py several times again and again.

The GUI folder is still under development and does not work well.
