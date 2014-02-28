**THIS IS A DRAFT.**
[Please report any issues you find.](https://github.com/angular/ng-darrrt-codelab/issues)


## Step 9: Run the app as JavaScript

In this step, you compile the app to JavaScript and
run it in the modern browser of your choice.

_**Keywords**: dart2js, minification_

Once you're ready to test your app in a non-Dartium browser,
you need to compile your app to JavaScript.
Before deploying your app, you might also want to minify its JavaScript.

**Note:** Compiling AngularDart apps to JavaScript currently results in large files.
See [issue 476](https://github.com/angular/angular.dart/issues/476) for details.


### Run the app as JavaScript.

**&rarr; In Dart Editor, right-click the HTML file and choose Run as JavaScript.**

For example, go to **web/8-filter/piratebadge.html**,
right-click it, and choose **Run as JavaScript**.

![screenshot of Dart Editor](img/runAsJs.png)

At the lower right of Dart Editor is a progress bar
telling you the status of the build,
which might take 15 or 20 seconds.
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

### Minify the JavaScript.

To reduce the size of the generated JavaScript by half or more,
you can _minify_ it,
removing all unnecessary characters from the JavaScript.
The best way to minify JavaScript produced from Dart is to use
the dart2js compiler's `--minify` option.
Although the `pub build` command
automatically minifies,
unfortunately `pub build`
doesn't yet work with the code lab samples.
One workaround, which this section describes,
is to specify dart2js options to Dart Editor.

<b> &rarr; In Dart Editor's menu, choose Run > Manage Launches. </b>

Alternatively, click the little arrow to the right of the Run button,
and then choose **Manage Launches**.

<b> &rarr; Choose the JavaScript launch configuration. </b>

Click the launch configuration to choose it.
The launch configuration should have a gray world icon,
and its target should be the HTML file for the app.

If you can't decide on the right launch configuration,
try this trick:
Delete all the launch configurations
that you didn't explicitly create or edit
(select them all, and click the red X).
Then run the app as JavaScript again,
and return to this dialog.
Now click the only launch configuration in the list.

<b> &rarr; Add the --minify compiler flag. </b>

Add **--minify** to the **Dart2js settings** section's **Compiler flags** field.

![screenshot of Dart Editor's Manage Launches dialog](img/manageLaunches.png)

<b> &rarr; Click the Run button. </b>

Like before, you'll see a status message.
Soon, the app will appear in your default browser.


## What next?

Try the [AngularDart Tutorial](https://angulardart.org/tutorial/).


## [Home](../README.md) | [< Previous](step-8.md)
