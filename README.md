# non-shared-files
## To run: npm init and node app.js
### The message in console expected is "Example app listening on port undefined" and shouldn't be able to access "localhost:3000" because the application express doesn't know the port to start a local server on because that port was a secret variable on .env file. 
The point of having a dot in front of a file is to be treated as hidden, meaning the ls command does not display them unless the -a or -A flags ( ls -a or ls -A ) are used.
