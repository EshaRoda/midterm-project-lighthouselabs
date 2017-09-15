# "Smart To-Do List!" Group Midterm Project (Lighthouse Labs)

Group Members: Jonathan, Shahab, Esha

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
