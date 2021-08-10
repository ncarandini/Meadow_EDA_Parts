# Eagle Install instructions

## 1. Find the Eagle library folder location

Open Eagle and use the `Eagle | Options | Directories...` command to open the `Directories` dialog:

![Open directories dialog from the Eagle Control Panel](readme-images/eagle-install/image_01.png)

and take note of the Libraries path:

![Directories dialog](readme-images/eagle-install/image_02.png)

from now on we'll refer to it as the `Eagle libraries` folder.

## 2. Copy the files

Now from GitHub project download the folder `Eagle\Meadow F7 Micro` (containing the `EAGLEMeadowEDA.lbf` file) to the `Eagle libraries` folder:

![Copy files](readme-images/eagle-install/image_03.png)

## 3. Activate the Meadow library

Now back to Eagle Control pannel, right click to the `Eagle\Meadow F7 Micro` folder and select `Use all`.

![Activate the Meadow library in the Eagle Control Panel](readme-images/eagle-install/image_04.png)

and you're good to go:

![Library content in the Eagle Control Panel](readme-images/eagle-install/image_05.png)

Have fun!

P.S. We are still working to make the 3D model for Eagle. If you like to contribute, please start from the STEP model found in the `3D_Models` folder and send us a pull request.