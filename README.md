# friend-finder
## Demo
	
*Friend Finder* is deployed to Heroku. Please check it out [here](https://mushy-friends.herokuapp.com/).

## Installation

To install the application follow the instructions below:

	git clone git@github.com:pyromaniac14281/friend-finder.git
	cd friend-finder
	npm install
	
## Running Locally

To run the application locally and access it in your browser, first set the `PORT` environment variable to the value of your choice. An example is shown below.

	export PORT=3030
	
After the `PORT` environment variable has been set, run the Node.js application with the command below.

	node server.js
	
The application will now be running locally on `PORT`, in this case that is port 3030. You can then access it locally from your browser at the URL `localhost:PORT`, in this case `localhost:3030`.
