# JS211_TicTacToe[![CircleCI](https://circleci.com/gh/AustinCodingAcademy/javascript-workbook/tree/gh-pages.svg?style=svg)](https://circleci.com/gh/AustinCodingAcademy/javascript-workbook/tree/gh-pages)

![](http://en.gravatar.com/userimage/107370100/a08594145564536138dfaaf072c7b241.png)

# Austin Coding Academy

## JavaScript 211 Project: Tic, Tac, Toe

### Part 1: Tic, Tac, Toe in the terminal

1. Fork and clone [Tic, Tac, Toe Repo](https://github.com/AustinCodingAcademy/JS211_TicTacToeProject.git)
1. Ensure you have installed all dependencies/packages: `npm i`
1. Open `main.js` and look at the Unit Test, see what is being called, passed as input arguments, and what the expected results are.
1. Ensure you know how to run the unit test:
    * `npm test main.js` + `ctrl + c` to escape.
1. Use a whiteboard to work out a solution. HOW DOES TIC, TAC, TOE actually work in excruciating detail?
1. Translate the broad ideas to pseudo code
1. Convert the pseudo code to real JavaScript Code
1. Add the the JavaScript code you've come up with one step at a time in `main.js`
1. Work through your bugs.
1. Use `node main.js` to run the game + `ctrl + c` to escape.
1. Achieve green checks for each of your unit tests.
1. Bonus Challenge: Since the game can only be won with three marks in a row, the minimum amount of marks required for a possible win is 5. There is no reason to run `checkForWin()` for marks 1-4. Adjust the program to only run `checkForwin()` after at least 5 moves have been made.

#### Part 2: Use the DOM to build a GUI for your game

1. Open `index.html` to find a pre-built 3x3 grid using `<td>` tags (table-data)
    * This html file is styled with `tictactoe.css`
    * It also has a script tag that links it to `dom-tictactoe.js`
1. Open `dom-tictactoe.js`. You'll find starter code that helps you attach the logic from part 1 to the DOM so a user can use the screen instead of the terminal to play the game.
1. Follow the instructions at the top of the js file to find the `@Todo`s and place your code in the appropriate place to make the game work!

#### Part 3: Build It from Scratch

1. Push Yourself Further
1. Create a new repo in GitHub, clone it
1. Create an `index.html` file.
1. Create a `tictactoe-styles.css` file
1. Create a `tictactoe-scripts.js` file
1. Build your game working through each little step one must complete to do it.

*This is where you get good!*

#### Hints

1. Run your unit tests first!!
1. Use [repl.it](https://www.repl.it) to write the solution code first. (it's a faster environment vs using the `node main.js` command over and over again.)
1. Read the comments in `main.js`
1. Use the [JS Docs at W3S on Accessing the First Array Element](https://www.w3schools.com/js/js_arrays.asp)
1. Push yourself further.
1. Look at your hints!
1. Don't skip the planning portion!!
1. **Clone, setup, testing, and running instructions for all projects is below**

******

## Cloning Your Project

1. Click the 'Fork' button (choose your account if prompted).
1. Copy HTTPS URL from your forked repository
1. In your terminal/gitBash/CommandPrompt navigate (using `cd`) into a directory where you want to start keeping your repositories. (`/jsDevFolder`)
1. Clone your new repository by typing `git clone <forked clone URL>` (the HTTPS
URL you copied above)
  ![Forking a repository](https://docs.google.com/drawings/d/1tYsLHaLo8JRdp0xC1EZrAo0o9Wvv4S5AD937cokVOBk/pub?w=960&h=720)
1. Now go into the new directory by using `cd project-repo`

1. Add the base repository as an upstream
    `git remote add upstream https://github.com/AustinCodingAcademy/<PROJECT-REPO>.git`

1. Check the configuration of your remotes with `git remote -v`, it should look
very similar to this (except it'll be YOUR username)

```bash
$ git remote -v

origin  git@github.com:username/javascript-workbook.git (fetch)
origin  git@github.com:username/javascript-workbook.git (push)
upstream    git@github.com:AustinCodingAcademy/javascript-workbook.git (fetch)
upstream    git@github.com:AustinCodingAcademy/javascript-workbook.git (push)
```

### Setup

1. From your project directory, run `npm i` to tell NPM to install all the
node modules we use in this class (see `package.json`)
1. Use your textEditor (VS Code) to change your files.
1. When you're finished `git status`, stage your file `git add .`, commit your changes `git commit -m "functions working"`, and push to
GitHub `git push`

    ```bash
    git status
    git add .
    git commit -m "Initial Commit"
    git push origin gh-pages
    ```

1. Now go to your forked repository on GitHub (at
  https://github.com/your-username/javascript-workbook). A little yellow box
  should have popped up asking you to make a Pull Request. Click to review.

1. Click "Create Pull Request"

1. Every time you make a change *and push to GitHub*, this PR will automatically
update. No need to do it more than once.

#### Get latest workbook updates

1. To get the latest code/homework/test updates, be sure to have a "clean
working directory" by committing or removing all of your changes. You check for
a "clean working environment" by running `git status` and making sure no files
show up.

1. Run `git pull upstream gh-pages`

![Contributing workflow](https://docs.google.com/drawings/d/1WeKQxOHgPKfwjy_eKtlJO62Fu4XTCWFeqkAh1oIqICM/pub?w=960&h=720)

### Running the apps

Simply run `node path/to/file.js`

example `node 01week/rockPaperScissors.js`

### Running Tests

Tests are a great way to make sure your code works the way you planned it would,
and to make sure you don't break something in the future. We will be using them
to test our understanding of the lesson. It's also our main way to assign grades
for an assignment.

To run the tests on a file run `npm test path/to/file.js`, etc.

### Running the Linter

Simply run `npm run lint`

#### Running the Server

1. Run `npm start`
1. To break out of the server, press `ctrl` + `c`

//Just created Repo 