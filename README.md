# CerebroCalibrGUI
<b>Description: Eye cam and world cam calibration GUI for CEREBRO (The Head-Mounted Eye-Tracker)</b>
# Requirements:
1. A video from the world camera of the animal
2. timestamps for each frame of the world camera video as a row in CSV format.Note: These time stamps should be synchronized with the eye camera.
3. eye data with each row being data from a frame of the eye camera containing 3 columns in the following format a)timestamp b)x-coor c)y-coor
# Basic setup
1. Please load the world camera video into the GUI
2. After that, please load the eye data and world cam timestamps in the correct format (csv).
3. If you want to plot eye data on the world cam, you will have to preprocess the eye data.
4. The status of if all the steps are done correctly can be seen in the console output window and Info panel. 
5. ![Main_3](https://user-images.githubusercontent.com/63812178/221701164-5b92c031-7928-4d26-b6e3-579f29681f34.PNG)
6. ** essentially this is all you need to get started. 

# visualizing eye data on the world camera
1. for this you need to add a new panel. You can add as many panels as you need.
2. ![Panel_3](https://user-images.githubusercontent.com/63812178/221701197-a8f9e7e9-07bf-4248-8e65-22877519cb6f.PNG)
3. ****please set the frames first before doing anything else.
4. ![setFrames_3](https://user-images.githubusercontent.com/63812178/221701216-d0aac73c-09eb-46d6-95f3-80a8127b3a0f.PNG)
5. You can choose to either display the current frame in the videoplayer or you can do a z-projection for the selected frames.
6. Once you have set frames and done with the z-projection, you can plot the current data
7. ![Panel_w_plot_3](https://user-images.githubusercontent.com/63812178/221701257-f567347c-8611-4f9b-9e4b-c1cf40296c4a.PNG)
8. you can change the styling of your plots using the plot settings panel on the main form.
9. ![Plot_Settings_3](https://user-images.githubusercontent.com/63812178/221701287-8503145b-640b-4535-aa4d-15a87b0b4735.PNG)
10. You can manuplate the scale and offset of the eye data using the transform data under the plot dropdown menu of the panel. 
11. ![transforms_panel_3](https://user-images.githubusercontent.com/63812178/221701322-cd3605da-85c3-4b0f-896d-3f47a513d756.PNG)
# export data
1. you can export the transformed data from the file selector menu. It will open up a dialog box to allow you to select destination for saving the processed data in the following format. (a)eye_frame_no,(b)eye_timestamp,(c)eyeX,(d)eyeY,(e)wrld_frame_no,(f)wrld_timestamp
2. You can also export a video with eye data overlayed on it. The marker size and characteristics can be set using the "plot controls" menu.
