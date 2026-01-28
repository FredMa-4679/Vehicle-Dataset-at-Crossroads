# Vehicle Dataset at Crossroads

## Overview

This dataset provides detailed vehicle trajectory data collected at a crossroads intersection. It focuses on vehicle movements across four directions, encompassing 12 distinct driving modalities: left turns, straight movements, and right turns for each direction.

The dataset includes comprehensive information for each vehicle, such as:
- Center coordinates of the vehicle
- Center coordinates of the front and rear axles
- Orientation angle (yaw)
- Speed
- And other detailed attributes

## Current Status

Our dataset is still under development and refinement. Currently, we are releasing only half of the data, covering 6 modalities. The remaining modalities will be added once sorting and processing are completed.

## File Naming Convention

The dataset is organized into the following 12 files:

| File Name | Movement Description |
|-----------|----------------------|
| `01_southbound_left_turn.csv` | From **south** entering, turning **left** |
| `02_southbound_through.csv` | From **south** entering, going **straight** |
| `03_southbound_right_turn.csv` | From **south** entering, turning **right** |
| `04_westbound_left_turn.csv` | From **west** entering, turning **left** |
| `05_westbound_through.csv` | From **west** entering, going **straight** |
| `06_westbound_right_turn.csv` | From **west** entering, turning **right** |
| `07_northbound_left_turn.csv` | From **north** entering, turning **left** |
| `08_northbound_through.csv` | From **north** entering, going **straight** |
| `09_northbound_right_turn.csv` | From **north** entering, turning **right** |
| `10_eastbound_left_turn.csv` | From **east** entering, turning **left** |
| `11_eastbound_through.csv` | From **east** entering, going **straight** |
| `12_eastbound_right_turn.csv` | From **east** entering, turning **right** |


## Usage

This dataset is intended for research in autonomous driving, traffic simulation, and related fields. Feel free to use it under the MIT License terms.

If you have any questions or feedback, please open an issue in the repository.

Thank you for your interest!
