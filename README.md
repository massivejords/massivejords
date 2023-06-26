## Hi, I'm Jordan! Check out some of my projects below!

### A. thaliana leaf area detection in OpenCV and PlantCV
I developed a computer vision algorithm using Python to automatically quantify the size leaves grown on agar plates. Below is [figure 2 from our paper](https://pubmed.ncbi.nlm.nih.gov/36518946/) showing the leaf area detection steps.

![Demo leaf area image](https://user-images.githubusercontent.com/72272198/235205383-44b73a77-794c-4455-9eda-a535eeef7117.png)

*The image-processing steps used for leaf identification. (A) Image converted to black and white using the B channel of the Lab color space. (B) Binary threshold. (C) Region of interest indicated by the blue lines. (D) Identification of individual shoots using clustering and splitting the image into six sections. Note that one seed failed to germinate so no leaf area was measured.*

#### [Check out the resulting publication in Application in Plant Sciences!](https://bsapubs.onlinelibrary.wiley.com/doi/10.1002/aps3.11504)

The software was actually used to collect leaf area for thousands of leaves in [Katz et al 2022](https://pubmed.ncbi.nlm.nih.gov/36130068/) as well!

[Look at the code repository here](https://github.com/massivejords/Agar-plate-leaf-area)

### At the Staller Lab, I am developing a Python package
While still a work in progress, this package contains code relevant to analyzing the NGS data output from our Fluorescence Activated Cell Sorting assays as well as some simple tile design functions.

[Shared code in a Python Package for collaborators](https://github.com/massivejords/tools)

### Additionally, check out some examples of charts and graphs
While these are all examples with fake data, they demonstrate some of the visualizations I can do completely in seaborn and matplotlib. 

![Graph with colorbars](https://github.com/massivejords/massivejords/raw/main/misc_1.png)
![Graph with legend and tile bars](https://github.com/massivejords/massivejords/raw/main/misc_3.png)
![Graph with sequences](https://github.com/massivejords/massivejords/raw/main/misc_4.png)

