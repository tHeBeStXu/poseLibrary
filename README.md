# poseLibrary
Pose Library for production
	    
This is a pose library tool for animation work.	        
It is Pyside2 version of Subin Gopi's work for Maya2017+.All IPs are belong to Subin Gopi and thank his great tutorials.    
Before using the script, you need to make true that your maya setup is OK.       		    
You can use it to export, import and rename pose. For management, you can create, expand, collapse and remove pose library folder.		

# How to install:
1. Download the project file and unzip it somewhere in the computer, make ture to remember the directory of the unzip file location		
2. Open Maya 2017+ and open script Editor		    
3. New a Python tab, and enter following script 		    

Dir = 'X:\WHERE\YOU\PUT\THE\FILE'		    
import sys		

if Dir not in sys.path:		
    sys.path.append(r'X:\WHERE\YOU\PUT\THE\FILE')      
  
import PoseLibrary    
from PoseLibrary.UI import UI    
reload(UI)    
    
ui = UI.MainUI()    

# How to use:
You can go to Subin Gopi's web: https://vimeo.com/user55256190 for further exploring.		

# Bugs:
If you find any type of bugs, please e-mail me at: razer_mamba@qq.com.    
    
If you like, please STAR this repository. Thank you very much.    
