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
5. ![Main_2](https://user-images.githubusercontent.com/63812178/220444851-9a191f99-255c-41f7-95a7-6bf73dbac733.PNG)
** essentially this is all you need to get started. 

# visualizing eye data on the world camera
1. for this you need to add a new panel. You can add as many panels as you need.
2. ![Panel_2](https://user-images.githubusercontent.com/63812178/220445029-68bb6139-6566-4797-857a-7b29235e444a.PNG)
3. ****please set the frames first before doing anything else.
4. ![setFrames_2](https://user-images.githubusercontent.com/63812178/220444948-cadd7023-55a7-47b5-83cc-25dd49f6312f.PNG)
5. You can choose to either display the current frame in the videoplayer or you can do a z-projection for the selected frames.
6. Once you have set frames and done with the z-projection, you can plot the current data
7. ![Panel_w_plot_2](https://user-images.githubusercontent.com/63812178/220445158-4cf2c54a-32f6-497c-a6da-6a2665395245.PNG)
8. you can change the styling of your plots using the plot settings panel on the main form.
9. ![Plot_Settings_2](https://user-images.githubusercontent.com/63812178/220445207-c91782df-eb33-4b42-9e7b-4decf42e0d7b.PNG)
10. You can manuplate the scale and offset of the eye data using the transform data under the plot dropdown menu of the panel. 
11. ![transforms_panel_2](https://user-images.githubusercontent.com/63812178/220445253-dd487230-bfb3-40bc-a849-e43c4937e165.PNG)
# export data
1. you can export the transformed data from the file selector menu. It will open up a dialog box to allow you to select destination for saving the processed data in the following format. (a)eye_frame_no,(b)eye_timestamp,(c)eyeX,(d)eyeY,(e)wrld_frame_no,(f)wrld_timestamp
2. You can also export a video with eye data overlayed on it. The marker size and characteristics can be set using the "plot controls" menu.
