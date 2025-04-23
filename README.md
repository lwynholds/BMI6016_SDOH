# BMI6016_SDOH

Group project for BMI 6016, Spring 2025

University of Utah, Department of Bioinformatics

## ToC: 

### About The Project 

The concept of Social Determinants of Health (SDOH) has been widely recognized in health research, following the early efforts by the World Health Organization (WHO) to contextualize systemic and population-level health disparities worldwide. In the United States, SDOH are central to public health and policy, and as such, are measured, tracked, and studied in detail by the Centers for Disease Control and Prevention (CDC) in cooperation with other organizations that conduct national survey data, such as Health and Human Services (HHS), the US Census and their American Community Survey (ACS), the Agency for Healthcare Research and Quality (AHRQ), and the National Institutes of Health (NIH). A substantial portion of SDOH data is derived from national surveys, census records, and geographic datasets, providing valuable insights into social and environmental conditions that impact health outcomes. However, integrating these diverse data sources into actionable tools for clinical and public health applications remains a significant challenge. 
 
In 2018, Cantor et al. published their Factors Affecting Communities and Enabling Targeted Services (FACETS) model, with open-data architecture and designed for New York City, to standardize and compile SDOH-related data at the census-tract level.(Cantor et al., 2018) FACETS facilitates the integration of community-level SDOH with patient health records, enhancing decision-making between providers and patients in care planning.  

Building on this approach, this current project developed a model tailored to the state of Utah, based on the FACETS framework, with special focus on air quality as a primary exposure. By integrating state-specific SDOH data, including environmental data, into a standardized framework, this initiative aims to provide a comprehensive tool for assessing community-level health determinants, ultimately supporting more informed public health interventions and clinical decision-making. 

[More](https://github.com/lwynholds/BMI6016_SDOH/blob/main/Group_4_Project_proposal.pdf)

### Getting Started 

#### Prerequisites
The datasets of this repository are compiled from publicly available data sourced from the CDC, ACS (Census), EPA, and others. The specific sources and variables are described in the spreadsheet, [Variable Sources](https://github.com/lwynholds/BMI6016_SDOH/blob/main/Final%20Deliverable/Group4%20Variable%20Summary.xlsx). The datasets were downloaded as their original source files, converted to CSVs, and manipulated using Python and related Python libraries as documented in the Jupyter notebooks.  The following software elements are required to reproduce and/or work with the dataset: 

Python:
[Python Libraries needed](https://github.com/lwynholds/BMI6016_SDOH/blob/main/Final%20Deliverable/Python_Libraries_Used)


Jupyter notebooks:
1. [Group4.ipynb](https://github.com/lwynholds/BMI6016_SDOH/blob/main/Final%20Deliverable/Group4.ipynb)

2. [Exploratory_data_analysis.ipynb](https://github.com/lwynholds/BMI6016_SDOH/blob/main/Final%20Deliverable/Exploratory_data_analysis.ipynb)

#### Installation 

1. Overview:
   Download all the files in the GitHub repository to your local machine, keeping the original directory structure.  The project files are in the [Final Deliverable](https://github.com/lwynholds/BMI6016_SDOH/tree/main/Final%20Deliverable) folder.
   
2. Download the files >25 MB, which are too large to host on GitHub, from this Box link: 
[Instructions for Downloading Large Files](https://github.com/lwynholds/BMI6016_SDOH/blob/main/Final%20Deliverable/Data%20Files/z%20To%20retrieve%20large%20data%20files%2C%20DO%20THIS.md)

 *Note: These files need to be placed with the other, smaller files in the 'Final Deliverable/Data Files/' folder on your local machine.*  

3. Instructions for Running the Jupyter Notebooks:
[Instructions for Running Notebooks](https://github.com/lwynholds/BMI6016_SDOH/blob/main/Final%20Deliverable/Assembly_instructions.md)

 *Note: Running the Jupyter Notebooks will recreate certain csv files that have also been included in the data directory (for reproducibility and extensibility purposes).* 

### Usage  

#### Data quality 
- Jupyter notebook:
  [Exploratory_data_analysis.ipynb](https://github.com/lwynholds/BMI6016_SDOH/blob/main/Final%20Deliverable/Exploratory_data_analysis.ipynb)
- Sample graphs:
  [Presentation of Project](https://github.com/lwynholds/BMI6016_SDOH/blob/main/Group%204%20Final%20Slides.pdf)

### Data Files 

#### Dataset Metadata 

**File Types**
- Jupyter Notebooks (code)
- CSV tables (data)
- pdf documents (documentation)
- XLSX spreadsheets (documentation and data)
- GIS files (map files)

**Source and Reference Materials:**
- [Github Folder](https://github.com/lwynholds/BMI6016_SDOH/tree/main/Source%20and%20Reference%20Material)
- [Variables Description](https://github.com/lwynholds/BMI6016_SDOH/blob/main/Final%20Deliverable/Group4%20Variable%20Summary.xlsx)

**Course Presentation Materials:**
- [Project Proposal](https://github.com/lwynholds/BMI6016_SDOH/blob/main/Group_4_Project_proposal.pdf)
- [Presentation of Project](https://github.com/lwynholds/BMI6016_SDOH/blob/main/Group%204%20Final%20Slides.pdf)

#### File Organization
Instructions for downloading the files and running the Jupyter notebooks can be found here:
[Downloading and Running the Notebooks](https://github.com/lwynholds/BMI6016_SDOH/blob/main/Final%20Deliverable/Assembly_instructions.md)

#### Sources and Variables
A complete list of variable names, sources and descriptive information can be found here:
[Variable Summary.xlsx](https://github.com/lwynholds/BMI6016_SDOH/blob/main/Final%20Deliverable/Group4%20Variable%20Summary.xlsx)

### License 
CC-BY

### Contact 
@lwynholds

### Acknowledgments 
Thanks to the instructors and everyone at the University of Utah's Biomedical Informatics Data Wrangling Course for enabling this project and providing feedback on it.
