# Dynamic Joint Chain Rig Tool
Dynamic Joint Chain Rig Tool for Game (Maya Plug-in)  
This is a rig tool for create dynamic chain by nHair in maya, especially for dynamic tails, hair and etc. in game engine(Unreal).  
Before using the script, you need to make true that your maya setup is OK for UE4.  
Each dynamic joint chain is seperate and modular, and you can add it to the exsited rig system.  
If you are not satisfied with the sim result, you can bake the sim to the Ctrls and change them manully.

# How to install:
1. Download the project file and unzip it somewhere in the computer, make ture to remember the directory of the unzip file location;  
2. Open Maya 2017+ and open script Editor;  
3. New a Python tab, and enter following script:  

Dir = 'X:\WHERE\YOU\PUT\THE\FILE'  
import sys  

if Dir not in sys.path: sys.path.append(r'X:\WHERE\YOU\PUT\THE\FILE')  

import DynamicChainRigTool  
from DynamicChainRigTool.UI import Main_UI  
reload(Main_UI)  

ui = Main_UI.MainUI()  

# How to use:
Please go to: https://www.bilibili.com/video/av45013722/.
If you have any question, please e-mail me.

# Bugs:
If you find any type of bugs, please e-mail me at: 328665042@qq.com.  
If you like, please STAR this repository. Thank you very much.
