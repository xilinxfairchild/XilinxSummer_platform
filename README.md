# XilinxSummer_platform
# 搭建基于ultra96的block design
vivado版本为2018.2。该文件下bdtcl.tcl为block design的脚本文件。BD，jpg为生成的block design图。
# 配置DPU IP
DPU为2.0版本。该文件夹下DPU.zip为DPU2.0的IP核。
DPU IP为单核B2304模式，且DSP使用模式为Low DSP Usage。
dpu配置参考《DPU for Convolutional Neural Network v2.0》
# 输出petalinux所需.hdf文件。
配套petalinux版本2018.2。
petalinux配置参考《ug1144 PetaLinux Tools Documentation》
