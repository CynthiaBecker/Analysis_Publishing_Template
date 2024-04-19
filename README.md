# Analysis_Publishing_Template

This repository provides an example of how to organize an R Markdown document in preparation for making your data analysis code open access on GitHub. Some guidelines when setting up the repository or folder:   
* Create a folder for data. For example [./data/](https://github.com/CynthiaBecker/Analysis_Publishing_Template/tree/main/data)
* Create a folder for figure output. For example [./figures/](https://github.com/CynthiaBecker/Analysis_Publishing_Template/tree/main/figures)

Navigate to the [Template_Data_Analysis_Publishing.Rmd](https://github.com/CynthiaBecker/Analysis_Publishing_Template/blob/main/Template_Data_Analysis_Publishing.Rmd) document and download it for an example template. There is a download icon in the top right that should work for downloading the file.      
1. Download the file
2. Adjust the file path to your repo/folder of interest
3. Adjust/edit the code as needed!

When it comes time to publish your code publicly, `knit` the R markdown document, and it will generate both an `*.html` and an `*.md` file. It will also populate figures in your `./figures/` folder.      

Use `git add` and `git commit -m "your message here"` to add all the figures and `.md` document to the github repo. When you finally `git push` the content to your repo, you will have a nice document that includes both code and figures, as seen [Here in this .md document](https://github.com/CynthiaBecker/Analysis_Publishing_Template/blob/main/Template_Data_Analysis_Publishing.md)
