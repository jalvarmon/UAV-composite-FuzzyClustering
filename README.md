# Fuzzy unsupervised-learning techniques for diagnosis in a composite UAV wing by using fiber optic sensors

## Abstract
Pattern recognition, which aims to associate data with a condition of a structure, has been applied successfully in Structural Health Monitoring (SHM) for damage diagnosis. Such association becomes more complex when applied to strain data measured from aerospace structures where the operational conditions produce changes in the strain patterns that are not related to a damage occurrence. Moreover, a damage occurrence only produces subtle changes in such patterns. That is why novelty detection strategies based on unsupervised learning have not demonstrated suitable results for strain-based SHMin operating aerospace structures. For example, imagine that it is possible to have data from all the different operational conditions for an aerostructure and, therefore, construct a model (e.g. statistical) from these data. Such model may be too general and some data from damage conditions may fit into the model and, subsequently, classified as a normal condition. One successfully-proved approach is to
use unsupervised-learning, density-based classification to create clusters according to the operational condition and, then, build models for each specific cluster. In previous works, the authors implemented such methodology in an aluminum beam under simulated environmental conditions and subsequently, in the wing’s main beam of an Unmanned Aerial Vehicle (UAV) made of composites. The results for the metallic structure demonstrated a good performance since the changes in the patterns due to the
operational condition variations were clear and identifiable. On the other hand, the data acquired from the UAV demonstrated to be fuzzy and without clear transitions among clusters. The aim of this work is to explore fuzzy clustering techniques in order to improve the global performance of the methodology for composite aerospace structures, which exhibit high stiffness. Fuzzy C-Means (FCM) and GustafsonKessel (GK) algorithms were tested using the UAV flight data and their performance was evaluated through Receiver Operating Characteristic (ROC) analysis

## Reference
To use this template for your research, fork this repository, change the name
to something descriptive for your project, and adjust the licensing as you
see fit.

To use this repository for your own research, simply clone the repo using the following:

```
git clone https://github.com/gchure/reproducible_research your_repo_title
```

> :warning: :warning: :warning: I wouldn't advise forking this repository. As you can only fork a given repository once, there is little utility in forking this repo if you hope to use it again in your future projects :warning: :warning: :warning:

## Layout

The repository is split into seven main directories, many of which have subdirectories. This structure has been designed to be easily navigable by humans and computers alike, allowing for rapid location of specific files and instructions. Within each directory is a `README.md` file which summarizes the purpose of that directory as well as some examples where necessary. This structure may not be perfect for your intended us and may need to be modified. Each section is briefly described below. 

### **`code`** 
Where all of the *executed* code lives. This includes pipelines, scripts, and figure files. 
 * **`processing`**: Any code used to *transform* the data into another type should live here. This can include everything from parsing of text data, image segmentation/filtering, or simulations.
 * **`analysis`**: Any code to to *draw conclusions* from an experiment or data set. This may include regression, dimensionality reduction, or calculation of various quantities.
 * **`exploratory`**: A sandbox where you keep a record of your different approaches to transformation, interpretation, cleaning, or generation of data.
 * **`figures`**: Any code used to generate figures for your finished work, presentations, or for any other use.

### **`data`** 
All raw data collected from your experiments as well as copies of the transformed data from your processing code. 

### **`miscellaneous`** 
Files that may not be code, but are important for reproducibility of your findings.
* **`protocols`**: A well annotated and general description of your experiments. These protocols should be descriptive enough for someone to follow your experiments independently 
* **`materials`**: Information regarding the materials used in your experiments or data generation. This could include manufacturer information, records of purity, and/or lot and catalog numbers.
* **`software details`**: Information about your computational environment that are necessary for others to execute your code. This includes details about your operating system, software version and required packages.

### **`tests`** 
All test suites for your code. *Any custom code you've written should be thoroughly and adequately tested to make sure you know how it is working.*

### **`software_module`** 
Custom code you've written that is *not* executed directly, but is called from files in the `code` directory. If you've written your code in Python, for example, this can be the root folder for your custom software module or simply house a file with all of your functions. 

### **`templates`** 
Files that serve as blank templates that document the procedures taken for each experiment, simulation, or analysis routine. 

### Required Files
There are some files which I consider to be mandatory for any project.

1. **`LICENSE`**: A legal protection of your work. *It is important to think deeply about the licensing of your work, and is not a decision to be made lightly. See [this useful site](https://choosealicense.com/) for more information about licensing and choosing the correct license for your project.*

2. **`README.md`**: A descriptive yet succinct description of your research project and information regarding the structure outlined below.


# License Information

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="github.com/gchure/reproducible_research">
    <span property="dct:title">Griffin Chure</span></a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">A template for using git as a platform for reproducible scientific research</span>.
This work is published from:
<span property="vcard:Country" datatype="dct:ISO3166"
      content="US" about="github.com/gchure/reproducible_research">
  United States</span>.
</p>
