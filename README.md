# transparent-window-unity
allows you to make your unity window transparent on build 
(note: unitys built in ui doesnt work for this i cant figure out why you will need to create your own)

how to set up:
1. create an empty game object and place the script on it
2. place the camera on the script in the inspector
3. make the camera background fully black with 0 alpha
4. go to edit->project settings->player->resolution and tick the Run In Background button(this doesnt have to be ticked but it will look alot better if it is)
5. go to build settings > player and untick Use DXGI Flip Model Swapchain for D3D11
6. build the project and it should be transparent
