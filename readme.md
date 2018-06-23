## The complete [Armory3d](http://armory3d.org/index.html) SDK to use with the [Blender](https://blender.org) render software.
#### Author: Robert Steckroth <[RobertSteckroth@gmail.com](mailto:RobertSteckroth@gmail.com)>
#### License: zlib/libpng 

All of the individual Armory3D SDK projects are managed with the git submodules command.  To install the Armory3D SDK use: 

```git clone --recurse-submodules https://github.com/restarian/armsdk.git```

Then, run the python script in the base directory to fetch the latest binary used by the SDK (*the script will detect and use python 2 or 3 automatically*):

```python fetch_others.py```

To update the entire SDK to the latest version use the git submodule forach option like so: 

```git submodule foreach git pull origin master```

Note: this repository also includes all of the documentation projects created for armory.

Make sure that *armsdk* (which is the base directory of this repository), is located in the same directory as the blender executable.
