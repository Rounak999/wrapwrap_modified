# wrapwrap_modified
This is a modified clone of rep https://github.com/ambionics/wrapwrap. It also contain dependency named 'ten' https://github.com/cfreal/ten. 

You can refer to above links of how to install them. If you want to use above repo follow below steps.
 
1. Install venv library - pip install virtualenv.
2. Start venv - python venv 'envname'.
3. Activate venv - source envname/bin/activate
4. Naviagate to 'envname' folder and git clone the repo.
5. Navigate to cloned folder and unzip ten file. Install ten dependecny using command pip install .
6. Now run the file using command ./wrapwrap.py /etc/passwd '<?php echo rounak' 'test' 1000 , i.e in the form wrapwrap.py filename prefix suffix nb_bytes.
