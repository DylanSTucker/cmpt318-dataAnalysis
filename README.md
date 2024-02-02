CMPT 318  Data Analysis Project

Description:
This project was developed for the class cmpt 318 data analytics which was taken at the University of Saskatchewan in 2023 during the fall semester.
The project uses a data set that was sourced from kaggle, which can be found using the following link: https://www.kaggle.com/datasets/arashnic/game-review-dataset/
The goal for this project was to analyse a data set of user video games from steam and construct a model to determine if user recommendations can be predicted based on genre tags.

The report folder contains detailed information on each step of the project including the methods I used to analyse and clean the data.

The model was not able to accurately predict user recommendations based on genre tags. A lack of data and data diversity may have contributed to this outcome.
More details on the projects results and methods can be found in the results.pdf and methods.pdf file inside the 'Report' folder.


Installation:
#clone repository
git clone https://github.com/DylanSTucker/cmpt318-dataAnalysis.git

#navigate to root directory
cd cmpt318-dataAnalysis

#switch to results branch
git checkout results



How to Run:
This project uses the python programming language.

The following data set will need to be downloaded from the website kaggle before running this project: https://www.kaggle.com/datasets/arashnic/game-review-dataset/
Create a new folder called 'Data' inside the root folder of this project and put the data set inside the newly created 'Data' folder.

Libraries such as pandas, numpy, seaborn, and sklearn will need to be installed before running the project.
use the following commands in a terminal before running this project:
#for installing the pandas library
pip install pandas

#for installing the numpy library
pip install numpy

#for installing the seaborn
pip install seaborn

#for installing the sklearn library
pip install sklearn


License:
MIT License

Copyright (c) 2023 Dylan Tucker

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
