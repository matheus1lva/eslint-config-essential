# eslint-config-essential

Eslint must stop you from doing dumb mistakes, not to annoy you with useless rules. 

Perhaps during development, or on your project, you or someone added all recommended react, airbnb and other rules! Most of them can be solved with prettier or any other code formatting tool. These rules start to annoy the developer and create friction during development. More `//eslint-disable-next-line` or comments similar to these are added... the codebase starts to get a mess...

Eslint is made to prevent you from making mistakes, not to enforce code style that can be added automatically pre-commit. 

So this "set" of rules, are pre-selected rules that only prevent errors, dumb mistakes, they are not to apply code style. We have selected all rules that are going to make your code better!

If any rule is missing, please send a PR and we are going to add them!


**DISABLE THEM ALL!!!!!**

## Install
```sh
$ npm install eslint-config-essential --save-dev
```


## Usage
edit your eslint config file and add:

```json
{
  "extends": "essential"
}
```

If you want to use new features, you must install a parser. What i mean by that: `babel-eslint` or `ts-lint`, this gives the ability to 
parse new features of ecmascript to be used by eslint. So eslint is able to understand it.

This config should be used just as an extension, not as a main rule.

