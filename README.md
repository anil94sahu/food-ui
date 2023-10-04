npm install gh-pages --save-dev

Add in package.json file : 

homepage : github repository name

"predeploy": "npm run build",
"deploy": "gh-pages -d build",

npm run deploy