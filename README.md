# Binary-Compound-Data-Collector-RPA

HEY! I REALLY RECOMEND THAT YOU READ THIS!

Welcome to the Data Extractor and Data Visulization program, made with Python and data from Materials Project plataform. I beg you to read this brief introduction text to favour your complete understanding of this program operation to allow you making better use of it. My wish is that this repository helps students and teacher of all universities in the world to obtain many data of binary compounds and saving them locally in an Excel file.

This project is subdivided into two principal scripts:

## 1. Data Extractor

### 0. Presets

After running this script you shoud specify the chemical elements combination list that will be combined with yours chemical element choice. After that in the Menu you will be asked to choice the chemical element that will be combinated with the list, but I will explain better in the next item, lets go!

### 1.1 Initial Menu and API Extraction

#### Menu
At the beginning you must specify the chemical element that you want combine with the preset element list. Think for example in the case below, the choice element is aluminum (AL). Besides that the element list contain all the transition metals in the periodic table, excluding the most exotic ones (the last line, after Lanthanum).

With that the scrip combine an create a data base with all the binary compounds between the aluminum and the transition_metals inside the elements list.

#### API

The API was crucial to obtain the information about all the materials in the combination list. Mainly elastic properties data of the microstructure of the compounds. Besides that the program gets the formation energy of that cristalografic structure, using the API to pick all the other missing information.

With the exception of the AI_ML predicts of K_VRH and G_VRH and the Decomposes-To data, but the explanation of this choice is explained breafly next. 

### 1.2 Web Scraping

Scraping path to obtain the AI-ML predicts of K-VRH and G-VRH and also the Decomposes-To are better... For the Decomposes-To data it provides a better visualziation of the chemical products after the chemical decomposition. The AI-ML predicts of K-VRH and G-VRH only could be obtained using the Web Interface plataform of the Materials Project plataform/site. 

Observation: Looking to obtain that information, it was necessary to login in the website to be allowed to see the physical computer calculation of that two elastic parameters or properties of the studied compound.

## 2. Data Visulizator

In the elaboration of this second script, I am very grateful to my teacher, that gave me an initial template that printed the graphs of all the 30 compounds.
"An images can explain better than a thousand words" so lets look an example:



With the Data Extractor file you can extract all binary compound material data that you wish. You just need to insert the quimi
