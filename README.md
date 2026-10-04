# yukmmz.github.io

Portfolio site listing small browser-based web apps. Published via GitHub Pages
(user page) at **https://yukmmz.github.io/**.

Single static `index.html`, no build step. To add a new app, add a `<article class="card">`
block in `index.html`.

## Apps listed

The list of apps is the site itself: see **https://yukmmz.github.io/** (each card links to the app and its
source). It is not repeated here, so adding an app only means adding its card to `index.html`.

## New-app suggestions (FB)

The **FB** button (top right) and the "Suggest an app" panel under the cards open a form for
suggesting new apps. It posts to the same feedback receiver as the FB button in each app
(`apps-operator/scripts/feedback-gas/`), with `app: "portal"`. Feedback on an existing app is
meant to go through that app's own FB button. Nothing is sent unless the visitor presses Send.
