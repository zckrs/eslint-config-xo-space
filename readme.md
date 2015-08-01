# eslint-config-xo-space [![Build Status](https://travis-ci.org/sindresorhus/eslint-config-xo-space.svg?branch=master)](https://travis-ci.org/sindresorhus/eslint-config-xo-space)

> ESLint [shareable config](http://eslint.org/docs/developer-guide/shareable-configs.html) for [XO](https://github.com/sindresorhus/xo) with 2-space indent

This is for advanced users. You probably want to use XO directly.


## Install

```
$ npm install --save-dev eslint-config-xo-space
```


## Usage

Add some ESLint config to your `package.json`:

```json
{
	"name": "my-awesome-project",
	"eslintConfig": {
		"extends": "xo-space"
	}
}
```

Or to `.eslintrc`:

```json
{
	"extends": "xo-space"
}
```

This package also exposes [`xo-space/esnext`](esnext.js) if you want ES2015 support and rules:

```json
{
	"extends": "xo-space/esnext"
}
```

And [`xo-space/browser`](browser.js) if you're in the browser:

```json
{
	"extends": "xo-space/browser"
}
```


## Related

- [eslint-config-xo](https://github.com/sindresorhus/eslint-config-xo) - ESLint shareable config for XO
- [eslint-config-react](https://github.com/sindresorhus/eslint-config-react) - ESLint shareable config for React to be used with the above


## License

MIT © [Sindre Sorhus](http://sindresorhus.com)
