# Lesson 1
## Guide to Embedding a Tableau Dashboard in a Jupyter Notebook
### Author: Vernon Naidoo
 
1. Start with any Tableau workbook (.twb file).
1. Save it as a Tableau Packaged Workbook (.twbx file).
1. From the Data menu, choose the name of your extract, then click "Extract Data..." and resave the file.
1. If you don't already have one, sign up for a free [Tableau Public](http://public.tableau.com) account.
1. From the Server menu in Tableau, choose Tableau Public > Save to Tableau Public.
1. If you are prompted, sign into Tableau Public.
1. Once you have the workbook open in Tableau Public, choose the share icon in the lower right corner.
1. When the Share window opens, copy the contents of the Embed Code box.
1. Open your Jupyter notebook (.ipynb file) in Google Colab.
1. Add a code cell with two lines:
    - %%HTML
    - [paste the HTML you copied from the Embed Code box on the second line]
1. Save the Jupyter notebook and execute the cell

Notes:
- It isn't possible to embed the dashboard in the readme.md file (in case you were considering that approach).
- I used a Jupyter notebook for covenience but suspect that any web page that can run javascript will work.
- The ipynb file for the notebook can be uploaded to GitHub but will appear as a code fragment when viewed directly.
- Viewing the same notebook through the Google Colab viewer will reveal the interactive dashboard.  

Link to a working example is below:

[PoC Tableau Dashboard](https://colab.research.google.com/github/VernonNaidoo-Toronto/COVID-19_Test/blob/master/Tableau_PoC.ipynb)
