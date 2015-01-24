Example isomorphic application using React, Express, and Browserify
========================================================


Directory structure:

/app
	holds code to be shared between server and client
	
/app/src
	Source code -- JSX files
	
/app/transformed
	Source compiled into javascript. modules should be required from here.
	
/app/transformed/main.js is bundled into /public/javascripts/bundle.js