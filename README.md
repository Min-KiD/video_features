
## Input
The inputs are paths to video files.
Paths can be passed as a list of paths or as a text file formatted with a single path per line.


## Output
Output is defined by the `on_extraction` argument; by default it prints the features to the command line.
Possible values of output are ['print', 'save_numpy', 'save_pickle']. `save` options save the features in
the `output_path` folder with the same name as the input video file but with the `.npy` or `.pkl` extension.


