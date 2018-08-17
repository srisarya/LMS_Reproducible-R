# Reproducible Research in R  

[![Join the chat at https://github.com/LMSBioinformatics/Reproducible-R](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/mrccsc/Reproducible-R?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![Build Status](https://travis-ci.org/mrccsc/Reproducible-R.svg?branch=master)](https://travis-ci.org/mrccsc/Reproducible-R)


##The Course

This course introduces R and statistical programming as well as best practices for reproducible research using R's dynamic reporting and version capture tools.

The course consists of 3 sections, 2 on basic R and 1 on reproducibility in R.  
Each section is presented as both HTMl and Rpres markdown ( to allow for intergration of the presentation in the RStudion enviroment itself).  Exercises and answer sheets are included after all subsections to practice techniques and provide future reference examples. 

Course material and exercises are available to view as rendered HTML at https://github.com/LMSBioinformatics/Reproducible-R/.  
All material is available to download under GPL v2 license.

For  information on other courses run by our team see our [github IO page](http://bioinformatics.lms.mrc.ac.uk/LMStraining.html).


## The Team
This course was created and conducted by the MRC London Institute of Medical Sciences  Bioinformatics Team at Imperial College London, Hammersmith Hospital.  
For more information on the team see our [github IO page](http://bioinformatics.lms.mrc.ac.uk/LMSpeople.html).


This course is free for MRC LMS and Imperial staff and students. 

## Setting up.


#### Install R.

R can be installed from the R-project website.  
R 3.1.0 or higher is required for this course.

http://www.r-project.org/

#### Install RStudio.

RStudio can be installed from the R-project website. 

http://www.rstudio.com/

#### Install required packages.

Having downloaded R and RStudio, some additional packages are required (rmarkdown and ggplot2).  
To install these,
* First launch RStudio
* Install the packages in the R console
<pre>
install.packages("ggplot2",dependencies=TRUE)
install.packages("rmarkdown",dependencies=TRUE)
</pre>

#### Download the material
The material can either be downloaded as a [zip](https://github.com/mrccsc/Reproducible-R/archive/master.zip)
<pre>
wget https://github.com/mrccsc/Reproducible-R/archive/master.zip ./
</pre>
or checked out from our Github repository
https://github.com/mrccsc/Reproducible-R/
