# Real Time Submission Form

# Basics

#### Link to the Github Repository for the Project
[Your Repo](https://github.com/ccgamble/Real-Time)

#### Link to the Deployed Application
[Your Application](https://cg-realtime.herokuapp.com/)

#### Link to Your Commits in the Github Repository for the Project

-[Christine](https://github.com/ccgamble/Real-Time/commits/master)


#### Provide a Screenshot of your Application

![Screenshot1](https://cloud.githubusercontent.com/assets/15853081/22710128/6bdbd9fc-ed39-11e6-8511-65e49ba1754d.png)
![Screenshot2](https://cloud.githubusercontent.com/assets/15853081/22710111/607337d6-ed39-11e6-8723-649a2d1dc669.png)

## Completion

#### Were you able to complete the base functionality?
Yes, I believe I met all of the base functionality.
- [x] Can generate a new poll
- [x] Gets back a link that can be shared with others to the poll
- [x] Users need to authenticate themselves before they can vote
- [x] Can see real time poll results and a picture of each student next to their response

#### Which extensions, if any, did you complete?
No extensions

# Code Quality

#### Link to a specific block of your code on Github that you are proud of
[Code](https://github.com/ccgamble/Real-Time/blob/master/public/poll.js#L19-L26)
I think this code is fairly clean and is a good way of hiding/showing the poll based on the login status of the user.

#### Link to a specific block of your code on Github that you feel not great about
[Code](https://github.com/ccgamble/Real-Time/blob/master/public/styles.css#L1-L7)
This is all of my styling. I know this isn't really included in the project spec, but it would have much better UI/UX if I had time to add SOME styling.

#### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
[Terminal screenshot](https://cloud.githubusercontent.com/assets/15853081/22713744/e9ac7938-ed46-11e6-950e-d4efe60a406d.png)


#### Please feel free to ask any other questions or make any other statements below!
I'm still trying to deploy to heroku. I missed that lesson, and I'm currently running into some errors.

# Instructor Feedback

- Points: (base 150)

89/150

UPDATES
- [x] Fix major poll bug with a test [Code](https://github.com/ccgamble/Real-Time/blob/master/test/routes.js#L87-L99)
- [x] Significant refactoring
- [x] no linting errors -> used eslint
- [x]  no spacing issues -> changed tabs to spaces
- [x] very minimal functionality in a document.ready or event listener
- [x] README with info on how to run the app and link to production [README](https://github.com/ccgamble/Real-Time/blob/master/README.md)
- [x] One unit test [code](https://github.com/ccgamble/Real-Time/blob/master/public/test/test.js)
- [x] [Deployed](https://cg-realtime.herokuapp.com/) 

Nice to Haves

- Seperate file for ajax calls
- Fix the ability to have 3 options or 4 options

### Base Functionality 

- 20/50

- Directs user to a different poll that the one we filled out - broken locally and in production - get the exact same id for each poll

- When another user visits the poll - they don't see the other votes until they vote - but argument to keep it this way so that other votes don't skew your vote. But it does update for all users live.

### JavaScript Style

35 points - Developer solves problems with a balance between conciseness and clarity and often extracts logical components. Developer can speak to choices made in the code and knows what every line of code is doing.

Need to set up text editor to correct tabs - code looks fine in editor 

### Unit Test

17 points - The application has most routes tested. There are no tests failing testing on master.

### Workflow

17 points - The developer makes a series of small, atomic commits that document the evolution of their application. There are no formatting issues in the code base.

## Retake - Feb 28, 2017

114/150 (score of 3)

**Note:**

When I run eslint on a cloned version of the app - I get a number of errors.

For example, [this like of code](https://github.com/ccgamble/Real-Time/blob/master/public/app.js#L32) gives a `'postURL' is not defined no-undef` error - which is a logical error which relates to the way you name the function and hoisting.

Concept and Features

Does it have the expected features?

50 points - Met expectations as outlined by the user personas, the application is a solid first version. All planned features were delivered and the application is easy to use.

Code Quality (JavaScript)

See eslint error notes

35 points - Developer solves problems with a balance between conciseness and clarity and often extracts logical components. Developer can speak to choices made in the code and knows what every line of code is doing.

Testing

17 points - The application has most routes tested and some unit tests. There are no tests failing testing on master.

Workflow

Notes: See the eslint notes above

12 points - The developer makes large commits covering multiple features that make it difficult for the evaluator to determine the evolution of the application.
