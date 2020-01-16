# Lab Markdown Template

>This is a basic RMD template for a lab notebook style entry. 

# Overview 

This is a custom R Markdown template that can be used for lab notebook styled reports. It is currently personalized to me (Alex Beaver), but can easily be altered for anyone's information. 

# Usage 

* I have not figured out how to make this into an easy to install R package yet.

* Download the files /inst/rmarkdown/templates/LabtemplateAB/
    * This is the file structure you need to create the template. 
* Create a new directory at ~/user named after your template. Somthing like "basictemplateAB" works. 
* Open Rstudio. Create a new project -> existing directory -> select the directory you created. Name the project the same name as the directory 
* Drop your inst file into the new project directory you created. 
* In the console of Rstudio:

```{r}
install.packages("devtools")
library(devtools)
devtools::install("Nameofyourtemplatedirectory")
```
* If this doesn't work you can read more about how creating templates works [here](https://chester.rbind.io/ecots2k16/template_pkg/). You can use the skeleton.rmd in  this repo as a backbone for creating your own template. 

* Now, you can open a new RMD file : New File ->R Markdwon -> From Template -> Yourtemplatename

# Personalize 

* You need to open the footer.html file in a text editor. Change the links and email in the text to your own information. Save the document. 