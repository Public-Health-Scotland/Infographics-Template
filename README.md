# Infographics Template
A template anyone can use to help develop their own automated Infographics using R

# How to Produce Infographics in HTML using RMarkdown

## Download the Necessary Files
* To download the necessary files, click on *Clone or download -> Download ZIP* and save it to the folder of your choice. 
![Download Zip Example](https://github.com/NHS-NSS-transforming-publications/Images/blob/master/RMarkdown_Basic1.png)
* Go to the zip file and unzip it (e.g. If you have WinZip, right click on it and choose *WinZip -> Extract to here*).
* You should see the four files that are below.
![Infographics_Files](https://github.com/NHS-NSS-transforming-publications/Images/blob/master/Infographics_Files.PNG)
  * The Template.RMD is the main RMarkdown file that we are interested in.  When run/knit in RMarkdown this file
    will create the final HTML infographics output file named Template.html.
  * The README.md is simply this instruction file and can be ignored.
  * The Template_using_ggpubr.R is an alternative way to create basic infographics in an easier to use way using only R package ggpubr without RMarkdown.
  * The blue_pill_icon.PNG file is an image file that Template.RMD references and shows in the HTML output.  This image file is used to represent any image file that is referenced from an external source instead of being generated by R itself.

## Run/Knit the Template File
![Knit document example](https://github.com/NHS-NSS-transforming-publications/Images/blob/master/Infographics_Knit.PNG)

* Open the HTML document (Template.html) that was just created. Now you have your Infographics HTML file!


# How to Produce Infographics using ggpubr

This is an alternative way to create the infographics template using ggpubr package. The advantage of doing this is that no HTML code is needed. Also there is no need to set parameters for spaces and paddings.

* Open "Template_using_ggpubr.R" and run the script. It will produce a plot with four pie charts aligned and some text description next to each of them. 
* You can save the final output by clicking on Export -> Save as PDF. Choose "Landscape" for orientation and give it a file name.
