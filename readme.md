# eslint-config-rndmem
The rndmem ESLint configuration.

## Changelog

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
© 2016 Stephen Niedzielski

This program is free software: you can redistribute it and/or modify it
under the terms of the GNU General Public License as published by the
Free Software Foundation, version 3 of the License.

This program is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General
Public License for more details.

You should have received a copy of the GNU General Public License along
with this program.  If not, see <http://www.gnu.org/licenses/>.