Calculator
---

This is a clone of iOS calculator app. But we have some few bugs that needs to be fixed.


Install
---

`npm install`



Usage
---

`npm start`

Instruction
---
Kindly fork from the `master` branch. You are expected to fix the bugs outlined below.
Each bug fix should be done in separate branches and pushed to this repo.
For example: after cloning this repo, to fix a task, I'll 
- checkout to the master branch: `git checkout master`. 
- Then create a branch with your name for this speficic bug fix: `git checkout -b your_name_handle_click`. This branch will contain the fixes for this bug.

How to Submit
---
- Push the fixes in your local `your_name_handle_click` branch to this remote repo: `git push origin your_name_handle_click`
- Create Pull Request(PR) and point it master.
- Don't forget to include detailed commit message on how you resolve the bug.

Bugs
---
- For unknown reasons, `handleClick()` in `src/component/App.js` is not being fired. The buttons are not working.
- `src/logic/isNumber.js` is not matching number properly. There seem to be a problem with the regex
- The `AC` button does not work. It throws an error when clicked twice. It is supposed to reset everything.
- Any other fixes or improvements you feel you can make to this project. This is optional, feel free to skip if you don't want to.

Please make sure the tests are passing by running `npm test`
