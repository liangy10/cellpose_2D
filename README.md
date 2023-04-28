# cellpose_2D
This is the code we use to segment cell culture images with bright field and other fluorescent channels. 
First, you have to install cellpose through anaconda. See instructions here: https://pypi.org/project/cellpose/#:~:text=To%20install%20the%20minimal%20version,install%20'cellpose%5Bgui%5D'.
Then you can open the terminal (click "Type here to search" in windows, then choose "Annaconda Prompt", it will look like this
(base) C:\Users\yajie.liang>
You need to activate the cellpose module by typing:
(base) C:\Users\yajie.liang>conda activate cellpose
Then you will see you have entered into the cellpose module:
(cellpose) C:\Users\yajie.liang>
From here, you can open cellpose gui by typing "python -m cellpose". You will see this:

(cellpose) C:\Users\yajie.liang>python -m cellpose
2023-04-28 15:30:00,397 [INFO] WRITING LOG OUTPUT TO C:\Users\yajie.liang\.cellpose\run.log
2023-04-28 15:30:00,397 [INFO]
cellpose version:       2.2
platform:               win32
python version:         3.8.16
torch version:          2.0.0+cpu
2023-04-28 15:30:00,717 [INFO] TORCH CUDA version not installed/working.

From the GUI, you can segment and traim models. 

In another scenario, if you want to process large batch of images, you need to run it through notebook or visual studio code. 

This is an example code for notebook: 
https://github.com/MouseLand/cellpose/blob/main/notebooks/run_cellpose.ipynb

