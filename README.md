

# lti-outcome-provider
This is an LTI tool provider that allows you to post outcomes (grades) back to the consumer.



## Usage
All packages needed are in the package.json. 

You should have node installed (built with 5.4). Then from the project directory at the commandline, type npm install. This will install all of your dependencies.

To run, type:

npm start

By default it listens on port 3000. The LTI launch endpoint is:

http://localhost:3000/lti

## Developing
This is a work in progress. Currently accepts and validates the LTI launch based on hard-coded values. Working on implementing outcomes, and then caliper. Once that is done, I will work to add more dynamic capabilities, like generating keys/secrets and storing them in MongoDB, handling multi-tenancy, etc. 


