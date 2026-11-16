# Draft \#1

A compressed R Project folder (.zip) that contains the following:

1. `data/`
    - A folder where all of your data files live. 
    - There should be two folders inside of this one: `raw/` and `processed/`
    - `raw/`
        - Place the original, unedited, "raw" data file(s) in here 
    - `processed/`
        - Where you will save the processed, cleaned data file(s) you create in `01_eda.qmd` below.
1. `01_eda.qmd`
    - A Quarto document containing your exploratory data analysis (EDA).
    - Should contain your code for reading in and processing your raw data files. 
        - If this step takes a long time to run, you can move this code into a separate QMD or R script file that you only run once (this will be what I ultimately ask you to do anyways).
    - **Make sure you save the resulting processed data file(s)** as either a CSV or an RDS object in the `data/processed/` folder.
    - I am purposely leaving what you should do in this section open. *Your goal is to get to know your data better.* Explore what the columns mean. Make plots. Create summary tables. If applicable, create new columns.
    - Do you want to revise any of your research questions? If yes, write out your new, edited questions in this document.
    - **Make sure you include written narrative!** Your document should not just be code. If you were to show your EDA to a peer, they should be able to follow what you are doing by just read your code and narrative.
    - **DO NOT MAKE ANY MODELS YET.** Leave this for the Draft \#2.
1.  `01_eda.html`
    - Rendered html version of `01_eda.qmd`
    - Make sure to include the html document option `embed-resources: true` in your YAML header so there is not an accompanying `*_files` folder.
1.  **All other files inside of your project folder, such as the actual `.Rproj` file**

