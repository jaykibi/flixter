# FLIXTER 

* Live (hosted with Heroku) version: http://flixter-kibi.herokuapp.com/
* Video demo: https://youtu.be/EL7wfU7IiPE

This is just a clone of udemy that I made! It makes use of the popular [STRIPE API](https://github.com/stripe) in order to take payments. Payments are not live, this is just a proof of concept/understanding. 

### Ruby version: 2.5.3

### Configuration: 
A Vagrant environment with virtual box was used for development of this project. Please refer [here](https://www.vagrantup.com/docs/installation) to install your vagrant virtual environment. 

### Database creation:
Once you have your environment set up and have a cloned the repo, run
**rake db:setup** this will create and run the migrations for the database on your project. 

![Homescreen](https://github.com/jaykibi/flixter/blob/master/app/assets/images/github_images/homescreen.JPG)
