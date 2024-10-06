# Chessboard using Python

This Python script generates a graphical representation of a chessboard using matplotlib and numpy. It combines a basic chessboard pattern with a gradient effect overlay for a visually appealing result.

## Features

-Creates an 8x8 chessboard pattern.
-Overlays a smooth mathematical function for aesthetic purposes.
-Utilizes matplotlib for visualization and numpy for numerical operations.

## Requirements

- Python 3.x
-The following Python libraries:
  -matplotlib
  -numpy

## Installation

To run this script, you need to have Python and the required libraries installed.

### Install the required libraries using pip:

```bash
pip install matplotlib numpy
```

## Example

The output will be a chessboard pattern overlaid with a smooth gradient function, displayed in a pop-up window.
![Screenshot 2024-10-06 155425](https://github.com/user-attachments/assets/cdb40414-2759-46df-9697-dec632b079b4)

### Code Overview
-Chessboard Pattern: The chessboard is created using the numpy.add.outer function, which generates alternating values of 0 and 1 for the 8x8 grid.<br>
-Overlay: The chess function adds a mathematical gradient over the chessboard using a combination of polynomial and exponential functions.<br>
-Visualization: matplotlib.imshow is used to render the chessboard and overlay the gradient.<br>
