# household
This is a model design for an web application, for household management. 

With the following specification, 

'''HouseHold
System specification
The goal of the application is to track various information about the state of a household.
->>>1. Stock management
One of the main features is the management of stock of various items and material in a household.
The items can range from cooking stuff (milk, flour, rice, cooking oil, etc.), to hygiene and health stuff
(shower gel, toothpaste, various drugs and medicines), to maintenance and reconstruction material
(paint, bulbs, packed concrete mixture, planks, bricks) to inventory (furniture, books, DVDs, etc.). The
items should be categorized (with a hierarchy of categories (paint - wood paint - brown paint) and
have a location (which should be shared by multiple items). It is necessary to track different pieces of
item of the same type separately (2 cans of the same paint separately), including the possibility to
track portions of the items (1 can of paint already used with just a half of paint remaining). For each
items, time information should be tracked (when added/bought, when opened, when used).
Amount of material in each item should be tracked (one sack of 1kg of rice, one can of 0.5l of paint,
…). All basic units should be supported (weight, volume, distance, dimensions). Aggregation for the
amounts is expected (How much paint do I have in total?).
Basic information like title, description, tags, picture, and similar for each item is obvious.
It should be possible to set up expiration date for each item and get notifications when an item is
about to expire so it can be discarded or restocked.
Advanced searching is needed, obviously. Listing items based on category of various levels (getting all
paints, getting only wood paints, etc.), name, date of expiration or date of opening.


->>>>2. Sharing the household
It should be possible to share the household data with other users (explicitely or in a
group/family/friends). Individual items should have a visibility level set to determine, who can see
the properties of that item.

->>>3. Energy consumption tracking
Along with the information about the inventory of the household, tracking of energies should be also
possible. Registering consumption of water, electricity, gas or others should be possible. It should be
possible to attach bills for specific period and value ranges. It should be possible to set up reminders
for registering the consumption values. It should be possible to browse the values, including
visualization of the consumption, comparing consumption in different periods of time.

->>>4. Maintenance planning
Lots of devices should be revised periodically in a household (electronics, chimney, filters, ...). It
would be very useful to be able to set schedules to certain items in the inventory for regular
maintanance and get notifications and tasks to have the maintenance done. The schedule might
range from once per month/year to every 2 day/6 months to specific days of week/month/year. Each
maintenance task should have a deadline, status, description. Tasks should be generated
automatically for the next maintenance. An assignee can be set.

This is a current running group project. I worked with 7 other people on this course.


To run the project, use,
->download the zip, uncompress it, open it via eclipse, intellij or any other IDE that support JAVA EE.
->jdk 19(also works on jdk 17), spring boot, thymeleaf plugins.
->have a postgres server running on port 5432 with username: postgres, password: postgres
->run application, go to browser and go to location http://localhost:8080/ to view the web app.
->Best to use chrome, edge, firefox (updated version).
