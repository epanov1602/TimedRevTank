## How to deploy this to an FRC Robot with Rev motors
Watch the video and follow the steps: https://github.com/epanov1602/TimedRevTank/

* If you need to download PyCharm, download from here:
https://www.jetbrains.com/pycharm/download/


* Open PyCharm and choose "Get from VCS"
![image](https://github.com/user-attachments/assets/33d91d52-9ac5-494c-adf8-1d85e50d3b18)


* If you don't see "Get From VCS", click the menu in the upper left corner and choose "Project from Version Control"
![image](https://github.com/user-attachments/assets/56edeab1-a5e9-4543-b984-ac8b8d67db14)


* Once you see the dialog, make sure to paste `https://github.com/epanov1602/TimedRevTank/` as URL and hit "Clone"
![image](https://github.com/user-attachments/assets/86656368-b45c-4362-bf78-006f3752f425)


* After the code is cloned (downloaded), you might need to click at the lower right corner of PyCharm window to choose another Python version
![image](https://github.com/user-attachments/assets/0fda813b-a66b-4ced-85e1-8cac48c36605)

, or you might see it in the upper right corner of the window
![image](https://github.com/user-attachments/assets/3b33481b-34df-4099-ad2b-479fe9921345)


* Try opening the robot code (single module: `robot.py`)
![image](https://github.com/user-attachments/assets/6b110d06-4ad4-4428-acc7-b50276c23b30)
(you will likely be offered to install "robotpy" package -- say yes)
![image](https://github.com/user-attachments/assets/a02d2474-13b8-4f0c-8715-a15626e9c205)


* Inside of the robot code you see four motors and their directions, you can change as you wish.
But ultimately you can `deploy` this code to the robot (or run it in `sim`), but before you are allowed to do it you must `sync`:
![image](https://github.com/user-attachments/assets/d151b3ad-96d4-410c-858a-3844e168bd1d)
