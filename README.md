# system-alert-window-example-kotlin
Kotlin version of this project: [noln/system-alert-window-example](https://github.com/noln/system-alert-window-example)

Behaviour is identical to the original project, the only differences are a few idiomatic syntax changes e.g. instead of `if (blah == null) ..`, `blah?.let{..}` is used.

**Note:** As with the original project, this mechanism for displaying Views over the top of other applicatons is deprecated and will not be supported in future versions of Android.

For more info on that, see the note and link to the presentation in the original, java-based project's [README](https://github.com/noln/system-alert-window-example/blob/master/README.md).