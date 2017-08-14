# react-wood-duck

The react-wood-duck is a shared pattern library hosting re-usable components and styles to be used across all CWDS-NS digital services development teams.
Contribution and Integration of this pattern library by digital services results in reducing coding efforts for all developers.
## Table Of Contents

* [react-wood-duck](#react-wood-duck)
* [Table of contents](#table-of-contents)
* [List of Components](#list-of-components)
* [Installation](#installation)
* [Usage](#usage)
* [Developmemt](#development)
* [Contributing](#contributing)
	* [Add and Modify the Components](#add-and-modify-the-components)
	* [Push to git](#push-to-git)
	* [Versioning](#versioning)
	* [Publish to NPM](#publish-to-npm)
	* [Documentation](#documentation)


## List of components

see the wiki 

## Installation

using npm,

	npm install react-wood-duck --save

for specific version 

	npm install react-wood-duck@version
  
## Usage

Now, you can import the components from the library into the application as,

	@import { component name } from 'react-wood-duck'
 
   For example, using component from library(react-wood-duck) in the application app/javascripts/components/hello_react.jsx  
   
   <img alt="Syntax highlighted styled component" src="https://user-images.githubusercontent.com/30934662/29230515-456a29cc-7e98-11e7-9fb4-2b1a34a98a55.png" height="300px" />
  
## Development 
###### (src, dist and the build process)

NOTE: The source code for the component is in src. A transpiled CommonJS version (generated with Babel) is available in dist for use with node.js and webpack.A UMD bundle is also built to dist, which can be included without the need for any build system.


## Contributing
Contribution and Integration of this pattern library by digital services results in reducing coding efforts for all developers.
See the [contributing guidlines]() for details on our code of conduct,
You can contribute by adding new components and by modifying excisting components and styles.

### Add and Modify the Components

Clone the repository from git

	git clone link

Create or modify the react components in react-wood-duck/src.

	npm run prepublish
	
when you run this, it compiles the "src" code and generates the transpiled CommonJS in “dist” folder within your local machine 
        
### Push to git

Commit the changes and push to GitHub
        
	git status 
	git add . 
	git commit -m “Your Message and specify the updated version number” 
	git push origin master  
 	
### Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository] 
Version react-wood-duck after you made changes. 

	npm version patch/minor/major
	
### Publish to NPM

	npm publish -m “ your message/version number”
	
### Documentation

Update the List of Components if you add any new components and styles to this library(Need to be edited)



