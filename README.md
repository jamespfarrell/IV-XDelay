# IV-X Delay VST Plugin

IV-X Delay is a free and open source delay VST effect modelled after a renowned vintage tape recorder. Its aim is to provide music producers with a fun and useful tool that sounds and works like vintage tape echo boxes, as well as to serve as an educational tool for anyone interested in audio development and digital signal processing.

This project has been developed using the JUCE framework as a wrapper and a GUI editor, and the r8brain resampling library to provide upsampling up to 192kHz. The rest of the DSP processing, including delay lines, filter and saturation implementations have been designed from the ground up using C++ realtime-safe features and data structures.

This code is licensed under a GPLv3 free software license. All other libraries used within this project are also licensed under open source licenses. Precompiled versions of the plugin are available as releases in this repository. In order to use them, download a release and copy the corresponding files to you computer's VST folder. Both Linux Makefiles and Visual Studio solutions are available to anyone who wishes to compile any version of the plugin, in the Builds folder. the JUCE Framework is not necessary, as its relevant modules are also included in this project. git-LFS is needed in order to clone the large noise tables.

