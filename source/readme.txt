to install an environment using the .ymal file,
open your terminal, change directory to the path where you want to create the env
use the command below:
conda env create -f data.yml (note that the data.yml file should be in the same directory)

to install packages in your base or dedicated env use the command below

conda install --file requirements.txt
 again, make sure to run the command while you are already in the directory where the .txt file is located
