# react-wood-duck

The react-wood-duck is a series of individual styles and components, that when combined make beautiful, intuitive designs.
The shared component library gives developers a collection of re-usable React components and SCSS partials for building their products.

## Installation

using npm,

        npm install react-wood-duck --save
  
## Usage

Now, you can import the components from the library into the application as,

         @import { component name } from 'react-wood-duck'
 
   For example, using component from library(react-wood-duck) in the application app/javascripts/components/hello_react.jsx  
   <img alt="Syntax highlighted styled component" src="https://user-images.githubusercontent.com/30934662/29230515-456a29cc-7e98-11e7-9fb4-2b1a34a98a55.png" height="300px" />
  
## Development (src, dist and the build process)

NOTE: The source code for the component is in src. A transpiled CommonJS version (generated with Babel) is available in dist for use with node.js and webpack.A UMD bundle is also built to dist, which can be included without the need for any build system.


## Contributing
See the [contributing guidlines]() for details on our code of conduct,
You can contribute by adding and modifying new or excisting components and styles.

### To Add/Modify Components

Clone the repository from git

        git clone link

Create or modify the react components in react-wood-duck/src.

compile the code in "src" and bundle them in “dist” folder locally, run

	npm run pre publish
        
## Push to git

Commit the changes and push to GitHub
        
        git status 
        git add . 
        git commit -m “Your Message and specify the updated version number” 
        git push origin master  
 	
## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository] 
Version react-wood-duck after you made changes. 
 “ npm version patch” —> it updates the package version automatically in package.json
 
## Publish to NPM

        npm publish -m “ your message/version number”


