I have issues running this app in production mode on android 10 devices.

### Repro

- checkout this repo
- use node ~10.21.0
- yarn
- expo start --no-dev
- open the app in production mode on an android 10 device with latest expo (from store, 2.16.1 at the time)
- open the app in production mode on an android 10 device with older expo (2.15.0, https://d1ahtucjixef4r.cloudfront.net/Exponent-2.15.0.apk)

For me,

- in dev mode it runs on both expo app
- in prod mode it runs only with the older

If the app runs properly, you should see the text 'If you see this, the app is working properly.'
