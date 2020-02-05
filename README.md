# Cooper Client Application API

The cooper client is a web applitcation that users can use to log their age along with the distance of any 12 minute run, to recieve a grading of their aerobic abilty, based on preset standards from the military Cooper Test.

## Deployed Site
https://cooper-client-eevan.netlify.com

## Dependencies
- Rails 6.0.2
- Ruby 2.5.1
- devise_token_auth
- rack-cors

## Setup
#### Clone repository
```
$ git clone https://github.com/EevanR/cooper-api.git
$ cd cooper-api
```

#### Install dependencies
Install dependencies
```
$ bundle
```
Install Rspec if you wish to run the automated tests
```
$ rails generate rspec:install
```

## Run testing frameworks
In console:
Initiate and Run Cypress 
```
$ rspec
```

### Actions available to the user

Head to the deployed address listed above and fill in the required fields!

## Updates/Improvement plans
Further styling and functionality.

## License
Created under the <a href="https://en.wikipedia.org/wiki/MIT_License">MIT License</a>.