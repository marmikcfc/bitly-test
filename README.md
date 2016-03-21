# Bit.ly Front-end Intern Application

This is my attempt on the Bitly coding excercise. 

## Tech Stack:

* Meteor.js : Basic user accounts and other inbuilt features of Meteor helped me with rapid protoyping
* Material Design 
* MongoDB for persistent data storage
* Clipboard,js to give me copy to clipboard feature
* Bitly SDK for URL Shortening


## Limitations
* Due to time constraints I couldn't complete realtime querying to Bitly SDK to get the counts. It could be added next. 
* Even the code looks a bit messy and it needs some kind of refactoring.
* Current Publication/Subscription model is bit messy and it would slow down the app if the amount of URL user queried is a huge. 

### Folder structure

```
client/ 				# Client folder
    modules/            # Meant for templates and views
	common/         # General purpose html templates
public/                 # Public files
lib/                    # All routes and Meteor Collections
server/					# Server folder
    publications/       # Collection publications
    
```

## Installation and Running

To install meteor use following command

``` 
curl https://install.meteor.com/ | sh
```
Next use following command to run

``` 
cd <project-directory> && meteor
```

