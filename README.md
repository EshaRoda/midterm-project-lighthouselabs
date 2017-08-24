# Jonathan Sue's "Daily Plan-It!" Group Midterm Project (Lighthouse Labs)

## Personal Observations and Notes

- Team members for this project were not chosen by the students. Rather, Lighthouse Labs' staff created the teams; it is my personal belief that they chose to match stronger students with individuals who were experiencing more difficulties with the curriculum.
- Given the composition of the team that I was placed on, it was necessary for me to assume a disproportionate amount of the overall duties for completing the project. As such, this is a brief overview of the tasks which I personally worked on:
  * The majority of the functionality for this app happens on the server-side. I was responsible for writing 100% of the code in server.js file, which contains all of the route handler specifications.
  * I created the database schema using my previous knowledge of relational databases. This database was created in PostgreSQL's command line interface. I also wrote 100% of our database migration scripts using Knex.
- Given that I was essentially needed to write the entirety of the code which was used for the functionality of the app, I found that I was unable to devote attention to other areas of the project. As such, here are a few issues with the project that I would've liked to resolve, had there been more time:
  * The server-side code is very messy and not very DRY. It definitely needs serious refactoring and better organization. That said, our goal when we were given this project was to first and foremost ensure that we had a working app before we made it "pretty".
  * Overall, the CSS is very poorly executed. There are a number of issues, which include, but are not limited to, the following: The styling is not appealing at all to the user. Styles are inconsistent between pages. Classes for HTML tags are confusingly named. There is no usage of Sass (which was a requirement). Most glaringly, there are several instances of inline styling (which is a big no-no for me).
  * Our group's use of GitHub was not very well-executed. Commits were far too infrequent for my liking. Branches were inconsistently named and the work that was done on each branch was not always scoped to the original feature which the branch was intended for.
- I may choose to work on fixing the aforementioned issues at a later time to make the overall project more presentable and professional. This will likely be dependent on whether I believe there is value in doing so, as well as my time availability.


## Project Goals (as provided by Lighthouse Labs)

- Build a web app from start to finish using the tech and approaches learned to date
- Turn requirements into a working product
- Practice architecting an app in terms of UI/UX, Routes/API and Database
- Manage a multi-developer project with git
- Simulate the working world where you do not always get to completely cherry pick your team, stack or product features
- Practice demoing an app to help prepare for the final project and employer interviews


## Project Background

For this project, our team chose to create our own version of the popular event planning web application, [Doodle](https://doodle.com). We chose this because this application fulfills a very important need for people in the modern communication age: it allows people to easily schedule events for a potentially large group without much effort. Our job was to do our best to re-create Doodle while putting our own spin on it.


## Functional Requirements

- Visitors can create an event proposal in much the same way as Doodle, by specifying:
  * An event title and description
  * their own name and email
  * organizers can then send the unique URL to possible attendees via their own communication workflow (email, Slack, Messenger, etc.)
  * attendees visit the unique URL and:
  * specify their name and email
  * specify their availability (yes/no only) for each possible time slot
  * view all responses including their own
  * modify their response
- the unique URL should be secret and thus not use a simple auto-incrementing integer but instead a larger ID that is harder to guess (much like how secret gists work on GitHub)
- note: this app does not follow the typical user authentication process: users don't need to register or log in and the only way to access the Schoodles is via links


## Final Product

!["Screenshot of Main Page"](https://raw.githubusercontent.com/jonosue/midterm-project-2017/master/docs/home-page.png)
!["Screenshot of Choosing Dates for Event"](https://raw.githubusercontent.com/jonosue/midterm-project-2017/master/docs/choosing-dates.png)
!["Screenshot of the Page Which Can Be Shared"](https://raw.githubusercontent.com/jonosue/midterm-project-2017/master/docs/date-voting-page.png)
!["Filling out the Form to Submit Response"](https://raw.githubusercontent.com/jonosue/midterm-project-2017/master/docs/fill-out-form.png)
!["List with Responses Shown"](https://raw.githubusercontent.com/jonosue/midterm-project-2017/master/docs/list-of-votes.png)


## Getting Started

1. Fork this repository, then clone your fork of this repository.
2. Install dependencies using the `npm install` command.
3. Start the web server using the `npm run local` command. The app will be served at <http://localhost:8080/>.
4. Go to <http://localhost:3000/> in your browser.


## Dependencies, Scripts, and External Requirements/Resources

- body-parser
- Bootstrap
- connect-flash 
- cookie-session 
- dotenv 
- ejs 
- express 
- knex 
- knex-logger 
- morgan 
- node-sass-middleware 
- nodemon
- npm-install-package
- npm-install-retry 
- pg 
- sqlite3


## Contact

Questions? Comments? Please tweet the author of the README at [@JonoSue](http://twitter.com/JonoSue).


*README: Last updated August 24, 2017*
