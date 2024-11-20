# transparent-window-unity
allows you to make your unity window transparent on build 
(note: unitys built in ui doesnt work for this i cant figure out why you will need to create your own)

how to set up:
1. download the script and import it into unity
2. place the script onto the main camera
3. make the camera background fully black with 0 alpha
4. go to "edit-> project settings-> player-> resolution" and enable "Run In Background"
5. disable "Use DXGI Flip Model Swapchain for D3D11" (in the "Standalone Player Options")
6. build the project and it should be transparent
