# Learn to code for data analysis

This repository provides the Jupyter notebooks and datasets for the Open University course
_Learn to Code for Data Analysis_, which was available
twice a year on [FutureLearn](http://tiny.cc/lcda), with discussion forums and facilitator support,
and is now available 24/7 on [OpenLearn](http://tiny.cc/lcda-ol), without forums and without support.

The course was written by Michel Wermelinger (parts 1 and 3),
Rob Griffiths (part 2) and Tony Hirst (part 4).

This repository does _not_ contain the course text. It contains:

- one test notebook to check that your software installation includes Python 3 and 
the necessary data analysis and visualisation libraries;
- one exercise notebook, one project notebook, and the necessary datasets, for each of the 4 parts of the course;
- additional software for interactive pivot tables in part 4.

You can run Jupyter notebooks 
locally on your computer using software like Anaconda, or 
you can run them in the cloud using services like CoCalc and Microsoft Azure. 
Running notebooks in the cloud will be noticeably slower, 
but you won't have to install any software and 
you can run them from wherever you have Internet access. 


## Accessing the Materials via MyBinder / BinderHub

To launch the notebooks in a tempoarary notebook server, click here: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ouseful-testing/Learn-to-code-for-data-analysis/binderised)

If you want to save any of the notebooks used there, you will have to download them as follows:

- as a single notebook from the notebook page `File` menu;
- as a zipped archive file of all notebooks using the the download button on the notebook homepage.

You can also upload your own notebooks from the notebook homepage either individually, or as a zip file. If you upload a zip file, you will need to unzip it. You can do this from a notebook command cell using the `unzip` shell command or [using Python code](https://thispointer.com/python-how-to-unzip-a-file-extract-single-multiple-or-all-files-from-a-zip-archive/). More details can be found in the __TO DO??__

#### Persisting Files on MyBinder

The environment launched from MyBinder is ephemeral - it is created on demand when you click a `launch binder` button and is destroyed after a short period of inactivity.

To save your work when working on MyBinder, there are two approaches you can take:

- using browser storage;
- downloading and uploading files.

##### Using Browser Storage

When running a notebook in MyBinder, on the toolbar you will see a group of three icons:

![](../images/browser_storage.png)

The cloud buttons with the up and down arrows can be used to save the current notebook using your web browser's file storage mechanism.

Click the cloud with the down arrow (*Save to browser storage*) to save a copy of the notebook in your browser's file store. Note that you can do this even if the MyBinder session has timed out, as long as you can see the notebook in your browser.

If you create another MyBinder session at a later time, and open a notebook from the notebook home page, if you remember previously having saved that notebook to notebook storage, you can press the cloud button with the up arrow (*Restore from browser storage*) to replace the copy of the notebook provided by MyBinder by default with the copy you previously saved.

This is a little bit clunky, and means you have to remember that you saved a notebook to browser storage, but it works!

Note also that you save the file to the storage associated with a particular browser. If you save a notebook when using a Firefox browser, the files will not be available if you later visit MyBinder using Chrome.

__TO CHECK: does file storage synch across logged in instances of Chrome?__ 

##### Downloading and Uploading Files

Another way of saving files is to download them to your own computer desktop and then upload then when you want to work on them again. The *Download* button will download the current notebook to you desktop. You can then upload a notebook saved to your desktop using the *Upload* button on the notebook server home page.

![](../images/jupyter_notebook_upload.png)

The "down" arrow button on the top right-hand side notebook homepage will zip and download *all* the files in the notebook listing, including all the files in any subdirectories / subfolders.

Alternatively, if you check a single file from the notebook homepage, you can choose to selectively download just that file by clicking the *Download* button from that is displayed when you check the item.

![](../images/jupyter_select_download.png)

## Instructions (Microsoft Azure)

[![Azure Notebooks](https://notebooks.azure.com/launch.png)](https://notebooks.azure.com/import/gh/mwermelinger/Learn-to-code-for-data-analysis)

You can copy these notebooks directly to Microsoft Azure,
without downloading them first to your computer, and run them there.
To do so, 
if you have used Azure Notebooks before, click the 'launch' badge above,
otherwise follow
[these instructions](Microsoft_Azure_Instructions/README.md).


## Instructions (Anaconda and CoCalc)

To get the notebooks and data files for the course,
click on the green 'Clone or download' button above.
You will see a pop-up window with a button 'Download ZIP'. Click on it. 
The notebooks and data files will be downloaded as a compressed archive: a file with extension `.zip`.
The archive will be in the folder where your web browser usually puts downloaded files.
You will need to double-click on the downloaded file to uncompress it, 
although your browser may have already done that automatically for you.

You should now have a sub-folder named `Learn-to-code-for-data-analysis-master` or similar.
You can rename the folder to whatever name you prefer.
If you will be working on the course using your desktop, e.g. with Anaconda, 
you need to move that folder to anywhere within your home folder,
so that Jupyter can find your notebooks and open them.

If you will be working on the course using a web-based service, e.g. CoCalc, 
you need to upload the folder to that service.

The instructions for installing Anaconda or using Cocalc
are given at the start of the course.

## The course
 
_Learn to Code for Data Analysis_ is a hands-on introduction to computer programming _and_ data analysis. 
It teaches how to access open data and clean, analyse and visualise it. 
It adopts a reproducible research approach: 
the data analysis is written up and publicly shared with the code used in the analysis.
 
The course teaches how to write computer programs, one line of code at a time, 
to download, clean, analyse and visualise open data (using line charts, bar charts and scatterplots). 
The course also teaches how to write up and share data analyses in a reproducible way. 
 
Each part of the course is organised around a specific analysis project using open data from 
the World Health Organisation, the Weather Underground, the World Bank and the United Nations. 
 
All coding and data analysis is done with tools used by professional scientists: 
the Python programming language, the pandas data analysis library and 
the Jupyter Notebooks programming environment.
 
The course does not assume prior experience in programming, data analysis, or statistics, 
but it requires basic numeracy and digital skills, like understanding percentages 
and working with files and folders.

### Learning outcomes
- Understanding basic programming and data analysis concepts
- Awareness of open data sources as a public resource
- Using a programming environment to develop programs
- Writing simple programs to analyse large bodies of data and produce useful results
 
### Syllabus
- Python: variables, assignments, expressions, basic data types, if-statement, functions
- Programming: using Jupyter Notebooks, writing readable and documented code, testing code
- Data analysis: using pandas to read CSV and Excel files, to clean, filter, partition, aggregate and summarise data, and to produce simple charts

### Pedagogy
The course follows 
Merrill's [First Principles of Instruction](https://en.wikipedia.org/wiki/First_Principles_of_Instruction). 
More details on how are [here](http://tiny.cc/fpoi).
