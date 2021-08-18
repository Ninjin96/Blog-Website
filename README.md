# Blog Website
Hi there everyone and future me! This is my very first backend project on my GitHub page. In this project I've used Node.js together with the Express.js module to set up a server and take a step away from the static websites I used to create in my previous projects. I've also used the templating language EJS to structure my code in a little more organized way. Have fun checking this project out and make sure to follow the steps!



## Preview:
[![](https://i.ibb.co/Q60Cx6w/preview.png)](#)

In this web application you can compose blogposts that will eventually appear on the homepage! Furthermore you can also go to your full individual posts by clicking on the *Read More* link next to your posts. There's also another way to do that and you can find out if you continue reading...

As a sidenote: this application will not save your blogposts so be careful not to close the webpage otherwise all your valuable stories will be gone! This is due to the fact that this application is not connected to a database.



## How To Use?
No idea yet how to use node.js? Fear not! These steps will help you to successfully run this application on your computer. If Node.js is already familiar to you then you can proceed to _**step 4**_.


### Step 1: Download Node.js
[
![](https://i.ibb.co/8PmX1PS/installnode.png)
](#)

First [download](http://github.com) node.js and choose the correct installer for your machine. This download process should be very self-explanatory.

To test if you've installed Node.js correctly. Open up you *command prompt* and type in:
~~~
node --version
~~~
[![](https://i.ibb.co/yS3LVHw/nodeversion.png)](#)

If you will be prompted a version number like so, you have successfully installed node.js.



### Step 2: Download And Extract The Files From This Repository
[
![](https://i.ibb.co/7Gz17wN/downloadrepo.png)](#)

Download the repo and save it somewhere you can remember the location of :)

After you've downloaded the *Blog-Website-main.zip* make sure to unzip it.



### Step #3: Start The Server!
After you have unzipped the *Blog-Website-main.zip* to your preferred location go and open your command prompt again.


[
![](https://i.ibb.co/QKjmK01/startserver.png)](#)

Firstly, make sure you are inside the *\Blog-Website-main* directory like in the picture above.

Secondly, install all the necessary node modules for this application by typing the following in the command line:
~~~
npm install
~~~
Now lastly, start up the server by typing in:
~~~
node app.js
~~~
The server is now up and running on your machine and you should be prompted: *Server started on port 3000...*



### Step 4: Open The Application In Your Browser.
After you've entered the command `node app.js` in your command prompt it's time to open your browser. Inside your browser, type in the URL: `localhost:3000` and hit enter.

Congrats! You should now be able to see the website up and running!



## What Now?
As you can see the home page is fully blank. You can navigate to the *About Us* and the *Contact* page. But that that's not all! This is a blog application after all right? This is what you can do:

- If you type in the URL `localhost:3000/compose` you can actually create your own blog post!

- Why not try making a few blog posts to see how they add up?

- After you've finished making some blogposts you can see your full blogpost by clicking on the *Read More* next to your post on the home page.

- You can also see your post by typing in the URL: `localhost:3000/posts/[title of your post]`.

Thank you so much for taking the time to check out my project! I hope you had fun and until next time :D
