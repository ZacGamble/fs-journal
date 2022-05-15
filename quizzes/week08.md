# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
It is the file that exists at the root of your project.
It contains all the data relevant to that project such as its dependencies.

``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
It needs to exist at the root directory level.
As it contains all the metadata such as dependencies, it needs to execute before anything else can run properly.

```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm run build
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
.env 
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
Using the heroku logs --tail command in the terminal is one way.
You can also view the web page itself and check for errors there.
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Run git add, git commit, git push heroku main, then heroku open. You should see the changes. Otherwise, re-run npm run build and the associated heroku commands used to launch the application.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Branching is importaint because it allows you to create and push experimental changes without the risk.
If you make crippling changes to the main branch constantly, development would be slow and painstaking. Branching avoids this.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Code review can happen during implementation or after the application hits production.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merging branches.
```