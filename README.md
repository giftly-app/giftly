<p align="center">
  <a href="https://giftly.app">
    <img src="https://cdn.itwcreativeworks.com/assets/giftly/images/logo/giftly-brandmark-black-x.svg" width="100px">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/github/package-json/v/giftly/giftly.svg">
  <br>
  <img src="https://img.shields.io/librariesio/release/npm/giftly.svg">
  <img src="https://img.shields.io/bundlephobia/min/giftly.svg">
  <img src="https://img.shields.io/codeclimate/maintainability-percentage/giftly/giftly.svg">
  <img src="https://img.shields.io/npm/dm/giftly.svg">
  <img src="https://img.shields.io/node/v/giftly.svg">
  <img src="https://img.shields.io/website/https/giftly.app.svg">
  <img src="https://img.shields.io/github/license/giftly/giftly.svg">
  <img src="https://img.shields.io/github/contributors/giftly/giftly.svg">
  <img src="https://img.shields.io/github/last-commit/giftly/giftly.svg">
  <br>
  <br>
  <a href="https://giftly.app">Site</a> | <a href="https://www.npmjs.com/package/giftly">NPM Module</a> | <a href="https://github.com/giftly/giftly">GitHub Repo</a>
  <br>
  <br>
  <strong>giftly</strong> is the official npm module of <a href="https://giftly.app">Giftly</a>, a free gift idea generator app for any occasion!
</p>

## 🌐 Giftly Works in Node AND browser environments
Yes, this module works in both Node and browser environments, including compatibility with [Webpack](https://www.npmjs.com/package/webpack) and [Browserify](https://www.npmjs.com/package/browserify)!

## 🦄 Features
* Getting proxy lists

### 🔑 Getting an API key
You can use so much of `giftly` for free, but if you want to do some advanced stuff, you'll need an API key. You can get one by [signing up for a Giftly account](https://giftly.app/signup).

## 📦 Install Giftly
### Option 1: Install via npm
Install with npm if you plan to use `giftly` in a Node project or in the browser.
```shell
npm install giftly
```
If you plan to use `giftly` in a browser environment, you will probably need to use [Webpack](https://www.npmjs.com/package/webpack), [Browserify](https://www.npmjs.com/package/browserify), or a similar service to compile it.

```js
const giftly = new (require('giftly'))({
  // Not required, but having one removes limits (get your key at https://giftly.app).
  apiKey: 'api_test_key'
});
```

### Option 2: Install via CDN
Install with CDN if you plan to use Giftly only in a browser environment.
```html
<script src="https://cdn.jsdelivr.net/npm/giftly@latest/dist/index.min.js"></script>
<script type="text/javascript">
  var giftly = new Giftly({
    // Not required, but having one removes limits (get your key at https://giftly.app).
    apiKey: 'api_test_Key'
  });
</script>
```

### Option 3: Use without installation
You can use `giftly` in a variety of ways that require no installation, such as `curl` in terminal/shell. See the **Use without installation** section below.

## ⚡️ Using Giftly
After you have followed the install step, you can start using `giftly` to get gift ideas for any occasion!

For a more in-depth documentation of this library and the Giftly service, please visit the official Giftly website.

## 🔧 Use without installation
### Use Giftly with `curl`
```shell
# Standard
curl -X POST https://api.giftly.app
```

## 📝 What Can Giftly do?
Giftly is a [free gift idea generator](https://giftly.app) app for any occasion!

## 🗨️ Final Words
If you are still having difficulty, we would love for you to post
a question to [the Giftly issues page](https://github.com/giftly/giftly/issues). It is much easier to answer questions that include your code and relevant files! So if you can provide them, we'd be extremely grateful (and more likely to help you find the answer!)

## 📚 Projects Using this Library
* coming soon!

Ask us to have your project listed! :)
