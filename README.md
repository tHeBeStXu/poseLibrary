# poseLibrary
Pose Library for production
	    
This is a pose library tool for animation work.		    
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
  
import CustomProceduralRigTool    
from CustomProceduralRigTool import Main_UI as Main_UI    
reload(Main_UI)    
    
UI = Main_UI.RiggingMainUI(dock=1)    

# How to use:
I will record a video for using this script. To be continued...    

# Bugs:
If you find any type of bugs, please e-mail me at: razer_mamba@qq.com.    
    
If you like, please STAR this repository. Thank you very much.    
