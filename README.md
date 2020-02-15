Install Unity Hub - https://docs.unity3d.com/Manual/GettingStartedInstallingHub.html
Intall Unity Version 2018.4.16f1 with Android support (you will need an account to use the asset store and such)
Add the hack_cewit folder as a project in unity hub 
You can now open it.
Click on the Play icon at the top middle icon to see the animation (When deployed on the VR you can move around but on the PC we can only see it through a window which is the Game View. While Play mode is on you can interact with the objects in the scene bar.)
Open General > Console to see the error messages or logs.


GETTING IT ON THE VR HEADSET
----------------------------
In order to run it on the VR, configure the Rift with your oculus account. Follow the oculus website steps for this. Go to Oculus > Platform > Edit setting and fill in these blanks accordingly.

Then File > Build Setting > Add Scene and  select device.

Click on Player settings; I know the config for Oculus Quest but not for Rift, Look into XR settings(for quest I had to select V2 Signing) then click build and in Other settings select at least Kitkat as the Android version.

Installing something called SideQuest might help with running it on the VR. Oh and you might need drivers for windows to detect the VR headset.

The first build will take time but it becomes faster after that.

The build will give you an apk which you will install on the VR headset.





What it does:
So currently I have this RPG knight character who will walk the kid through the vaccine process; make it sound like a super power and what not. I was working with a force field but it makes everything look very saturated so you can decide what to do about that. The dragons are kind of like the virus the vaccine is supposed to fight off. The dragons are mobile but just needs some tweaks in terms of the trajectory. I have written the script to make them move in a straight line toward the user. Just play with the 3 inputs in the trajectory part to get the right line of movement.

Also to fix the dragon animation; Goto assets>free dragons > animator >souleater CTRL
You just need to create the correct workflow.
