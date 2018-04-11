# Tools:
- CubeMX
- Cortex-Debug (vscode plugin)
- GNU ARM Embedded Toolchain 
- GNU Make/mingw32-make
- OpenOCD
- SVD files (they provide description of the peripherals of the microcontroller, can be found [here](https://github.com/posborne/cmsis-svd))

# Configuration

## Debugger
This example uses OpenOCD and ST-Link V2, if you use different tools check [this](https://marcelball.ca/projects/cortex-debug/) out.

# todo
- absolute paths in launch.json, unfortunately vscode is not supporting user-created custom variables
