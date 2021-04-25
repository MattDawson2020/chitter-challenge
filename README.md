Chitter Challenge
=================

```
STRAIGHT UP

As a Maker
So that I can let people know what I am doing  
I want to post a message (peep) to chitter

As a maker
So that I can see what others are saying  
I want to see all peeps in reverse chronological order

As a Maker
So that I can better appreciate the context of a peep
I want to see the time at which it was made

As a Maker
So that I can post messages on Chitter as me
I want to sign up for Chitter

HARDER

As a Maker
So that only I can post messages on Chitter as me
I want to log in to Chitter

As a Maker
So that I can avoid others posting messages on Chitter as me
I want to log out of Chitter

ADVANCED

As a Maker
So that I can stay constantly tapped in to the shouty box of Chitter
I want to receive an email if I am tagged in a Peep
```

Setup:
-------

* Clone this repo and run bundle migrate to install any dependencies
* Run migration files 1, 4 and 5. Files 2 and 3 are redundant after an SQL issue prevented database alteration  
* Use < rackup > command in terminal to launch Sinatra server, and go to localhost:9292 to interact with the app


Successes
-----

* All but advanced challenge feature implemented with full test coverage
* Successfully implemented authentication and login, as well as time formatting
* Everything until Bcrypt and styling done without references/ documentation

------------------

To improve
-----
* Styling is weak and took far too much effort, would use a front end framework next time
* More detailed planning, needed to remake a table because I couldnt work out how to add a relationship to an existing table
* Forgot to implement functionality to have a users name taken into a message and rendered on page
