ros-install-osx: Melodic on Mojave
===============

This repo contains the files and instructions I used to set up ROS Melodic on Mojave. Almost all of the files are from @mikepurvis's [original repo]() or @bgromov's [modifications](https://gist.github.com/bgromov/23a74bbe846d965964b150080cb2d574). I added 

To start follow the [instructions](https://gist.github.com/bgromov/23a74bbe846d965964b150080cb2d574) from bgromov. My install script differs slightly because I didn't build the full desktop setup. These instructions worked for me up to the build step, at which point I had to make changes to the libraries in `src/` using the files in `build_files_corrected/`. Copy those over, rerun `catkin build --limit-status-rate 1`, and then source the ros workspace.
