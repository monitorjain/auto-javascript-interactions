# auto-javascript-interactions
This is a javascript project that enables auto tracking and collection of user actions and interactions and adds it to New Relic Browser Agent Service as dynamically collected analytics

# Auto user actions library setup
The user actions library is stored in a secured S3 bucket at this location: https://auto-instrumentation.s3.amazonaws.com/auto-user.min.js

To add this library to your Angular or React Project, simply add the following to your project (Index.html in Angular or equivalent in React)
![Image](https://user-images.githubusercontent.com/45892212/98804327-2624a080-246a-11eb-8a42-c7d428c96b0b.png)

Once the library has been added as prescribed in the image above, simply exercise the Angular or React app to generate enough events.

The auto instrumentation library current supports:
* Scroll tracking X and Y axis
* clicks on links and interactive elements
* double clicks
* Full screens and screen resizes
* Keyboard events
* Input actions

Note:
If you want to add more event tracking, simply fork the project or create an issue. 
