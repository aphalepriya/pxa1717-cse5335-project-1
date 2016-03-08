CSE 5335 PROJECT 1
==================

README.MD
---------

### What server framework did you choose and why?

The server framework used for this project is **Ruby on Rails**. Rails is quite easy to use and its MVC structure makes segmenting of the client framework more organized. It is compatible with many javascript based frameworks like angularjs, jquery, reactjs
For more information, please read [link](http://rubyonrails.org/)

### What client framework did you choose and why?

The client framework chose for this project is **Angularjs**. It is a javascript based framework which can handle single page applications very efficiently. 
Also angularjs packages also known as angularjs-rails gems are also available easily.
For more information, please read [link](https://angularjs.org/)

### What aspect of the implementation did you find easy, if any, and why?

* Implementing the server in Rails was easy and so was the scripting in AngularJS. This is because there are a lot of tutorials available on the internet which neatly explain the working of these two. 
* Plotting the google map was also fine as google API were readily available.

### What aspect of the implementation did you find hard, if any, and why?

* Deployment of the project on Heroku seemed tricky due to database conflicts. * Rails uses sqlite3 by default while heroku needs postgresql. Due to these requirements, the additional requirements of heroku needed to be fulfilled.

### What components OTHER than your client and server framework did you install,
if any, and if so, what is their purpose for your solution?

* Other than AngularJS and Rails, postgresql installtion was required locally on my machine. 
* I also bundle-installed the required gems (meaning rails packages) required for the postgresql. 


### What Ubuntu commands are required to deploy and run your server? 

** Ubuntu commands required to run the rails server are: **
'rails server'
This command starts the rails server and the application can be view at localhost:3000

** For Heroku deployment, the following command sequence needs to be followed**
heroku create

git push heroku master

heroku run rake db:migrate

heroku open




