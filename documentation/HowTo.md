# How To

Guide on __*How To Run Kinesis*__

## First Steps

- Connect projector and speakers to PC
- Start PC and projector
- Open the `Ambient.maxpat` in `Kinesis/max`
- Open the `Kinesis.vl` in `Kinesis/vvvv`
- ! the renderer is white at first, then black with one or more pink dots ! 
- the system is ready as soon as you see a colorful renderer.

- By default the patch is set to play and loop. The only thing that is not implemented yet to start completely autonomously is the detection of a person that enters the room. So just for initialization `OnPersonEnter` needs to be triggered once by __rightclicking the bang__. Then it will loop infintely. See below

![Initalize](./img/startInstallation.gif)

- click on the renderer window and press `ALt + Enter`to enter Full Screen Mode
- __*Kinesis* is up and running!__

Depending on the setup, it can be that the transformation variable in the content node needs to be set once. It readjusts everything depending on the hight and angle of the Kinect. In my test setup. The Kinect is attatched to the wall above the projection at 2m hight and looking down in a 45° angle.
This is something that I would try to make easier, so people that don't know VVVV can setup the installation entirely.

For more detailed info's refer to this [Miro Board]([https://duckduckgo.com](https://miro.com/app/board/uXjVPHW5M0w=/?share_link_id=838551012172) "Kinesis Setup & issues").
