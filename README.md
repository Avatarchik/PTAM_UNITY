## PTAM in UNITY

this is the PTAM stereo visual studio project for VisionerTech VMG-PROV. It is used to sense the environment and localize the headset.

## Requirement:

1.  Recommended specs: Intel Core i5-4460/8G RAM/GTX 660/at least two USB3.0/
2.  Windows x64 version.(tested on win7/win10)

## Installation

1.  Download and install the  Visual Studio 2012, the download address is here: https://www.microsoft.com/zh-cn/download/details.aspx?id=30682

2.  Download and install OpenCV(version 2.4.X) as:
http://docs.opencv.org/2.4.11/doc/tutorials/introduction/windows_install/windows_install.html

3.  Open "PTAM_UNITY/RenderingPlugin/VisualStudio2013/RenderingPlugin.sln", then change settings for visual studio project linked with OpenCV:
http://docs.opencv.org/2.4.11/doc/tutorials/introduction/windows_visual_studio_Opencv/windows_visual_studio_Opencv.html

## How to Run

1. Build "/RenderingPlugin/VisualStudio2013/RenderingPlugin.sln" release version, RenderingPlugin.dll will copy to corresponding unity folder automatically.
2. Put camera parameters got from stereo_calib or stereo_calib_executable to "/UnityProject/save_param/"
2. As in stereo_seethrough, use Unity open "/UnityProject/" folder and double click "scene", then click run!
