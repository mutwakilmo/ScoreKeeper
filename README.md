# ScoreKeeper

## Summary

-   `Drawable`  elements enhance the look of an app's UI.
-   A  [`ShapeDrawable`](https://developer.android.com/reference/android/graphics/drawable/ShapeDrawable.html)  is a primitive geometric shape defined in an XML file. The attributes that define a  `ShapeDrawable`  include color, shape, padding, and more.
-   The Android platform supplies a large collection of styles and themes.
-   Using styles can reduce the amount of code needed for your UI components.
-   A  `style`  can specify common properties such as height, padding, font color, font size, and background color.
-   A  `style`  should not include layout-related information.
-   A  `style`  can be applied to a  `View`,  `Activity`, or the entire app. A  `style`  applied to an  `Activity`  or the entire app must be defined in the  `AndroidManifest.xml`  file.
-   To inherit a style, a new style identifies a  `parent`  attribute in the XML.
-   When you apply a  `style`  to a collection of  `View`  elements in an activity or in your entire app, that is known as a  _theme_.
-   To apply a theme, you use the  `android:theme`  attribute.
