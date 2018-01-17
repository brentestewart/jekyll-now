---
published: true
---
My current development rig includes my Surface Book and two external monitors and it always bugged me that I couldn’t setup different wallpapers on each monitor.  So I did a little research and found out, that while it is not obvious, Microsoft did provide a way to make it happen without the need of any third party software.

### Step 1
Multi-select (ctrl-click) the photos you want to use and right click one of them and select “Set as Desktop Background.” Your pictures should now be distributed across you monitors.
![Step One](/images/wallpaper_step_one.png)


### Step 2
Open the Run command by right clicking the Start Icon and selecting Run.  Then type “control /name Microsoft.Personalization /page pageWallpaper” in the Run dialog and click OK.  This is a hidden page that cannot be accessed from the control panel.
![Step Two](/images/wallpaper_step_two.png)


### Step 3
Click the Clear All button to deselect all pictures (this prevents windows from cycling through the select pictures).  Then you can right click on each picture and assign it to the monitor of your choice.
![Step Three](/images/wallpaper_step_three.png)
