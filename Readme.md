# What is this I don't even?

Welcome to Nooga Startups, a directory of the awesome startups located in Chattanooga, Tennessee. It was inspired by sites like [Made in New York](http://nytm.org/made/).

# Chatta-what?

[Chattanooga](http://goo.gl/maps/lb6o7), fondly known as the 'Noog, 'Nooga, or simply "The Paris of Southeast Tennessee". Chattanooga is home to a number of great startups, a fantastic outdoor scene, delicious food, and some great whiskey.

## Interesting Facts about Chattanooga:
 - The world's first coca-cola bottling plant opened here in 1899.
 - The annual [Riverbend Music Festival](http://www.riverbendfestival.com/) is consistently rated as one of the best festivals in the country.
 - World-class kayaking and climbing is located within thirty minutes of the city.
 - The country's first 1Gbps residential network, and the coverage stretches across the entire county.
 - Conveniently located ninety minutes from Atlanta, Nashville, Birmingham, and Knoxville. From country music concerts to the world's busiest international airport... it's all close.

# What's the point of this?

It's time to get the secret out... Chattanooga has an emerging tech scene, a thriving downtown, and a lot of energy and momentum. We want to make it easier for engineers, journalists & founders to see whats happening in Chattanooga and get more information about the movement.

Software is eating the world and the most successful economies of tomorrow are building around this. Our goal is for Chattanooga to be one of these economies and it's time to build the buzz and bring in the talent.

# How can I run this project?

First, make sure that you have ruby & rails dependecies installed locally. Before generating your application, you will need:

* The Ruby language – version 2.2
* The Rails gem – version 4.2

See this article [Installing Rails](http://railsapps.github.io/installing-rails.html) for instructions about setting up Rails and your development environment. If you're running an outdated version of Ruby, see this article [Updating to Rails 4.2](http://railsapps.github.io/updating-rails.html) 

## Setting up your database 

Use SQLite for development on Mac or Linux, unless you already have PostgreSQL installed locally (which we use for production deploys). You can easily change the database later if you select SQLite to start.


## Installing NoogaStartups locally

Once you have Rails on your machine, running the project locally is three commands:

Grab the dependecies with bundler 

        bundle install

Next create the database and run a migration

        bundle exec rake db:create db:migrate

Finally, run the rails server & navigate to port 3000
  
        # server running on localhost:3000
        bundle exec rails s 
        

# How can I get my startup added to this list?

The easiest way is to submit a [pull request](https://github.com/Tgemayel/Nooga-Startups/pulls). Tweet [@NoogaStartups](http://twitter.com/noogastartups) if you need help.

When submitting your [pull request](https://github.com/Tgemayel/Nooga-Startups/pulls), make sure your image is 600x400 to keep all images consistent in size.

Please note that at this time we are only looking for product-focused tech startups featuring a website our users can visit to learn more.

For those new to GitHub (we've all been there):

1. Install git on your computer:

        sudo apt-get install git-core # Ubuntu 
        brew install git-core # OS X
        
2. Fork the Nooga-Startups repository by clicking on the Fork Button in the top right corner of this page.

3. Open up your terminal and run the following:

        git clone https://github.com/<your_username_here>/Nooga-Startups.git

4. Make your changes and push to your fork:

        git status # Shows what files you modified
        git add <modified files> # Do this for every file
        git commit -m "<comment your commit here>"
        git push https://github.com/<your_username_here>/Nooga-Startups.git

5. Submit a pull request by clicking on the Pull Request button in Github

6. If merged, head to [Nooga Startups](http://noogastartups.com) and enjoy your handy-work!
If commented, make sure to make the following changes and re-submit!



# I want to get involved

Great! We fully intend on this being a community run project. Check the [issues log](https://github.com/Tgemayel/Nooga-Startups/issues) to see what things you can tackle first!
