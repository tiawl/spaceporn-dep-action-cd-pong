# spaceporn-action-cd-pong

A composite action triggered on repository dispatch event. It is activated on new release notification. It parses the new release's data, update content of the repository and open a pull request.

## Important note

This composite action is not intented to be used outside of the [tiawl/spaceporn][1] dependencies chain. For this reason, there are no contributing file/rules on this repository. However feel free to open an issue if you have a question. We will be happy to answer.

## CICD reminder

These repositories are automatically updated when a new release is available:
* [tiawl/toolbox][2]
* [tiawl/vulkan.zig][3]
* [tiawl/wayland.zig][4]
* [tiawl/X11.zig][5]
* [tiawl/glfw.zig][6]
* [tiawl/cimgui.zig][7]
* [tiawl/spirv.zig][8]
* [tiawl/glslang.zig][9]
* [tiawl/shaderc.zig][10]
* [tiawl/libjq.zig][15]
* [tiawl/spaceporn][1]
* [tiawl/spaceporn-action-env][11]
* [tiawl/spaceporn-action-bot][12]
* [tiawl/spaceporn-action-ci][13]
* [tiawl/spaceporn-action-cd-ping][14]

This repository is automatically updated when a new release is available from these repositories:
* [tiawl/spaceporn-action-env][11]
* [tiawl/spaceporn-action-cd-ping][14]

## License

This repository is dedicated to the public domain. See the LICENSE file for more details.

[1]:https://github.com/tiawl/spaceporn
[2]:https://github.com/tiawl/toolbox
[3]:https://github.com/tiawl/vulkan.zig
[4]:https://github.com/tiawl/wayland.zig
[5]:https://github.com/tiawl/X11.zig
[6]:https://github.com/tiawl/glfw.zig
[7]:https://github.com/tiawl/cimgui.zig
[8]:https://github.com/tiawl/spirv.zig
[9]:https://github.com/tiawl/glslang.zig
[10]:https://github.com/tiawl/shaderc.zig
[11]:https://github.com/tiawl/spaceporn-action-env
[12]:https://github.com/tiawl/spaceporn-action-bot
[13]:https://github.com/tiawl/spaceporn-action-ci
[14]:https://github.com/tiawl/spaceporn-action-cd-ping
[15]:https://github.com/tiawl/libjq.zig
