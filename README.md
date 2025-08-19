# ManciniDuffy_AR
Cancini Duffy

# System Requirements 
Unity 6
Blender ( Or any animation software )   
USD Exporter Package (com.unity.exporter.usd)
Unity Recorder Package
Reality Composer ( Can be installed onto iPhones / iPads if unable to access a Mac) 

# Steps - Unity 
1. Create an animation in Blender, or any animation software that can export as an FBX.
2. Export animated sections of a model and non-animated sections seperately into Unity, and make sure the objects pivot point is centered at the origin
3. Open the Unity recorder window and drag the animated section of the model into the Input source tab
4. Go to recording mode and switch it to frame interval
5. Enter the range of frames your animation has
6. Check the output format and change it to USDZ
7. Change the filepath output to wherever you want it to be saved
8. Press start recording and wait until it cycles through the frames
9. Export non-animated sections by going to the USD tab and exporting selected models as USDZ

# Steps - Reality Composer 
1. Import selected USDZ models into reality composer
2. Align them to each other
3. Tap the three dots and scroll to behaviors
4. Add a behavior
5. Choose the scene enter behavior
6. Tap USDZ animation and select the animated section of the model
7. Test the model with the AR button
8. Export project as USDZ

You can now 
