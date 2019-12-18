# IUPAC-project
Source code for IUPAC project

This repository contains the data of raw mass lists, assigned mass lists and jupyter notebooks which were used for data analysis

1. Data:

    a) In the folder 'mass-lists' in the appropriate folder for each of the 5 laboratories (a-e) are the following files in '*.csv' format with separator sep=',': "CHA.csv", "SFA-Ctk.csv", "SFA-PW.csv", "SHA-Ctk.csv", "SHA-Pw.csv" и "SRHA.csv"

    b) For each of the 5 laboratories, there are 6 assigned mass-lists in the format '*.csv' with the separator sep='\ t' in the folder 'data'

    c) For each of 9 laboratories, there is an assigned mass-list in the format '*.csv' with the separator sep='\ t' in the folder 'All-SRFA-Formulae'

    d) Files 'data.csv' and 'SRFA.csv' - are combined table from files in folders 'data' and 'All-SRFA-Formulae' in the format '*.csv' with the separator sep='\ t'

2. Source code:

    а) 'Analytics.ipynb' - Jupyter Notebook that was used for primary data analysis

    b) 'For article.ipynb' - The notebook that was used for generating figures for the article partially combines all the others Notebooks

    c) 'MassSpectrum.ipynb' - Notebook that was used for generating Mass Spectrum Figure

    d) 'Models-2.ipynb' - 'Models-5.ipynb' - Results of notebooks are not included in the article. The idea was is it possible to predict presence or absence mass peaks in one spectrum by using information about others. Numbers (2-5) are connected with a definition of 'common' formulae, for example, we can suppose that formulae are common if its presence at least in 2 out of 5 different spectra

    e) 'Table Generator.ipynb' and 'Table Generator-SRFA.ipynb' - are used for generating one common table for all data (separately for SRFA and other data)

    f) 'Van Krevelen.ipynb' and 'Van Krevelen (SRFA).ipynb' - are used for generating Van Krevelens (separately for SRFA and other data)

3. Figures

    Figures that were generated for the article are placed in folder 'Figures'