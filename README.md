# Gulp Frontend
Gulp frontend workflow using Coffeescript, Sass, Neat, &amp; Bourbon  
  
## Getting Started
Install npm modules with ```npm install```  
  
Next install bower components with ```bower install```  
  
Use ```npm install -g bower``` if bower is not already installed  
  
Work on files in the **src** folder, compiled code goes to a folder named **dist**

```
git clone https://github.com/rongierlach/gulp-frontend.git
cd gulp-frontend/
npm install -g gulp
npm install -g bower
npm install
bower install
gulp
```

## Running Gulp
Run ```gulp``` to get working  

Clean out the **dist** folder with ```gulp clean```  

To just build run ```gulp build```  

Optionally you may pass a production flag with ```gulp build --production``` to minify scripts
