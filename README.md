# meanjs-app
* Complete setup for meanJs application. Amazing meanjs generatore and all dependencies included.
No need to stumble upon tedios methods of installation to bootstrap your application.

* I feel many people get in trouble while installing dependencies for meanjs generatore as I got bundles of errors. So, here is all dependencies already added for people like me who have trouble in bootstraping new app.
* It is quite simple to start your new MEAN stack application with already integrated yo generatore and quick example modules for 'articles' and 'chat' added.

## Prerequisites
Make sure you have installed all of the following prerequisites on your development machine:
* Node.js - [Download & Install Node.js](http://www.nodejs.org/download/) and the npm package manager. If you encounter any problems, you can also use this [GitHub Gist](https://gist.github.com/isaacs/579814) to install Node.js.
* MongoDB - [Download & Install MongoDB](http://www.mongodb.org/downloads), and make sure it's running on the default port (27017).
* Bower - You're going to use the [Bower Package Manager](http://bower.io/) to manage your front-end packages. Make sure you've installed Node.js and npm first, then install bower globally using npm:

```bash
$ npm install -g bower
```

* Grunt - You're going to use the [Grunt Task Runner](http://gruntjs.com/) to automate your development process. Make sure you've installed Node.js and npm first, then install grunt globally using npm:

```bash
$ npm install -g grunt-cli
```
* When both mongoDb and nodeJs are installed, create folder for project and clone directory into it.

   ```bash
	$ mkdir my_directory
   ```

   ```bash
	$ git clone git@github.com:tahirwaseer/meanjs-app.git my_directory
   ```
 You can user any other method to download repositry. 
 
4. Lets have some action, goto cloned directory

	```bash
	 $ cd my_directory
	```
and run app using grunt;

	```bash
	 $ grunt
	 ```
Here you go! Goto http://localhost:3000 and have fun.
