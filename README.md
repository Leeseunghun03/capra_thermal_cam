# capra_thermal_cam
ROS node for the [PureThermal Mini](https://store.groupgets.com/collections/flir-lepton-accessories/products/purethermal-mini-flir-lepton-smart-i-o-module) with a [Flir Lepton 3.5](https://store.groupgets.com/collections/flir-lepton-accessories/products/flir-lepton-3-5)

## Dependencies

This node depends on usb_cam. 

## How to use
- First copy the udev file in your `/etc/udev/rules.d/` folder.
- Compile the repo inside its workspace
- Source your repo
- Launch the node
  - `roslaunch capra_thermal_cam capra_thermal_cam.launch`
- Launch rqt image viewer
  - `rosrun rqt_image_view rqt_image_view`
- To view in web_ui, add camera with topic `/capra_thermal_cam/image_raw`.

## Example (PureThermal 1 / FLIR Lepton 2.5)

![image](https://github.com/user-attachments/assets/29d3ee49-e4fb-41ab-a30d-2814ca77f01b)
