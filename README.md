# IIEC (Indian Innovation & Entrepreneurship Community) - PYTHON 
>  *Specialization in Python (with flask towards Data Science)*   
Instructor [Mr. Vimal Daga](https://www.linkedin.com/in/vimaldaga/) Sir || [IIEC - RISE](https://www.linkedin.com/company/iiec-rise/) || [Google Drive (screen shots)](https://drive.google.com/drive/folders/1RAJNUsdK2TWK94rrByaouXPkKDlR6-vb) || [Telegram (updates)](https://t.me/joinchat/AAAAAFepWVRLIsjqwCO6_w) || [Discord (doubts)](https://discord.com/invite/DqAgTT)

### DAY 1 | 8 August    
Anaconda | [windows](https://repo.anaconda.com/archive/Anaconda3-2020.07-Windows-x86_64.exe) | [mac os](https://repo.anaconda.com/archive/Anaconda3-2020.07-MacOSX-x86_64.pkg
) | [linux](https://repo.anaconda.com/archive/Anaconda3-2020.07-Linux-x86_64.sh
) | [other](https://www.anaconda.com/products/individual)   
[1. Session](https://www.youtube.com/watch?v=VW0PUBSxVxg&feature=youtu.be) || [Q. How to read data stored in RAM?](https://www.linkedin.com/posts/iiec-rise_how-to-read-the-entire-data-from-the-ram-activity-6698235562727411712-VhnS)    
Note: deadline 15th August    

**Things learnt**   
1. how to make python to launch notepad/ chrome/ any particular site in chrome.
``` python    
import os   
os.system("notepad")
os.system("start chrome")
os.system("start chrome  youtube")
```   
2. how to make python to speak out the argument passed.   
``` python
pip install pyttsx3
import pyttsx3
pyttsx3.speak("Welcome world")
pyttsx3.speak("It's good to learn How to learn")
```     
### DAY 2 | 9 August
[2. Session](https://www.youtube.com/watch?v=Mk3HvO3YEl8&feature=youtu.be) || [Q. How to read data stored in RAM?](https://www.linkedin.com/posts/iiec-rise_how-to-read-the-entire-data-from-the-ram-activity-6698235562727411712-VhnS)

**Things learnt**
1. Summary : 
    -  Fundamentals of learning (how to understand things)
    -  exploring what all we can do with command prompt in windows.
2. New :
    -  Underhood function of accessing an elements in list
    -  Varibales(at a time can store only one element) has its limitation, so we moved to lists
    -  Limitation of list data type (can only do row operations but not col operations), so we moved to numpy array (can do both row and column operations)
    -  In order to use a package first we need to know about it well rather using for the solving the current situation.
    -  whats those `>>>`  in live programming, its called REPL (Read Evaluate Print Loop) | [webiste](https://repl.it/languages/python3)
3. Idea : Take few minutes to go through the core usage/ limitation/ documentation of every module in use.
``` python
notepad test.py  # by deafults it is saved with "test.py" .txt extension
notepad "test.py"  # no extension
dir  # to check it

# when we declare a list to hold multiple elements, access them using list_name[index_number], the underhood function is 
list_name.__getitem__(index_number)

# when we import a module, if we wants to what all the functions it provides
dir(module_name)

# what about built-in functions of python, then try this
dir(__builtins__)
```     
>  **sources :**
-  [Online IDE ](http://repl.it)
-  [Mobile App](https://play.google.com/store/apps/details?id=ru.iiec.pydroid3)     
-  iso download [link 1](https://drive.google.com/file/d/1nZVXCVOy41LjAyOAiHMcNgFIwUlJYw16/view?usp=sharing)   [link 2](https://ia801004.us.archive.org/4/items/rhel-8.0-x86_64-dvd/rhel-8.0-x86_64-dvd_archive.torrent)        

### redhat sessions     
[1. Session](https://youtu.be/8Q83qs2MAVA)      
**Summary**      
-  To find out the way to browse a ram. (Suppose when we intialize any variable x=5; in our program than it is taught to us that it gets stored in ram but now how one can proof that it is present in the ram.) 
-  About GUI(Graphical User Interface) and CLI(Command Line Interface). 
-  How to open applications using terminal (eg. Typing Firefox on the radhat and pressing enter will open the browser) 
-  speak-ng command(to speak what O/P it is giving), date cmd, cal command, which command. 
-  Saw that the cookies that fb and google send to our systems are very critical and even if someone by any way copies them to his/her system can get a complete acess of our Google and Facebook accounts or and other accounts and will never be asked to enter any username password and no otp verification will be there and also  a 3 level verification will not work.

[2. Session](https://youtu.be/JBNvnINsswo)      
**Summary**      
[3. Session](https://youtu.be/lpZysBJ2CRA)      
**Summary**         
[4. Session](https://youtu.be/aPyJQVC6R9E)      
**Summary** 

