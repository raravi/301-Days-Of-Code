# #301DaysOfCode - Log
The daily log of my **#301DaysOfCode** challenge.

## Log

### Day 1: 27 Jan 2020

**Today's Progress:** Trying out firebase with a React app. Created a React app. Then created a firebase DB. And connected the two for now. Using the freeCodeCamp React exercise for Todoist clone.

**Thoughts:** The going is slow. But there are many concepts to grasp. React hooks, firebase, Sass mixins.

**Link to work:** No link yet, I have to create a repo and safeguard the API keys before that!

### Day 2: 28 Jan 2020

**Today's Progress:** Todoist clone: firebase API key has been obfuscated, and the repo set up for project. Sudoku: Working on Sudoku game in React. Setting up the static version of the site.

**Thoughts:** Good progress today. Satisfied.

**Link to work:**
1. [sudoku](https://github.com/raravi/sudoku/commit/e48786bfb4c0a66a79a9f350dee1b05b94fe37fe)
2. [todoist](https://github.com/raravi/todoist-clone/commit/25366d22437923752d6f054636ef21fa0e97b4c5)

### Day 3: 29 Jan 2020

**Today's Progress:** Sudoku: Added Status buttons. Made the static version of the site responsive!

**Thoughts:** Not much progress, took awhile to get the responsive layout setup properly.

**Link to work:** [sudoku](https://github.com/raravi/sudoku/commit/84f7100a260fce2da8ea7b974956a4dd7649917b)

### Day 4: 30 Jan 2020

**Today's Progress:** Sudoku: Moved the code into different components. Added Timer functionality using [moment.js](https://momentjs.com/) and useEffect hook. Used the map() function to keep the code DRY.

**Thoughts:** moment.js took most of my time today.

**Link to work:** [sudoku](https://github.com/raravi/sudoku/commit/46c320b1d4643d0215cb52599971230b02f4744c)

### Day 5: 31 Jan 2020

**Today's Progress:** Sudoku: Most of the frontend events/functions are wired. The Game is functional!

**Thoughts:** Good progress today.

**Link to work:** [sudoku](https://github.com/raravi/sudoku/commit/e87d0de0fb87dd5ec41eb3e884cc551a126b0ef8)

### Day 6: 1 Feb 2020

**Today's Progress:** Prepared for interview on HackerRank. Added the projects - todovanilla, tictactoe, bitcoin converter & sudoku - to github pages!

**Thoughts:** Time spent setting things up.

**Link to work:**
1. [Sudoku](https://raravi.github.io/sudoku/)
2. [todo](https://raravi.github.io/todo-vanilla/)
3. [Bitcoin converter](https://raravi.github.io/bitcoin-converter/)
4. [Tic Tac Toe](https://raravi.github.io/tictactoe/)

### Day 7: 3 Feb 2020

**Today's Progress:** Added a unique sudoku function and added 'Solved' overlay on win!
Used sudoku solver by [robatron](https://github.com/robatron/sudoku.js)

**Thoughts:** The sudoku web app is ready!

**Link to work:** [Sudoku](https://raravi.github.io/sudoku/)

### Day 8: 4 Feb 2020

**Today's Progress:** Sudoku: Added documentation. Moved the Sudoku solver to a separate folder.
Todoist-clone: Got stuck with using Context, finally figured out the errors!
Added Meta tags to the projects - todovanilla, tictactoe, bitcoin converter & sudoku.

**Thoughts:** Time spent on organizing code.

**Link to work:**
1. [Sudoku](https://raravi.github.io/sudoku/)
2. [todo](https://raravi.github.io/todo-vanilla/)
3. [Bitcoin converter](https://raravi.github.io/bitcoin-converter/)
4. [Tic Tac Toe](https://raravi.github.io/tictactoe/)
5. [todoist](https://github.com/raravi/todoist-clone)

### Day 9: 5 Feb 2020

**Today's Progress:** Created a Twitter bot to retweet/post/favorite tweets. Deployed the node.js app to Heroku free tier. It's currently running from there!

**Thoughts:** Understood the basics of node.js / Twitter API / bot setup / Heroku deployment.

**Link to work:** [twitter-bot](https://github.com/raravi/twitter-bot)

### Day 10: 6 Feb 2020

**Today's Progress:** Twitter-bot: Refactored the code, tweet/retweet/follow/reply to new followers functionality added.

**Thoughts:** Hit the Twitter rate limits due to a bug, and fixed it.

**Link to work:** [twitter-bot](https://github.com/raravi/twitter-bot)

### Day 11: 7 Feb 2020

**Today's Progress:** Chat App: Created boilerplate for client-server level. Lots of decisions pending. Realtime communication using [socket.io](https://socket.io/get-started/chat/).

**Thoughts:** A good start!

**Link to work:**
1. [server](https://github.com/raravi/chat-app-server)
2. [client](https://github.com/raravi/chat-app-client)

### Day 12: 9 Feb 2020

**Today's Progress:** Chat App: Added basic styling to the app. It feels like a chatting app now :)

**Thoughts:** Still figuring out the basics of the app!

**Link to work:**
1. [server](https://github.com/raravi/chat-app-server)
2. [client](https://github.com/raravi/chat-app-client)

### Day 13: 10 Feb 2020

**Today's Progress:** Chat App Server: Added Login / Register routes. Added boilerplate code to handle the above API endpoints. Learnt the basics of Express.js / Passport.js / MongoDB / body-parser / Middleware setup / Routing / API setup!

**Thoughts:** Good progress on server end.

**Link to work:** [server](https://github.com/raravi/chat-app-server)

### Day 14: 11 Feb 2020

**Today's Progress:** Chat App Client: Added the Login / Register pages and used [axios](https://github.com/axios/axios) to POST requests to the API endpoints.
Chat App Server: Added [cors](https://github.com/expressjs/cors) middleware to handle requests from different origins.

**Thoughts:** Good progress on client end.

**Link to work:**
1. [server](https://github.com/raravi/chat-app-server)
2. [client](https://github.com/raravi/chat-app-client)

### Day 15: 12 Feb 2020

**Today's Progress:** Chat App Client: Refactored code into components. Added Message history to chat!! The chat app will revert to Login page on server disconnect. Still learning about session management using socket.io!
Chat App Server: On user being authenticated, chat history will be fetched from MongoDB and sent to client. Understood MongoDB basics.

**Thoughts:** Good progress on client/server end.

**Link to work:**
1. [server](https://github.com/raravi/chat-app-server)
2. [client](https://github.com/raravi/chat-app-client)

### Day 16: 13 Feb 2020

**Today's Progress:** Chat App Client: Added Logout functionality to the website. DRYed the CSS, and themed the site a bit differently! Made the site responsive too!!

**Thoughts:** Progress on the UI side!

**Link to work:** [client](https://github.com/raravi/chat-app-client)

### Day 17: 14 Feb 2020

**Today's Progress:** Chat App Client/Server: Added Forgot / Reset password functionality. Learnt to send mail from node.js backend using nodemailer. Created a /resetpassword route from backend to handle reset requests. The /resetpassword page looks the same as 'texter' chat-app, even though its just a plain HTML page!

**Thoughts:** Added a challenging functionality to the app!

**Link to work:**
1. [server](https://github.com/raravi/chat-app-server)
2. [client](https://github.com/raravi/chat-app-client)

### Day 18: 15 Feb 2020

**Today's Progress:** Chat App Server: Added Rate Limiter middleware to prevent timing attacks.
The Password Reset Token has been hashed prior to saving it in the DB, so it doesn’t compromise user account even if the DB is attacked (e.g., hacker gaining read access to the DB and see plain-text tokens is a threat!)
Removed the pseudorandom number generator Math.random() and replaced it with the cryptographically secure random number generator crypto.randomBytes() function. Math.random() is predictable and a hacker can generate numbers to determine what would be generated next. Crypto.randomBytes() uses system entropy to generate numbers, and is used by OpenSSL!

**Thoughts:** Added security features to the app, making it more secure against attacks!

**Link to work:** [server](https://github.com/raravi/chat-app-server)

### Day 19: 16 Feb 2020

**Today's Progress:** Chat App Client/Server: Learnt about XSS / CSRF attacks and best strategies to handle each. Implemented JWT Signing / Verification correctly. Checking Origin to prevent XSS attacks. HMAC Token is generated with increased key length for better security.

**Thoughts:** Added security features to the app!

**Link to work:**
1. [server](https://github.com/raravi/chat-app-server)
2. [client](https://github.com/raravi/chat-app-client)

### Day 20: 17 Feb 2020

**Today's Progress:** Research for a Markdown Editor App to be written in React!

**Thoughts:** No code today, only designing.

**Link to work:**

### Day 21: 18 Feb 2020

**Today's Progress:** Set up the barebones of the project. Headers were designed.

**Thoughts:** It's a start. I'm still not sure which features of a Markdown editor are feasible.

**Link to work:** [notes-client](https://github.com/raravi/notes-client)

### Day 22: 19 Feb 2020

**Today's Progress:** Had to refactor the code completely to handle word pairs matching.

**Thoughts:** A challenging project, I'm rewriting how browser handles default behaviour in contentEditable mode.

**Link to work:** [notes-client](https://github.com/raravi/notes-client)

### Day 23: 20 Feb 2020

**Today's Progress:** Added functionality to handle Headers/Lists/Quotes. DRYed the code.

**Thoughts:** Lots of bugs squashed!

**Link to work:** [notes-client](https://github.com/raravi/notes-client)

### Day 24: 21 Feb 2020

**Today's Progress:** Added italics, strikethrough, code, underline pairs! Moved code to Pairs/Headers module.

**Thoughts:** Good progress today.

**Link to work:** [notes-client](https://github.com/raravi/notes-client)

### Day 25: 22 Feb 2020

**Today's Progress:** Modified names of Pairs/Headers for better readability. Fixed 'Backspace on empty line' issue.

**Thoughts:** Cleaned up code!

**Link to work:** [notes-client](https://github.com/raravi/notes-client)

### Day 26: 24 Feb 2020

**Today's Progress:** Refactored code completely to fix faulty design. Eliminated a lot of unnecessary code! This raised a lot of bugs, took the whole day to fix them.

**Thoughts:** I need to write good unit tests.

**Link to work:** [notes-client](https://github.com/raravi/notes-client)

### Day 27: 25 Feb 2020

**Today's Progress:** Added Link functionality. And a bit of styling.

**Thoughts:** Nearing a stable version of the app!

**Link to work:** [notes-client](https://github.com/raravi/notes-client)

### Day 28: 26 Feb 2020

**Today's Progress:** Added fix to Ordered List to correct item numbers upon edits.

**Thoughts:** Nearing a stable version of the app!

**Link to work:** [notes-client](https://github.com/raravi/notes-client)

### Day 29: 27 Feb 2020

**Today's Progress:** Added CUT/COPY/DELETE functionality for Selected text. Fixed Ordered List numbering on text CUT.

**Thoughts:** Learning to work with browser capabilities, rather than rewriting everything!

**Link to work:** [notes-client](https://github.com/raravi/notes-client)

### Day 30: 28 Feb 2020

**Today's Progress:** Added PASTE functionality for Selected text. Fixed issue with Anchor/Focus node order. Moved Editor code to a different folder.

**Thoughts:** I think it's time to make editor look good :)

**Link to work:** [notes-client](https://github.com/raravi/notes-client)
