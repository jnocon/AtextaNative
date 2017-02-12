# AtextaNative
An Alexa Message Automation System
#####[Trello Board](https://trello.com/b/lu2jmbQp/alexa-flexa)

### wireframes


---
## List of Resources

### Awesome Lists
* [Awesome Redux](https://github.com/xgrommx/awesome-redux)
* [Awesome React-Native](https://github.com/jondot/awesome-react-native)

### File Structure
* [A Better File Structure For React/Redux Applications](https://marmelab.com/blog/2015/12/17/react-directory-structure.html)

### Official Docs
* [Redux](http://redux.js.org/)
* [react-native](https://facebook.github.io/react-native/)
* [Sequelize](http://docs.sequelizejs.com/en/v3/)
* [Express 4](http://expressjs.com/en/4x/api.html)
* [Webpack 2](https://webpack.js.org/configuration/)
* [Lodash](https://lodash.com/docs/4.17.4)
* [ESLint](http://eslint.org/)

### Unofficial Doc
* [Native-Code-Sharing](https://differential.com/insights/sharing-code-between-android-and-ios-in-react-native/)

## Git Notes

#### Commits
  * [prog] - progress on specific feature has been made
  * [feat] - implementation of specific feature
  * [fix] - fixing bugs 
  * [style] - styling changes
  * [setup] - changes to readme,gitignore,package.json, webpack
  * [refactor] - code does the same thing but it is better code

#### Useful commands
* **Adding upstream:** git remote add [upstream] 
* **Rebasing:** git pull --rebase [upstream] master
* **Delete local branch:** git branch -d [branchName]

#### Testing Links
* **Mocha:** https://mochajs.org/
* **Chai:** http://chaijs.com/api/
* **SuperTest:** https://github.com/visionmedia/supertest
* **SuperAgent:** https://github.com/visionmedia/superagent
* **Sinon:** http://sinonjs.org/


## Ignite 

### :arrow_forward: How to Run App

1. cd to the repo
2. Run Build for either OS
  * for iOS
    * run `react-native run-ios`
  * for Android
    * Run Genymotion
    * run `react-native run-android`

### :no_entry_sign: Standard Compliant

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)
This project adheres to Standard.  Our CI enforces this, so we suggest you enable linting to keep your project compliant during development.

**To Lint on Commit**

This is implemented using [ghooks](https://github.com/gtramontina/ghooks). There is no additional setup needed.

**Bypass Lint**

If you have to bypass lint for a special commit that you will come back and clean (pushing something to a branch etc.) then you can bypass git hooks with adding `--no-verify` to your commit command.

**Understanding Linting Errors**

The linting rules are from JS Standard and React-Standard.  [Regular JS errors can be found with descriptions here](http://eslint.org/docs/rules/), while [React errors and descriptions can be found here](https://github.com/yannickcr/eslint-plugin-react).

### :closed_lock_with_key: Secrets

This project uses [react-native-config](https://github.com/luggit/react-native-config) to expose config variables to your javascript code in React Native. You can store API keys
and other sensitive information in a `.env` file:

```
API_URL=https://myapi.com
GOOGLE_MAPS_API_KEY=abcdefgh
```

and access them from React Native like so:

```
import Secrets from 'react-native-config'

Secrets.API_URL  // 'https://myapi.com'
Secrets.GOOGLE_MAPS_API_KEY  // 'abcdefgh'
```

The `.env` file is ignored by git keeping those secrets out of your repo.

### :open_file_folder: Related Articles
Ignite Documentation - [Ignite Wiki https://github.com/infinitered/ignite/wiki](https://github.com/infinitered/ignite/wiki)
