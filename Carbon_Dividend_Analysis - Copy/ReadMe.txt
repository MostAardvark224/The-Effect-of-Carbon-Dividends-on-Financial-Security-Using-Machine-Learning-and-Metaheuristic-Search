
The "Code" folder contains 
	
- FSRI_Construction
- Survey Data Cleaning
- Dividend Data Analysis 

The "FSRI_Construction" file contains all of the code that was used to create the FSRI, train the machine learning models, and run the genetic algorithm. It's the main file that most people would probably want to access. Execute this file to reproduce the allocation results. Note that it does take a substantial amount of time to complete.

The "Survey Data Cleaning" file imports the SHED survey and cleans it so that I'm only working with the elements that I need. If you wanted to access the entire SHED survey and pick and choose what to include that's the file for you. 

The "Dividend Data Analysis" file just contains some simple statistics and analysis I did comparing both scenarios.

--------------------------------------------------------------------------------------------------------------------------------------------

The "Data" folder contains

- Two SHED surveys (The original and the cleaned version)
- Dividend_Data
- Stata Files and Data (available upon request)

The two SHED surveys were used for the training of the machine learning models and the creation of the FSRI.

The Dividend_Data file contains all of the final results from both the equal dividends scenario as well as the GA's scenario.

The Stata Files and Data folder were adapted from Anders Fremstad and Mark Paul's "The Impact of a Carbon Tax on Inequality". This folder contains all of the files I used from them, as well as the files that were originally theirs which I altered to reflect updates in the economy. These files are used to generate the carbon tax burden. 

*** This folder is not currently uploaded in GitHub. If you would like the Stata files and data, please send me an email (amaybabel@gmail.com) and I'd be happy to send the files over. I didn't upload these files on GitHub because there were too many files and the folder took up to much space.