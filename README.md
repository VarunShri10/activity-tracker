# Browser Activity Tracker

## Use it
- Open `index.html` in Chrome or another modern browser.
- Add activities on any date and time, choose 1-day/2-day reminders, and mark items complete.
- Data is saved in that browser's local storage on that device.

## Install on Android
1. Host the folder on an HTTPS static host (or open the page from a supported local web server).
2. On OnePlus 13, open the site in Chrome.
3. Chrome menu (⋮) > **Add to Home screen** or **Install app**, then confirm.
4. Enable notifications from the app page if prompted.

## Important reminder limitation
This client-only version checks reminders while its page is open. Web pages cannot reliably run scheduled code after being closed, and browser notifications alone do not provide a dependable closed-app scheduler. Reliable reminders while closed require a push-notification service/backend or a native Android app. Data is local to each browser/device and is not synced.
