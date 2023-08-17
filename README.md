# From Spark to Ignition: Establishing a Plan for Entrepreneurial Success🚀
This is the repository where you can download everything we need for the UMass Amherst Engineering Class "From Spark to Ignition, Establishing a Plan for Entrepreneurial Success"  
It also has a bunch of things I have found useful in my educational journey.  

## List of things you will find here so far:  
-  Power Point Presentations for most of the classes  
-  Example mind map as an image and "mind map" format for use with Docear, although outdated, still the best mind map software out there: https://docear.org/  
-  Template one page Business Plan  
-  Example filled out business plan 
-  Instructions on how to run a ipython notebook (sparkignite.ipynb)  

## Instructions on how to set up a good developer environment 
##### (you may or may not be using this in this class, it is just very useful to have handy - it is basically a really powerful calculator)  
### Setting things up  
Install Visual Studio Code: https://code.visualstudio.com/#alt-downloads  
Install git: https://git-scm.com/download/win  

In GitHub.com, click on the green "<> Code" button and choose "Download Zip"

-  Then open VS Code and go File👉Preferences👉Profiles👉Import Profile  
- In the upper center of the screen, a dropdown select menu will appear.  
-  Choose "Select File".  
-  Navigate to folder that has all the files from this GitHub repository and choose the file: `for_spark.code-profile`  
-  On the left-hand sidebar, click: "Create Profile"  


### Once you have installed VS Code and git...

-  Press Ctrl+Shift+\` or Cmd+Shift+\`. The \` button is the one to the left of the 1 key
This will open a terminal window  
-  Then copy and paste into the terminal  
`./micromamba.exe shell hook -s powershell | Out-String | Invoke-Expression`  
This will activate Micro Mamba, a self-contained python environment  
-  Then run:  
`micromamba create -f environment.yml`  
This will install most of the necessary libraries.  
-  Then run  
`micromamba activate car `  
This will activate the newly created development environment  
-  There are a few libraries that can't be installed using the `micromamba` command, for these, you need to use pip, the "Python Package Index"    
There is a file called `pip.sh`.  Open that and copy its contents and past it into the terminal.  Once it is done, you should be all set!  

-  Now you need to make some changes to the VS Code `settings.json` file in the `.vscode` folder so that the application knows where to find python.

#### You should be good to go, although you may need to restart VS Code to have everything be up to date.  Let me know if you have trouble  
