## Step 9: Run the app as JavaScript

In this step, you compile the app to JavaScript and
run it in the modern browser of your choice.

_**Keywords**: dart2js, minification_

Once you're ready to test your app in a non-Dartium browser,
you need to compile your app to JavaScript.
Before deploying your app, you also need to minify its JavaScript.

**Note:** AngularDart currently produces large JavaScript.
_[PENDING: perhaps explain more, definitely link to bugs to follow]_

### Run the app as JavaScript.

**&rarr; In Dart Editor, right-click the HTML file and choose Run as JavaScript.**

For example, go to **web/8-filter/piratebadge.html**,
right-click it, and choose **Run as JavaScript**.

![screenshot of Dart Editor](img/runAsJs.png)

At the lower right of Dart Editor is a progress bar
telling you the status of the build,
which might take up to a minute.
_[PENDING: time this.]_
You might also see many warnings in an Output pane;
as long as your app eventually comes up,
you can ignore the warnings.

Once Dart Editor compiles your file,
it brings up the app in your default browser
(for example, Chrome).


### Run the app in another browser.

Copy the app's URL from your default browser,
and paste it into another browser,
such as Safari or Firefox.

### Minify the JavaScript

This step is necessary because `pub build`
doesn't yet work with the code lab samples.
(The `pub build` command automatically minifies the JavaScript.)
The section has a workaround.

<b> &rarr; In Dart Editor, _[PENDING: instructions for modifying the launch to specify --minify]_ </b>


_[PENDING: link to what they should do now]_

## [Home](../README.md) | [< Previous](step-8.md)
