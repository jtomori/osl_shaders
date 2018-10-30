# OSL Shaders

My experiments with **Open Shading Language** shaders, tested in Arnold.


## Setup

* Your environment should have those variables: *(You can set them in **houdini.env** file)*
    ```
    ARNOLD_PLUGIN_PATH = /path/to/this/repo
    ```
* For debugging, add this variable:
    ```
    OSL_OPTIONS = "range_checking=1,debug_uninit=1,max_warnings_per_thread=100,compile_report=1"
    ```