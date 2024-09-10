# Scripts
### Script 1 - file_format_lefse.ipynb
In the first script I did a bit of data manipulation, to change the format of my data to the one that could have suited the Lefse Galaxy tool, which have to respect the *following requisites*:
<br>
<br>
The text tab-delimited input file consists of a list of numerical features, the class vector and optionally the subclass and subject vectors. The features can be read counts directly or abundance floating-point values more generally, and the first field is the name of the feature. Class, subclass and subject vectors have a name (the first field) and a list of non-numerical strings.
Although both column and row feature organization is accepted, given the high-dimensional nature of metagenomic data, the listing of the features in rows is preferred.

![immagine](https://github.com/user-attachments/assets/7946241d-9e52-44ca-956c-d45204db0b2a)

### Script 2 - relative_abundance_phylum.ipynb

This second script contains the code for analyzing microbial communities in skin affected by Atopic Dermatitis (AD). The scripts read microbial count data at the Phylum level from Excel files for lesioned skin (LE), non-lesioned skin (NL), and healthy skin (HS), consolidate it, and calculate relative abundances.

The function `concat_excel_files(folder_path)` merges all Excel files from a specified directory into a single DataFrame, standardizing counts to derive relative abundances. The script then computes and visualizes these abundances across the different skin conditions using stacked bar charts, highlighting differences in microbial profiles. The analysis helps understand how microbial landscapes vary across affected and unaffected skin, potentially informing AD pathogenesis and treatment strategies.
![immagine](https://github.com/user-attachments/assets/d6c14f29-5e86-4b72-acd2-bbaaed1318fb)


