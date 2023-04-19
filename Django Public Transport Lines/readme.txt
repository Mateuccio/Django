The Django Djitney
The Codes-ville Official Department of Transportation needs your help! 
They recently finished building the routes for their new commuter train, the Django Djitney, 
and need someone to create an easy-to-use site for commuters to be able to see the train routes. 
They’ve supplied the train routes in a database, but they need your help to create a site that 
they can use to show the different routes across all the stations, as well as update them when there are changes in the routes.

Each jitney line takes different routes through the stations. You can take a look through 
models.py to see how each model relates to each other. But the basic breakdown is that a “stop” 
consists of a “line”, a “station”, and a “stop number”.

The town wishes to have the ability to view, edit, update, and delete lines, stops, and stations. 
They’ve outsourced the creation of the templates, and they’ve supplied the models on their own. 
All you’ll need to do is create the views and link them up to the templates.