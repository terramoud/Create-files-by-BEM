# Create-files-by-BEM
This is Node.js utility for create the files in BEM style naming (react.js style) and writing of prepared code into them and adding paths to them in of the main project files (index.scss or index.js)

How Use. 
In terminal enter:
  node cbem.js index PayButton-Arrow_text_bold
  
index this is entry points of your app. In this case it is index.pug index.js and index.scss into them will be adding paths to created files (include, @import and require()). 

In this case PayButton-Arrow_text_bold shall be:
PayButton - this is folder (block by BEM)  
  PayButton.pug
  PayButton.js
  PayButton.scss
  
  -Arrow this is folder too (element by BEM)  
    PayButton-Arrow.pug
    PayButton-Arrow.js
    PayButton-Arrow.scss
    
    _text is folder too (modifier by BEM)  
      PayButton-Arrow_color_bold.js
      PayButton-Arrow_color_bold.scss
      
This is wiil be created after send command in terminal
Paths can change in cbem.js file.
For more details please considered source code from cbem.js
