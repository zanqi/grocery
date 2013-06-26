Grocery
=======

Overview
---------
Grocery is a web application that allows a family to manage their grocery shopping list. A sample deployment can be found here: [Grocery](http://rocky-atoll-4820.herokuapp.com/)

Setup
------
To run, install rails 4.0, then cd into the root directory of this source and run the following commands:
```
bundle install --without production
bundle update
bundle install
bundle exec rake db:migrate
rails s
```
The last command starts up the server. You can visit the application at [http://localhost:3000](http://localhost:3000)

On the next in Grocery development
----------------------------------
* Add a calendar view like [this](http://bl.ocks.org/mbostock/4063318) to let the family visualize their buying habbit. Put filters besides the graph to let the family choose what they are interested in: e.g. Only show items "Milk" in the calender.
* Add auto-completion to help user creating and editing items.
* Investigate how to use [Square](https://squareup.com/ca?country_code=ca) to automate checking the purchased items off the list and recording its price in the process. Use the recorded price to create [Bubble Chart](http://bl.ocks.org/mbostock/4063269).