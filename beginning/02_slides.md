<!SLIDE>
# What is PhoneGap? #

<!SLIDE center>
# Develop native apps with HTML/CSS/JS #
![Features](what_is_it.png)

<!SLIDE center>
# Wrap your app, deploy anywhere #
![Features](chart.png)

<!SLIDE center>
# Access to Native Phone Features #
![Features](features.png)

<!SLIDE center>
# PhoneGap Build will build the app for you #
![Features](pgbuild.png)

<!SLIDE center>
# Used for real apps #
![Features](real_apps.png)

<!SLIDE>
# Is as simple as making a one-page web app #

    <html>
      <body>
        Hello world
      </body>
    </html>

<!SLIDE>
# Native phone features are exposed through a Javascript library #

    // find all Bobs
    var options = new ContactFindOptions();
    options.filter="Bob";
    options.multiple=true; 
    var fields = ["displayName", "name"];
    navigator.contacts.find(fields, onSuccess, onError, options);

<!SLIDE>
# Sounds great in theory, but what about in practice? #

!SLIDE bullets incremental
# Once Upon a Time... #

* a client had an idea...
* to replace paper-based inspection forms...
* with a mobile app...
* that gathered data & pictures for remote inspectors.

!SLIDE bullets incremental
# In Walks the Hero #

* A developer with lots of web app experience...
* ... but no native app experience...
* says "Hey, let's use Phone Gap!"

!SLIDE bullets incremental
# Development Starts #

* Developer sets up everything he knows...
* Rails "RESTful" web backend...
* Coffeescript, HAML compilers...
* Backbone.JS, Jasmine tests...
* JQuery Mobile BETA...

<!SLIDE center>
# He Declares... #
# This Will Work! #
![Features](king.png)

<!SLIDE center>
# But It Doesn't Work #
# The App Sinks #
# He's Fired #
![Features](vertical.png)

!SLIDE bullets incremental
# Issues with the app included #

* iPhone version was unresponsive.
* Android version was responsive... but only in airplane mode and with 20 seconds of lag between clicks.
* Could not take pictures.
* Could not sync data to and from the central server.

!SLIDE bullets incremental
# Issues with the app included #

* Unexpected app crashes.
* Sudden blank pages.
* Weird page zooming.
* Caused uncontrollable bursts of anger from users.

!SLIDE bullets incremental
# I am asked to rescue the app #

* Evaluation process to judge if app was salvagable.
* Switch to week-by-week iterations to show progress.
* Direct contact with all parties for feedback & testing.
* Months and months of fixes & rework.

!SLIDE bullets incremental
# Project Enters Pilot #

!SLIDE bullets incremental
# Let's Go Back #

* For all of the promises of PhoneGap, what happened?

<!SLIDE center>
# Develop native apps with HTML/CSS/JS #
![Features](what_is_it.png)

!SLIDE bullets incremental
# On really? #

* Design/Dev techniques from desktop web did not work on mobile.
* The app was incredibly slow.
* It did not behave like a native app.

<!SLIDE center>
# Wrap your app, deploy anywhere #
![Features](chart.png)

!SLIDE bullets incremental
# Oh really? #

* App looked different for each device.
* Android support was very spotty.
* Performance issues dogged the app, especially on Android.

<!SLIDE center>
# Access to Native Phone Features #
![Features](features.png)


!SLIDE bullets incremental
# Oh really? #

* iPhone support was pretty good, but...
* Android camera support was very spotty.
* Had issues with file-access support across different devices.

<!SLIDE center>
# Still fighting this... #
![Features](text_message.png)

<!SLIDE center>
# PhoneGap Build will build the app for you #
![Features](pgbuild.png)

!SLIDE bullets incremental
# Oh really? #

* We used PhoneGap Build for a while, but...
* Once we required SSL for logins, we had to switch to using XCode to produce builds.

<!SLIDE center>
# Used for real apps #
![Features](real_apps.png)

!SLIDE bullets incremental
# Yes! #

* Despite the issues, we were still able to make it work.
* Have to learn how to play to PhoneGap's strengths and avoid the weaknesses.

!SLIDE bullets
# Tip #1 #

* Acknowledge that smartphones are nowhere near as powerful as desktops.

!SLIDE bullets
# Tip #2 #

* Avoid use of heavy frameworks.
* (Backbone.js, Knockout, etc.)

!SLIDE bullets
# Tip #3 #

##Avoid "fancy" CSS or advanced rendering.

!SLIDE
# Tip #4 #

##A fast response to a slow process beats a slow response to a fast process.

!SLIDE
# For example #

What's faster than calling 

    methodThatTakesFiveSeconds()?

A call that takes 250 milliseconds more:

    $.mobile.showPageLoadingMsg() 

    setTimeout((()-> methodThatTakesFiveSeconds()), 250)

!SLIDE bullets
# Tip #5 #

* Do not expect the screen to update just because you updated the DOM.

!SLIDE bullets
# Tip #6 #

* Avoid DOM manipulation as much as possible.

!SLIDE bullets
# Tip #7 #

* Test on actual mobile devices daily.

!SLIDE bullets
# Tip #8 #

* Early in development, find out how to disable every mobile-web browser feature.

!SLIDE bullets
# Tip #9 #

* Don't try to pull in your views from the web dynamically.

!SLIDE bullets
# Tip #10 #

* Don't test through the view.


!SLIDE bullets
# Tip #10 #

* Adjust your attitude.

!SLIDE bullets incremental
# Attitude... #

* If you are drawn to PhoneGap as a way to leverage your web skills for native devices... 
* ... especially because you think you’re a HTML/CSS/JS wizard/guru/ninja/rockstar...
* ... you’ll fall harder than the rest.

!SLIDE bullets incremental
# Attitude... #

* If you look at PhoneGap as a cost-effective way to create a simple app...
* ... you’ll have a better experience with PhoneGap.

!SLIDE bullets incremental
# Attitude... #

* If you look at PhoneGap as something not to be trusted...
* ... as a technology that provides a passable mobile experience...
* ... and if you are keep your client's expectations realistic... 
* ... you just might be successful with PhoneGap.

!SLIDE bullets incremental
# How Would I Start a New PhoneGap App Today? #

* Buy the front-end from a professional mobile designer.
* Stick with straight-up HTML/CSS/JQuery, with no framework.
* No JQuery Mobile.

!SLIDE bullets incremental
# How Would I Start a New PhoneGap App Today? #

* Use Coffeescript to produce more consistent Javascript.
* Keep the app simple to avoid Android device compatibility issues.

!SLIDE bullets incremental
# How Would I Start a New PhoneGap App Today? #

* Promise little, deliver more.
* Push the client away from complexity or features that won't work well.

!SLIDE bullets incremental
# Bigger Picture #

* PhoneGap is not the sole reason things did start well.
* Constant iterations with regular feedback was the biggest issue.
* PhoneGap took us farther than we could have gone on our own, in the present time.

<!SLIDE center>
# If it doesn't fit, it doesn't fit #
![Features](squarepegroundhole.jpg)

!SLIDE bullets
# Thanks #

* Darren Cauthon
* @darrencauthon
* github.com/darrencauthon
