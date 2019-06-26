# Angular Js2


## Instructions

1. Make sure you have these installed
  - [node.js](http://nodejs.org/)
  - [git](http://git-scm.com/)

2. Clone this repository into your local machine using the terminal (mac) or Gitbash (PC) 

    `git clone https://github.com/coursefiles/angular2-essential-training.git`
    
3. CD to the folder

    `cd angular2-essential-training`
    
4. Run the following to install the project dependencies:

    `npm install`
    
5. Run the npm start command to build the code, watch for file changes, and serve up the site locally:

    `npm start`

The repository has a branch for each video starting point. For example, the branch **02-01b** is used as the starting code for the video *02-01 NgModule and the root module*. You can checkout branches using `git checkout -b <branchname>` and not have to re-run `npm install` each time since you will remain in the same root folder.

Note that the site will run using `lite-server` and will be served up at the following local address:  
    http://localhost:3000

*If you use a code editor that launches its own web server please note that it may run on a different port number. 
You will want to use `npm start` for this project.*

## FAQ
If you are getting a list of errors on `npm install` that look like `Cannot find name 'Promise'`, check your `package.json` file and see if the following DevDependencies have a caret in front of the version number (the ^ symbol):
```json
"devDependencies": {
  
  "@types/core-js": "0.9.34",
  "@types/node": "6.0.41"
  
}
```
If the caret is there (would look like `"@types/core-js": "^0.9.34"`) then remove it (or copy the contents of the [package.json](https://github.com/coursefiles/angular2-essential-training/blob/master/package.json) file on the origin repository) and run `npm install` again.
  
## More Stuff
Check out some of my [other courses on LinkedIn Learning](https://www.linkedin.com/learning/instructors/justin-schwartzenberger?u=2125562). 
You can also [follow me on my twitter](https://twitter.com/schwarty).
