## Step 9: Build the app and run as JavaScript

In this step, you compile the app to JavaScript and
run it in the modern browser of your choice.

_**Keywords**: dart2js, minification_

Once you're ready to test your app in a non-Dartium browser,
you need to compile your app to JavaScript.
Before deploying your app, you also need to minify its JavaScript.

**Note:** AngularDart currently produces large JavaScript.
[PENDING: perhaps explain more, definitely link to bugs to follow]

### Run the app as JavaScript.

**&rarr; In Dart Editor, right-click the HTML file and choose Run as JavaScript.**

[PENDING: say what you should see.]

![screenshot of Dart Editor](/img/runAsJS.png)

**&rarr; Run the app in another browser.**

### Minify the JavaScript

If you used `pub build`, your JavaScript would already be minified.
Unfortunately, that doesn't work (yet).
Here's a workaround.

**&rarr; In Dart Editor, [PENDING: instructions for modifying the launch to specify --minify]


### Learn more about
 - [Introducing Filters](https://angulardart.org/tutorial/07-ch05-filter-service.html)

### Problems?
[PENDING: resources]

## [Home](../README.md) | [< Previous](step-8.md)
