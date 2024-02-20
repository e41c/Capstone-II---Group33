# Dev Notes

Hello Ryan here! This section of the repo is made just to log the entire development journey from all the milestones and setbacks I encounter. I'll try to be as open/transparent and frequent with these updates as the project progresses.

## Dev Log - 02/19/2024

I'm embarrassed to admit how long it took me just to read over the css files and cross reference every div tag with their respective classNames. I tried my hand at tailwind.css but was unfruitful. Maybe I'll try again in the future but for now normal css stylesheets will suffice. I was able to conjure up a basic template for the landing page, complete a functional navigation bar at certain screen resolutions.<br>

Our groups Sprint 5 presentation is 4 days away as of writting and the workload seems manageable. Hopefully we'll have 2 screens functional & rehearse a skit when presentation day comes!<br>

Here are some prototype early development webpages I authored for the project!

**Wide Resolution**
![landing page wide-resolution](./screenshots/02-19-2024/landing-page-1.JPG)
![landing page wide-resolution part 2](./screenshots/02-19-2024/landing-page-2.JPG)

**Narrow Resolution**
![landing page narrow-resolution](./screenshots/02-19-2024/landing-page-3.JPG)

## Dev Log - 02/13/2024

I couldn't get any of my group members code to run on my local machine so I remade it all from scratch and salvaged what I deemed usable (model folder for all the schemas, and the dockerfile). I'll be setting up a simple front-end registration, login and sign up page, API calls, and Routes myself

I finished the basic routing for 3 pages as of today register, login, and homepage for students and was able to have front end post all the data into my mongodb database via tables and schema

Here is my registration page with a successful post request
!["Registration page with console logs"](./screenshots/02-13-2024/front-end-student-register-pg.JPG)

and here is my mongodb database, table and schema
!["mongodb compass with the data being stored in the database"](./screenshots/02-13-2024/back-end-mongodb-students.JPG)
