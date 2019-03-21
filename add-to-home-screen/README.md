Google Codelabs: Add Your Web App to a User's Home Screen
=========================================================

https://codelabs.developers.google.com/codelabs/add-to-home-screen/index.html

Original GitHub: https://github.com/googlecodelabs/add-to-home-screen


## memo

Step 3:

> The [Web App Manifest specification](https://www.w3.org/TR/2016/WD-appmanifest-20160331) provides only general instructions for using these. The `name` member is intended for locations where a typical user would see the name, such as on the web app's add to home screen banner and on its splash screen. The `short_name` member is intended to be used in places without enough room for the full name of the web application. But Chrome uses the `short_name` when both are present, but will use either if only one is present. Other browsers may behave differently.

Step 4:

https://manifest-validator.appspot.com/

Step 6:

> Note: Do not move this to your `/js` folder. For a service worker to work on a whole site, it has to be in the site root.
