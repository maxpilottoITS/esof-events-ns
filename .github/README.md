# esof-events-ns
ESOF Events app made with Nativescript

## Requirements
* Node.js
* Nativescript CLI
* Xcode
* Homebrew

## Run
* `npm install`
* `npm run iphone` or `npm run iphoneX`

## Maps API Key
You need to provide your own api key, create a `config.js` file in your project root

```javascript
module.exports = {
    "google": {
        "map": {
            "api": "YOUR_KEY_HERE"
        }
    }
}
```
