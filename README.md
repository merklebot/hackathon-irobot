**This image contains basic commands of movement and work with camera, microphone and speaker of iRobot.**

## Image link
Image link could be acquired in **packages** section of the main repository page

## How to use
The container for this image should be runned with flags `--device /dev/ttyUSB0` (**TO CONTROL MOVEMENTS!!**),  `--device /dev/video0` and `--device /dev/snd`. 
Also, environmental varialbes `-e SDL_AUDIODRIVER='alsa'`, `-e AUDIODEV='hw:1,0'`, `-e AUDIO_INPUT_DEVICE='hw:2,0'` shoud be added.

Basic example contained in _main.py_ 
