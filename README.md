# Sass_Workflow

<strong> Type 'npm install' to install dependencies. </strong>

#

Note: "sass": "node-sass -w scss/ -o dist/css/ --recursive"

<strong>Type 'npm run sass' to run script</strong>

  - This script will watch all changes in the scss folder. Sass code will be compiled to css code. The output will create a css file in the dist folder.

#

Note: "deploy": "gh-pages -d dist"

<strong>Type 'npm run deploy' to run script</strong>

  - This script will make dist folder the directory that will be deployed for github pages.
  
  - <strong>IMPORTANT</strong> : add <em>"homepage": "https://url.github.io/example/",</em> in between "main": "index.js", and "scripts": {
  
    - Replace "https://url.github.io/example/" with your desired url. 
    
#

Upload and Update gh-pages
  1) run git add .
  2) run git commit -m ""
  3) run git push 
  4) run npm run deploy
