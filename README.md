
{
  "manifest_version": 2,
  "name": "Kanye West",
  "version": "0.1.2",
  "author": "Sam Lanning <sam@samlanning.com>",

  "description": "Kanye West lmao.",
  "icons": {
    "16": "images/icon16.png",
    "32": "images/icon32.png",
    "48": "images/icon48.png",
    "128": "images/icon128.png"
  },

  "app": {
    "background": {
      "scripts": ["background.js"]
    }
  },
  "permissions": [
    "storage",
    "webview",
    "audioCapture",
    "videoCapture",
    "fullscreen",
    "pointerLock",
    "http://*/*",
    "https://*/*"
    ]
}
