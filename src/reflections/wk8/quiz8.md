# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
This file holds various metadata relevant to the project.  It is used to give information to npm that allows it to identify the project as well as handle the project's dependencies.
``` 
**2.** At what level of your project do you need package.json when  deploying your application? Why?
<!-- enter you answer in the space below -->
```
The package.json file should be deployed at the root level as to be relevant throughout the entire application.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
The use of the vue create npm compliler in your command line.
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
vue-routers
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
Through the log retrieval on the heroku dashboard and through your CLI utilizing '$ heroku logs'
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
This can be done in 5 steps:
1) Clone the repository from GitHub to your local device
2) Make your cahnges, and commit them to Github
3) Login to your Heroku account
4) Set remote for your project
5) Push to Heroku master to deploy updates

As seen in the Heroku documentation:
https://devcenter.heroku.com/articles/git
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
It helps teams work in parallel to obtain a goal faster.  It also tracks work being done and prevents descepancies that would surely happen if everyone was working on the master branch.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Ideally, code reviews should happen after unit testing.  
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merge: Such as, merging the client branch to the master branch so everyone that pulls the master down has my changes from the client branch on it.
```
