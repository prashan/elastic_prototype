# elastic_prototype

Data Folder
************************************************
The data is found in the "data" folder. 
Training data - data\nutrition_folds\fold1\train\fold_1_train.csv
Testing data  - data\nutrition_folds\fold1\test\fold_1_test.csv

Code
************************************************
ellipse alternating -> use ellipse_alternating.py
rectangular alternating -> use rectangular_alternating.py
rectangules hierarchial -> use rectangular.py

Sample commands for running 
____________________________________
ellipse alternating
_____________________________________
template of command
python <file_name.py> -d <data_directory> -o <output_file_name> -b <number_of_balls_to_start_with> -f <fold_number>
command
python ellipse_alternating.py -d nutrition_folds -o dec1_ellipse_only_seed230_3 -b 5 -f 1
*note the data is provided for 1 fold.

____________________________________
rectangular alternating
_____________________________________
template of command
python <file_name.py> -d <data_directory> -o <output_file_name> -b <number_of_balls_to_start_with> -f <fold_number>
command
python rectangular_alternating.py -d nutrition_folds -o dec1_rectangular_alt_seed230_6 -b 5 -f 1
*note the data is provided for 1 fold.

_____________________________________
rectangules hierarchial 
_____________________________________
template of command
python <file_name.py> -d <data_directory> -o <output_file_name> -b <number_of_balls_to_start_with> -f <fold_number>
command
python rectangular.py -d nutrition_folds -o dec1_rectangular_only_seed230_6 -b 5 -f 1
*note the data is provided for 1 fold.

____________________________________
Output generation
____________________________________
When the program runs it will generate relevant .jpg files and .pdf files that shows the prototypes/subspaces. The .jpg files will be 2d or 3d plots of the chosen subspaces. The .pdf file will contain the information in the .jpg files and in addition would also contain more details about the chosen prototypes and classifications.

