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

2. Navigate to the render directory:

    ```bash
    cd render

3. Build the program using make:
   ```bash
    make

The compiled program will be available as ./render.

##  Usage
Running the Snow Demo
1. To run the snow demo:

    ```bash
    ./render snow

2. Viewing Options
For a full list of available options, use:

   ```bash
   ./render --help