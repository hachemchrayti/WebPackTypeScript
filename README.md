Step 1: tsc --init to initialize a tsconfig.josn file 
then change     "target" to  "es6" and   "module" to "es2015"

Step 2 : npm init to create package.json file 


Step 3: install webpack and its cli and loader via ths command : (-D pour dire devDependencies)
 npm install webpack webpack-cli ts-loader -D
 
 Step 4 : install typescript locally to add it to the devDependancies (even if it installed globally in your machine we have to install it 
 in the npm dependencies ) via the command : 
 npm install typescript -D
 
to run on dev mode : npm run server
to run build mode : npm run build 


