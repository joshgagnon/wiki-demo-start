# Wiki Demo Project

Your job is to create a super basic wiki using javascript or typescript.



### Getting started
Install nvm, unless you have node v22 installed already
```
nvm install 22
nvm use 22
```

Clone the repo and run 
```
npm i
npm run serve
```

### Requirements
* You should be able to type in a new url path and the app will do a look up to see if that page exists and if not create a new blank one for you
* Data persistence - however you like: localstorage or a database or json in the file system
* Presentation - will the wiki data use html, markdown or something else?
* The wiki pages should have some sort of organisational structure, whether it be categories, a tree, or a graph.  Present this somehow so users can find pages.

### Tech
* Will you use a framework?  Vue, React, Vanilla, or anything you like, the world is your oyster
* How will users enter data?  Textarea elements aren't very user-friendly for long text, what could you use instead?
* Do you want to add a backend? How will that play alongside esbuild?

### Considerations
* Will titles have to match urls?
* How you will you deal with name collisions?
* Will you have validation?
* How will you manage application state?
* Will you have edit histories?  Any authorisation or authentication?