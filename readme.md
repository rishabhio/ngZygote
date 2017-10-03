# Lets build an angular app from very scratch 

# Step-1 
###Create a directory and name it ngZygote to contain our project 
-> mkdir ngZygote 

# Step-2  
###Initialize an npm package 
-> npm init // choose default options mostly 

# Step-3 
### edit your package.json file and add dependencies information to it as shown below 
### all these are the minimal dependencies for our angular app 

# Step-4 
### now install all the dependencies using the following command 
-> npm install 

 this installs all the required dependencies to the project 

## now add typescript configuration file to your project 
this file instructs typescript compiler on how to do certain things 

### next add another file webpack.config.js which is what is used by webpack to 
### accomplish its tasks 

 webpack is a module loader which is generally used to achieve module loading stuff but 
 with its plugins it usually does more than just module loading , it has plugins to 
 perform many different tasks like 
 understanding different file extensions and loading them all 
 performing certain set of tasks 

-> webpack.config.js 


 All the configurations we did above are just a setup to get us started , we've not yet 
 written a single line of our project code but these configurations save a lot of time 
 in a long run as we'll see shortly 

 Create a src folder for the source of our app 
-> mkdir src

 inside src created the following 4 files and make sure they look similar to what's given below. 

