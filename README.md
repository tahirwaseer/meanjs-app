# meanjs-app
Complete setup for meanJs application. Amazing meanjs generatore and all dependencies included.
No need to stumble upon tedios methods of installation to bootstrap your application.

It is quite simple to start your new MEAN stack application with already integrated yo generatore and quick example modules for 'articles' and 'chat' added.
Here are simple steps to awesomeness;

1. Install mongoDB, its quite easy download from official website : http://docs.mongodb.org/master/installation/ and follow the simple steps of installation. 

2. Install nodeJs to your machine, download from the official site;
   https://nodejs.org/en/download/
3. If you have not installed grunt-cli command line tool for grunt(automates and runs all tasks), then use this command to install it;

   $ npm install -g grunt-cli
   
this will give you access to your locally installed grunt.

3. When both mongoDb and nodeJs are installed, create folder for project and clone directory into it.

   $mkdir my_directory & cd my_directory

   $ git clone git@github.com:tahirwaseer/meanjs-app.git

 here you go. Done with the setup shit.
 
4. Lets have some action, goto cloned directory

   $ cd meanjs-app

  and run app using grunt;

  $ grunt

Here you go! Goto http://localhost:3000 and have fun. 
