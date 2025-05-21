# HLND2T_DiligentGraphics

Closed-source GoldSrc-like engine with [DiligentGraphics](https://github.com/DiligentGraphics/DiligentEngine) as RHI and [slang](https://github.com/shader-slang/slang) as shading language.

This is a technical verification demo that completely overhaul the vanilla graphics pipeline.

This will be ported to real GoldSrc and SvEngine once all features are stable.

Download: https://github.com/hzqst/HLND2T_DiligentGraphics/releases

## Supported backends:

* D3D12 ( launch parameter: `-d3d12` )

* D3D11 ( launch parameter: `-d3d11` )

* Vulkan ( launch parameter: `-vk` )

* OpenGL ( launch parameter: `-gl` )

* WebGPU ( launch parameter: `-webgpu` )

## Following issues are accepted :

1. Graphics artfacts / glitch (* Your graphics card & graphics driver & the graphics backend you were running on, in detail)

2. Fatal Error (with msgbox prompt) (* Please describe how to trigger the Fatal Error, in detail)

3. Slience Crash (* Please describe how to trigger the crash, in detail)

4. Visual inconsistency with vanilla engine. (*Except dynamic lights)

## Following issues are unaccepted :

1. Performance issue (* like why I can't get 600fps on 4k res or why I am getting stuttering)

2. Feature request

## Screenshots

![](/img/1.png)

![](/img/2.png)