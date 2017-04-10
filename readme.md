# eslint-config-rndmem
The rndmem ESLint ECMAScript 2015 configuration

## Changelog

### v9.0.3
- Update: [no-underscore-dangle](http://eslint.org/docs/rules/no-underscore-dangle):
  permit pre and postfix underscores
- Update: [mocha/no-synchronous-test](https://github.com/lo1tuma/eslint-plugin-mocha/blob/master/docs/rules/no-synchronous-tests.md):
  permit synchronous Mocha tests

### v9.0.2
- Chore: upgrade to rndmem-npm-skeleton v0.2.5 template

### v9.0.1
- Chore: upgrade dependencies

### v9.0.0
- Breaking: add html, import, mocha, and objects plugins
- Breaking: remove node env
- Breaking: upgrade dependencies
  - New [no-compare-neg-zero](http://eslint.org/docs/rules/no-compare-neg-zero):
    forbid comparisons to -0
  - New [nonblock-statement-body-position]
    (http://eslint.org/docs/rules/nonblock-statement-body-position): require
    single line if, else, while, do-while, and for statements when not using a
    block statement

### v8.0.0
- Breaking: upgrade dependencies
  - New [no-multi-assign](http://eslint.org/docs/rules/no-multi-assign): forbid
    multiple assignments within a statements
  - New [prefer-promise-reject-errors](http://eslint.org/docs/rules/prefer-promise-reject-errors):
    require Error type when rejecting a Promise
  - New [template-tag-spacing](http://eslint.org/docs/rules/template-tag-spacing):
    forbid spacing in tagged template literals
  - Update [object-shorthand](http://eslint.org/docs/rules/object-shorthand):
    require methods over arrow function properties
  - Update [no-use-before-define](http://eslint.org/docs/rules/no-use-before-define):
    require outer scoped variables to be defined as read top to bottom before use
- Breaking: forbid redundant [radix](http://eslint.org/docs/rules/radix)
  parameter in parseInt() since this library is ES6+
- Update: promote [func-style](http://eslint.org/docs/rules/func-style)
  violations to error
- Update: demote [strict](http://eslint.org/docs/rules/strict) mode violations
  to warning
- Chore: use NPM package main entry instead of dummy index.js

### v7.0.0
- Breaking: [indent](http://eslint.org/docs/rules/indent)
  require case clauses to be indented WRT switch statements

### v6.0.0
- Breaking: [func-style](http://eslint.org/docs/rules/func-style)
  require the use of function expressions instead of declarations

### v5.0.0
- Breaking: add rules to forbid duplicate, limitless, and unused disable ESLint
  directive comments

### v4.0.1
- Update: disable
  [class-methods-use-this](http://eslint.org/docs/rules/class-methods-use-this)
  and [no-continue](http://eslint.org/docs/rules/no-continue)

### v4.0.0
- Breaking: upgrade dependencies and three new rules:
  [capitalized-comments](http://eslint.org/docs/rules/capitalized-comments),
  [no-await-in-loop](http://eslint.org/docs/rules/no-await-in-loop),
  [require-await](http://eslint.org/docs/rules/require-await)

### v3.0.1
- Update: add some common base 2 and base 10 magic numbers to the ignore list

### v3.0.0
- Breaking: upgrade dependencies

### v2.0.0
- Require @param, not @arg, JSDoc method parameter annotations for VS Code's
  IntelliSense
- Fix peerDependencies

### v1.0.4
- Update: workaround JSPM peerDependencies

### v1.0.3
- Update: allow imports and exports

### v1.0.2
- Update: use NPM engine property to detect unsupported JavaScript features

### v1.0.1
- Update: limit [one-var](http://eslint.org/docs/rules/one-var) to only vars,
  not let and const
- Update: upgrade to ESLint v3.9.1 and eslint-plugin-node v3.0.3

### v1.0.0
- New: initial release

## License (GPLv3)
© 2017 Stephen Niedzielski

This program is free software: you can redistribute it and/or modify it
under the terms of the GNU General Public License as published by the
Free Software Foundation, version 3 of the License.

This program is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General
Public License for more details.

You should have received a copy of the GNU General Public License along
with this program.  If not, see <http://www.gnu.org/licenses/>.