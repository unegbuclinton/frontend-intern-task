Calculator
---

This is a clone of iOS calculator app. But we have some few bugs we need to be fixed.


Install
---

`npm install`



Usage
---

`npm start`


Bugs
---

Kindly fork from the `master` branch for each of the bugs you will be fixing. Each bug fixed has to have its own branch. 

Then create a merge request for each. Give detailed commit message on how you resolve each of them.

- For unknown reasons, `handleClick()` in `src/component/App.js` is not being fired. The buttons are not working.
- `src/logic/isNumber.js` is not matching number properly. There seem to be a problem with the regex
- The `AC` button does not work. It throws an error when clicked twice. It is supposed to reset everything.
- Any other fixes or improvements you feel you can make to this project.

Please make sure the tests are passing by running `npm test`