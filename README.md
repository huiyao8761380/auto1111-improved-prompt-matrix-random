# auto1111-improved-prompt-matrix-random

This script is [advanced-prompt-matrix](https://github.com/GRMrGecko/stable-diffusion-webui-automatic/blob/advanced_matrix/scripts/advanced_prompt_matrix.py) modified to support `batch count`. Grids are not created.  

https://github.com/ArrowM/auto1111-improved-prompt-matrix

## Usage

Use `<` `>` to create a group of alternate texts. Separate text options with `|`. Multiple groups and multiple options can be used. For example:

An input of `a <corgi|cat> wearing <goggles|a hat>`  
Will output 4 prompts: `a corgi wearing goggles`, `a corgi wearing a hat`, `a cat wearing goggles`, `a cat wearing a hat`

Each output prompt will be generated for each seed when using a `batch count` > 1. `batch size` is ignored.

 

 

 

![CN](https://github.com/huiyao8761380/auto1111-improved-prompt-matrix/blob/main/7B7JUF%25MY2ZQ0S4%7B%5BKKYRDG.png)
