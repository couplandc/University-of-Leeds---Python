This ibynb file was produced to forefill the need to create one non spatial visualisation and one spatial visualisation, the topic covered was to display the impact the distance from postcodes to primary roads has on the number of burglary's in that area. 
The study area chosen consists of Leeds, Bradford, Sheffield and Hull. The code aims to visualise both graphically and spatially, supported by statisticaly analysis using spearmans correlation, in order to see the impact distance has on the number of burglarys 
in and around the urban areas with excellent highway access.

Each code cell has appropriate comments next to it for explaination and each section has markdown cells explaining and justifiying the choices made in the coding and final product.
The outputs are procuded using colour friendly palettes and formatting for the intended audiences i.e the Police and crime data analysts.

Some of the data was preprocessed in QGIS before processing in python in order to reduce file size and optimise the python coding beforehand, as this ipynb was made in Google Colab where files have to be uploaded.
This file follows basic readibility and logical flow where it is seperated into 3 stages; Data processing, Data cleaning, Data visualisation.


Contents; 
cleaned_data file containing all data to be uploaded to google colab before running the code.
  - Census_merged
  - Crimes Merged
  - Major roads
  - Output areas
  - Primary road start points
Ive have also included a seperate Report word document containing all the text and references used in the markdown cells within the ipynb as a seperate viewing method as it can be a bit difficult to see in the ipynb file and if you wanted to read it seperatly.

All data used is open source and has been referenced in the ipynb and report file so you are able to easily find and download new updated data when it becomes avalible to be able to see differences between years.

