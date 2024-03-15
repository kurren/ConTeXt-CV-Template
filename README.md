# ConTeXt-CV-Template
ConTeXt CV Template. This repository hosts a customizable ConTeXt (a dialect derive from TeX, like LaTeX) template designed to create visually appealing and structured CVs.

## Structure
The files with the suffix *tex* are the one you should edit to modify the file; basically, this is what they are doing:

- **cv_template** is the main project file, it defines the structure of the all thing, listing the files needed to produce the final output. You shouldn't need to edit this file, unless you change the name of any of the other files, should that be the case, you should reflect those changes here.
- **cv_layout** is where you define the style and formatting of the output document, things such as typography styles (font family, line hieght, colours) and page layout (including columns). You should edit this file if you want to change pages layout, the font, or the colours.
- **cv_structure** is where you actually define the structure of the document (as opposed to the above mentioned *cv_template* where the structure of the project is defined). You should edit this document if you change the sections naming, or sections order of the ouptut document.

Then you have the actual content, these are the sections where you should write the content you wanto to end up in the output document. You can find those section in the *content* folder: the sections are:

- **header**
- **intro**
- **domains**
- **positions**
- **clients**

The CV length depends on how much stuff you'd like to put in. I'm happy with mine being three pages long. The following screenshots are those three pages from my current CV.

!APB CV Page 1(https://github.com/kurren/ConTeXt-CV-Template/blob/master/page_1.png?raw=true)
!APB CV Page 1(https://github.com/kurren/ConTeXt-CV-Template/blob/master/page_2.png?raw=true)
!APB CV Page 1(https://github.com/kurren/ConTeXt-CV-Template/blob/master/page_3.png?raw=true)


You can find more about *ConTeXt* at the Wiki ConTeXt Garden https://wiki.contextgarden.net/Main_Page
You can find an exmaple of the output (cv_template.pdf) with *Lorem Ipsum* text, as well as my own cv formatted with this template: *apianabianco_cv.pdf*




a.
