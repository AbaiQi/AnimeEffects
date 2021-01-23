# AnimeEffects
A 2D animation tool which doesn't require a carefully thought-out plan.  
It provides various animation functions based on deformation of polygon mesh.  

http://animeeffects.org/en/

Note: For the present, there may be incompatible changes without notice in advance.

## Development Environment
* Windows/Linux/Mac
* Qt5.7 or later
* MSVC2015/MinGW/GCC/Clang (32-bit or 64-bit)

## Runtime Requirements
* OpenGL4.0 CoreProfile or later
  * On linux, you can check whether your graphics card supports OpenGL4.0 CoreProfile or not, run `glxinfo | grep "OpenGL core profile version"` on your terminal
* FFmpeg (Please install ffmpeg on your own for video exporting, you can also place a ffmpeg executable in /tools.)


--------------------------------------------------------------------------------------------------
简体中文介绍
# AnimeEffects

这是一款很容易地操作的2D关键帧动画制作软件。 
AnimeEffects提供各种动画键，如移动，旋转，缩放，骨变形，自由形变，不透明度和图像变化。 您可以导入图像文件，如JPEG，PNG，GIF和PSD用于动画资源。 对于PSD，AnimeEffects支持图层剪切和许多混合模式。

http://animeeffects.org/en/

注意：目前，可能会有不兼容的更改，恕不另行通知。
开发环境

     Windows / Linux / Mac
     Qt5.7或更高版本
     MSVC2015 / MinGW / GCC / Clang（32位或64位）

linux下编译

ubuntu20.04下示范,系统默认Qt5.12.8

安装依赖库

sudo apt install qtcreator(qtcreator是Qt官方的集成开发环境包)

下载源码

git clone https://github.com/AbaiQi/AnimeEffects.git

编译

cd /AnimeEffects

qmake

make


运行时要求

     OpenGL4.0或更高版本
         在Linux上，检查显卡是否支持OpenGL4.0，在终端上运行命令“glxinfo | grep OpenGL”。即可查看OpenGL支持版本。     
     FFmpeg（自行安装ffmpeg以进行视频导出，也可以在/tools中放置一个ffmpeg可执行文件。）  
    FFmpeg官方下载地址
    https://ffmpeg.org/download.html

附
本软件汉化参考Adobe Photoshop官方简体中文版上的功能译名。
