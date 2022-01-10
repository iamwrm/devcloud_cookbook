# devcloud_cookbook

https://devcloud.intel.com/oneapi/documentation/analytics-toolkit/
https://devcloud.intel.com/oneapi/documentation/shell-commands/

https://github.com/oneapi-src/oneAPI-samples/
https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/DPC%2B%2BFPGA/Tutorials/GettingStarted/fpga_compile
https://github.com/oneapi-src/oneAPI-samples/tree/master/DirectProgramming/DPC%2B%2BFPGA/Tutorials/GettingStarted/fast_recompile

```
pbsnodes | less
qsub -I -l nodes=s011-n003:ppn=2
qsub -I -l nodes=1:gpu:ppn=2 -d .
```