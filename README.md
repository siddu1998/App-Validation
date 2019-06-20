# App-Validation
### Camera Matrix 
Camera parameters required for any of the methods are found in the cameraMatrix.yaml file. These have been found using the checkerboard.



### Breaking down the directory
App Validation
|
|
|----No Parking
    |---Images
    |---BirdsEye View
        |---bird view
        |---marked points
    |---Code
    |---Two Point


|----Walking
    |--(simillar structure as above)
|----cameraMatrix.yaml
|----master_log_2_point_method_and_birdsview_for_collected_dataset.xlsx
|----ReadMe



### width of pavements
While calculating the birdseyeview, we have 300 pixels along the x-direction which correspond to the pavement width. This allows us to establish a relation between and identify the pixels per meter along x, which can be further used to get the pixels per meter along the y-direction.

No parking sign has a road width of 1.70688meters
Walking sign has a road width of 1.85928meters

