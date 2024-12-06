# has-types <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][11]][1]

Does the given package have TypeScript types?

## Example

```mjs
import hasTypes from 'has-types';
import assert from 'assert';

hasTypes('has-types').then(x => assert.equal(x, true));
hasTypes('react@19').then(x => assert.equal(x, '@types/react'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/has-types
[npm-version-svg]: https://versionbadg.es/inspect-js/has-types.svg
[deps-svg]: https://david-dm.org/inspect-js/has-types.svg
[deps-url]: https://david-dm.org/inspect-js/has-types
[dev-deps-svg]: https://david-dm.org/inspect-js/has-types/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/has-types#info=devDependencies
[license-image]: https://img.shields.io/npm/l/has-types.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/has-types.svg
[downloads-url]: https://npm-stat.com/charts.html?package=has-types
[codecov-image]: https://codecov.io/gh/inspect-js/has-types/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/has-types/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/has-types
[actions-url]: https://github.com/inspect-js/has-types/actions
