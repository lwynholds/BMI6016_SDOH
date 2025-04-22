# Instructions for Downloading Files/Assembling Data Folders for Jupyter Notebooks

**You must first compile data sources before running the Python code.** 

1. Download the GitHub Repository to your local machine. PRESERVE THE DIRECTORY STRUCTURE.

2. Go to https://uofu.box.com/v/LWYNHOLDS-BMI6016-SDOH-LG-DF to retrieve the big files: sdoh_2020_tract_1_0.xlsx, 2020_UA_BLOCKS.txt, Region8_CancerRisk_by_block_poll.xlsx, and unzipped annual_conc_by_monitor_2020.csv. Paste them into the Data Files folder with the smaller data files.
   
- If you want to check source authenticity, you can go to each Data Source listed URL in the [Group4 Variable Summary table](https://github.com/lwynholds/BMI6016_SDOH/blob/main/Final%20Deliverable/Group4%20Variable%20Summary.xlsx ) and re-download the sources from there. 

3. Once all data files are in your local Data Files folder, open the ["Group4" Jupyter notebook](https://github.com/lwynholds/BMI6016_SDOH/blob/main/Final%20Deliverable/Group4.ipynb ) and begin running code. 

4. Run the cells in order through "Making one flat CSV (to join on Tract ID)"

5. In doing this, you will regenerate a set of CSVs, which will appear in "Data Files/CSV for SQL." You may load these into SQL or Python for querying. 

6. This will also regenerate a much larger, combined CSV file called "one_df_to_rule_them_all.csv," which will appear in the Data Files folder. You may also use this single file for querying in SQL or Python, but if you try to open it with Excel or a similar spreadsheet program, some data will be lost. Keep it closed and query with an appropriate language. 

-  At this point, the data can be used two ways: We have an additional Jupyter notebook to perform a data quality assessment of the large "one_df_to_rule_them_all.csv" file. To do this, leave the ["Group4"](https://github.com/lwynholds/BMI6016_SDOH/blob/main/Final%20Deliverable/Group4.ipynb ) notebook and open the ["Exploratory_Data_Analysis"](https://github.com/lwynholds/BMI6016_SDOH/blob/main/Final%20Deliverable/Exploratory_data_analysis.ipynb) notebook to evaluate the data quality. Leave all other files and folders untouched. 

7. Proceeding with the rest of the code will produce heatmaps illustrating the different data layers. 

8. When you reach the section labeled 'TO USE' in ["Group4"](https://github.com/lwynholds/BMI6016_SDOH/blob/main/Final%20Deliverable/Group4.ipynb ) notebook, follow Steps 1, 2, and 3 to plot an address of interest with layers of interest on one heatmap. 
