# CerebroCalibrGUI
<b>Description: Eye cam and world cam calibration GUI for CEREBRO (The Head-Mounted Eye-Tracker)</b>
# Basic setup
1. Please load the world camera video into the GUI
2. After that, please load the eye data and world cam timestamps in the correct format (csv).
3. If you want to plot eye data on the world cam, you will have to preprocess the eye data.
4. The status of if all the steps are done correctly can be seen in the console output window and Info panel. 
![Main](https://user-images.githubusercontent.com/63812178/219810039-a2f3211d-7c3a-4d0d-b5bf-f83e762a75b4.PNG)
** essentially this is all you need to get started. 

# visualizing eye data on the world camera
1. for this you need to add a new panel. You can add as many panels as you need.
2. ****please set the frames first before doing anything else.
![setFrames](https://user-images.githubusercontent.com/63812178/219811109-8c92eb2c-a2c5-4dca-b2ef-bcdf7987a073.PNG)
3. You can choose to either display the current frame in the videoplayer or you can do a z-projection for the selected frames.
![Panel](https://user-images.githubusercontent.com/63812178/219810948-16eca7da-4be9-4b57-9c9b-3454c6bdf723.PNG)
4. Once you have set frames and done with the z-projection, you can plot the current data
![Panel_w_plot](https://user-images.githubusercontent.com/63812178/219811026-01dff165-f341-4e83-87ea-a24f9caf26c3.PNG)
5. you can change the styling of your plots using the plot settings panel on the main form.
![Plot_Settings](https://user-images.githubusercontent.com/63812178/219811078-4a44387d-4903-449d-9037-4babf1b9219b.PNG)
6. You can manuplate the scale and offset of the eye data using the transform data under the plot dropdown menu of the panel. 
![transforms_panel](https://user-images.githubusercontent.com/63812178/219811219-4c571160-6758-46de-8efd-80abd4acb106.PNG)
