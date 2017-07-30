# ManualAnnotationTool

This utility was created to assist the initialization of the cell tracking and segmentation algorithm described in [1]. 


### Prerequisites

You will need a licensed version of MATLAB.

## Getting Started

Download the code to \<MANUAL-ANNOTATIO-ROOT\>. Make sure that \<MANUAL-ANNOTATIO-ROOT\> is included in the matlab path, or set the current folder \<MANUAL-ANNOTATIO-ROOT\>. 
to start the utility type in the command console:
```
ManualAnnotation
```

### Manual Annotations Steps

## Load the data
1. Press the "Load Data" button on the bottom right side. A pop up window will appear asking if this is an existing project or a new one. Pres the "New" button.
2. A file selection window will appear. Please select the FIRST FRAME in the sequence.
3. Another file selection window will appear. Please select the SECOND FRAME in the sequence.

## Adjusting the contrast:
 The two vertical scrollbars set the low and high values of the image. Change them until the cells are clearly visable. This could be done at any stage of the annotation. NOTE: If nothing happens, try to annotate at least one cell and then the changes may take affect.

## Annotation:
# Adjusting the view:
1. Zoom into the desired are by pressing the zoom icon in the toolbar or by using the shortcut (Ctrl+UpArrow/(Ctrl+DownArrow))
2. Center the desired cell using the pan icon in the toolbar or by using the shortcut (Up/Down/Left/Right arrows)

# New Cell
1. Create a new cell by pressing "New Cell" (Ctrl+N)
2. Start annotating the cell on the left image (Frame \#1)
3. Annotate the cell on the right image (Frame \#2)
4. Repeat for all cells

# Correction
1. Select the desired cell to correct from the dropdown menu in the top right.
2. Press on the desired frame to correct.
3. Press the "Clear" button or use the shortcut (Ctrl+C)
4. Press the "Draw" button or use the shortcut (Ctrl+D)


## Save the current state 
1. Press the "Save" button. 
2. Select a location to save the data.


## Continue from a saved state
1. Press the "Load Data" button on the bottom right side. A pop up window will appear asking if this is an existing project or a new one. Pres the "Continue" button.
2. The utility should revert to the state when saved.

## When Done
1. Press the "Done" button.
2. Select a location to save the output images.  
3. (OPTIONAL) Save the current state

## Keyboard Shortcuts.

*Ctrl + N* - Create a new cell
*Ctrl + Up/Down Arrow* - Zoom in and out
*Left/Right/Up/Down Arrows* - Pan the image
*Ctrl + C* - Clear the current annotation
*Ctrl + D* - Draw the current annotation (Used after Clear)

## Authors

* **Assaf Arbelle**


## License

When using this utility, please cite our paper: ######

## Acknowledgments

* A great thanks to my mentor Dr. Tammy Riklin Raviv

