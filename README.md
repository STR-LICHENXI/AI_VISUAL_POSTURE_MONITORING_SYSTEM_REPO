# AI_VISUAL_POSTURE_MONITORING_SYSTEM_REPO
A real-time AI posture monitoring system built with OpenCV and MediaPipe to prevent back pain.

OVERVIEW & FEATURES 

It is a real-time AI posture monitoring system built using python , opencv , mediapipe from google.

So this is basically a program i developed to solve a problem I faced oftenly : My bad sitting posture hurts my back . So I use the AI model from media pipe to help monitoring my body posture based on algorithem i came up with so that it gives warning  when it identifies my bad body posture.

HOW IT WORKS 

The algorithem identifies bad posture by measuring the vertical distance between the midpoint of the ears and shoulders. It determines bad posture by comparing this distance with a preadjusted threshold (which can be adjusted based on your own computer/table angle relative to your body /chair as well.)

I spent alot of time to do this project , I'm not really that satisfied with it , but that is mostly due to limitation of hardware rather than code.  Anyway , it works !  


INSTALLATION

In order to run this program , firstly copy the code to your whatever IDE you have.
Type the following to your terminal :
pip install opencv-python mediapipe

Then copy the code to your whatever IDE you have. 
Then try download the 'pose_landmarker_lite.task'  file as well .  
( there is only one file you need to download though )

## Important
Make sure to go to the code section where it says:
    base_options=BaseOptions(model_asset_path="D:\GITHUB1_MONITOR\pose_landmarker_lite.task"),
and change the location of the file 'pose_landmarker_lite.task' to your own. 

In the end , make sure you have camera on and keep in mind that the parameter is only adjusted to match the angle of camera and chair of the developer(me) , which is guaranteed to work terribly on you. Hence feel free to adjustment based on your unque angle with the camera. 


If any mistakes exist in the code or the process, please inform me and give me mercy . (I'm still a high school beginner on programming and GitHub. )
