# Houdini Tree Generator

A procedural tree generator created in Houdini using VEX. This tool allows you to create customizable 3D trees with adjustable parameters for trunk height, branch spread, and more.

## Demo

https://youtu.be/dkBasHDk7wQ

## Components

- VEX code for tree generation
- Full Houdini project (.hip) and Digital Asset (.hda) available upon request

## Setup Instructions

### Required Parameters

To use this VEX code, create a new node (e.g., a Wrangle node) and set up the following parameters:

- `trunk_height` (float): Controls the overall height of the trunk
- `trunk_width` (float): Controls the base width of the trunk
- `branch_length` (float): Controls the length of branches
- `branch_spread` (float): Controls how far branches spread from trunk
- `up_angle` (float): Branch angle from vertical (in degrees)
- `branches` (integer): Number of branches to generate
- `random_seed` (float): Seed for randomization
- `branch_variation` (float): Controls variation in branch length

### Recommended Parameter Ranges

- trunk_height: 1-10
- trunk_width: 0.1-1.0
- branch_length: 0.5-5.0
- branch_spread: 0-2.0
- up_angle: 0-90
- branches: 5-50
- random_seed: 0-100
- branch_variation: 0-1.0

## Features

- Procedural trunk generation with natural curve
- Dynamic branch system with:
  - Customizable spread and angles
  - Natural drooping effect
  - Thickness variation
  - Random variation for organic look
- Smooth tapering from trunk to branch tips
- Quaternion-based branch twisting

## Requirements

Houdini 19.5 or later (developed with Apprentice License)
Note: Apprentice License limitations apply to saved files

## License Information
This project was developed using a Houdini Apprentice License. Please note:

Files saved with Apprentice License cannot be used for commercial purposes
HDAs created with Apprentice License can only be loaded in Houdini Apprentice
See SideFX's Houdini Apprentice License Terms for full details
The complete Houdini Digital Asset (.hda) and project file (.hip) are available separately
