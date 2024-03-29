# 📖 Use Workbox to Generate a Service Worker

* As an app user, I want to be able to precache assets and view my app even when offline.

## Acceptance Criteria

* It’s done when logic is added to the `index.js` to register a service worker.

* It's done when the `webpack.config.js` file is updated to use the GenerateSW class of the workbox webpack plugin.

* It’s done when the app is started using `npm install` and `npm run start:dev` and a log from GenerateSW appears in the console with a message similar to the following: `“The service worker at service-worker.js will precache 5 URLs, totaling 35.1 kB.”`

* It’s done when a `service-worker.js` file is generated in the build directory.

* It’s done when the service worker is active and the app is still visible even when offline.

## 📝 Notes

Refer to the documentation:

* [Workbox docs on generating a service worker with webpack using GenerateSW](https://developers.google.com/web/tools/workbox/guides/generate-service-worker/webpack)

* [Workbox docs on GenerateSW](https://developer.chrome.com/docs/workbox/reference/workbox-webpack-plugin/#type-GenerateSW)

* [Simulate offline behavior with Chrome DevTools](https://developer.chrome.com/docs/devtools/network/reference/#offline)

* [Interact with service workers with Chrome DevTools](https://developer.chrome.com/docs/workbox/improving-development-experience/#service-worker-development-aids)

## 💡 Hints

* How can we use Chrome DevTools to test if our service worker is active and our app is still visible even when offline?

## 🏆 Bonus

If you have completed this activity, work through the following challenge with your partner to further your knowledge:

* Why don't JavaScript modules work inside service workers?

Use [Google](https://www.google.com) or another search engine to research this.

---
© 2024 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
