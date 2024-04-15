<!-- <div align="center">
    <img src="https://github.com/Htbibalan/PYTHON_COURSE_2024/blob/main/source/construct.webp" width="120" height="120" alt="Icon" title="Icon Title">
</div> -->

<div align="center">
    <h4>This repository works best in dark mode and on a vertical screen &#x26A0;</h4>
</div>

![Banner Image](https://github.com/Htbibalan/PYTHON_COURSE_2024/blob/main/source/trump_old.webp)
The image created by DALL.E shows a 35mm film style photo of a man sitting in the oval office typing a letter.

##### "As a political figure, Donald J. Trump used Twitter to praise, to cajole, to entertain, to lobby,  to establish his version of events — and, perhaps most notably, to amplify his scorn"
                        Kevin Quealy
                        The Complete List of Trump’s Twitter Insults (2015-2021)
                        The New York Times | 19.01.2021


# Overview
#### This repository primarily contains data, Python scripts, and plots for a project required by the course **HEL-8048-1 24V Advanced Data Analysis and Visualization Using Programming** at UiT The Arctic University of Norway. Below you will find more information about the organization of this repository, the source of data and further necessary details.

# The source and structure of data

![the new york times](https://github.com/Htbibalan/PYTHON_COURSE_2024/blob/main/source/0126_ittart-jumbo.webp)
"About 850 individuals were targets of former President Trump’s scorn on Twitter."
© Mikki Janower for The New York Times. 

#### The data used in this project was initially downloaded from [kaggle](https://www.kaggle.com/datasets/ayushggarg/all-trumps-twitter-insults-20152021). The data reflects all the tweets^ containing insults, posted by Donald Trump, the former US president from 2015 to 2021. Unlike what one might expect, no coding, text mining or natural language processing was used to extract data from tweets posted by Donald Trump, rather a group of journalist lead by Kevin Quealy <sub>***manually*** </sub> read all the tweets and marked insults and targets! You can read more about this process in an interview published on [The New York Times ](https://www.nytimes.com/2021/01/26/insider/Trump-twitter-insults-list.html). 

#### In this project, I filtered the data and limited the tweets to posts between 2017-2020 which corresponds to his years in the office.

^ I use the word "Tweets" and "Twitter" although the name of the brand is changed to X. Simply because I do not like the new name and logo!

# The organization of this repository
* **/data** stores .csv files containing data used in this project
* **/notebooks** is where you will find the script used in this project to filter, group and plot the data, the only script you need to use is ***hel8048_project.ipynb***
* **/plots** is the folder where the figures generated by the script are stored
* **/results** is the folder where the "final" results and plots of the study are represented with captions, this directory also contains a separate "readme" file that will be automatically displayed as soon as you open the link.
* **/source** contains some files(e.g icons or images) used either in the home-page or other folders of the repository and files you might need to run the project script

# Info desk
#### How to use this repository?
* Clone the repository: run your anaconda prompt (terminal), change directory to your desired pathway and use this command:

                git clone https://github.com/Htbibalan/PYTHON_COURSE_2024.git
* In case you are missing some packages used in this project, you can use the **"/source/requirements.txt"** to install them all at once. In order to install the packages, you can use the command below either in your base environment or any other specific environment:

                conda install --file requirements.txt
    before running the command, make sure to change the directory to the pathway where the files is stored.

* You can create this environment using the the file **"/source/data.yaml"** where "data" will be the name of the environment that will be created, to do so, in your terminal change the driectory to the pathway where you want to create the environment and place the "data.yaml" in that folder, then run the command below:

                conda env create -f data.yaml

    Once created, make sure to switch to the newly created environment using the command below:

                  activate data




# License
            MIT License

            Copyright (c) 2024 Htbibalan

            Permission is hereby granted, free of charge, to any person obtaining a copy
            of this software and associated documentation files (the "Software"), to deal
            in the Software without restriction, including without limitation the rights
            to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
            copies of the Software, and to permit persons to whom the Software is
            furnished to do so, subject to the following conditions:

            The above copyright notice and this permission notice shall be included in all
            copies or substantial portions of the Software.

            THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
            IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
            FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
            AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
            LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
            OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
            SOFTWARE.




