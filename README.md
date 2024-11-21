# Render Program

This repository contains the `render` program, a tool designed for rendering visual scenes. Below, you'll find instructions on how to set up and use the program.

## Requirements

- CUDA Toolkit 11.7
- A compatible GPU
- A Linux-based system with support for `make`

## Installation

1. Update your `PATH` environment variable to include the CUDA binaries:
   ```bash
   export PATH=/usr/local/cuda-11.7/bin:${PATH}
Navigate to the render directory:


cd render
Build the program using make:

make
The compiled program will be available as ./render.

Usage
Running the Program
To render the default scene, simply execute:


./render

Running the Snow Demo
To run the snow demo:


./render snow
Viewing Options
For a full list of available options, use:


./render --help
Example Commands
Render a specific scene:
bash
复制代码
./render <scene_name>
Adjust program settings via command-line options:
bash
复制代码
./render --option1 value1 --option2 value2





