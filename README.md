# Setting up iOS project

When starting up working on a fresh project you always say that this time everything will be as it should be, so it's recommended to spend some time (lets say a day) on a proper project setup. One day of project configuration can save lot more later on.


## Setup SCM repository

Source Control Management is a wide topic, but one thing is clear - Every project should be under some kind of source control. You should also remember about "Check In Early, Check In Often" rule.

* Git
* Mercurial
* SVN

## Custom scripts

Xcode allows us to define pre build scripts, which will be run overtime when we build the app. One of the most popular is to increment build/version number of an app.
Icon version (http://www.merowing.info/2013/03/overlaying-application-version-on-top-of-your-icon/#.VPRoJBwk_zI)

## Setup Pods

Most likely you will use some kind of external 3rd party libraries/code. Cocoapods is a dependency manager of 21st centry. 

## Configure Continous Integration / Deployment

There are plenty of available options for CI/CD, and its very recommended to pick one that best fits your needs. You will benefit from that step a lot when releasing new versions to testers / AppStore. Continues Integration will assure no taste failing code will get into production/beta builds and Continous Deployment can help with Apple's very bad app release process. (Reference to "one line deploy")

* http://jenkins-ci.org/
* http://solanolabs.com
* http://circleci.com/
* http://shippable.com
* http://codeship.io/
* http://travis-ci.org/
* http://cisimple.com/
* http://semaphoreapp.com
* http://hosted-ci.com/
* http://wercker.com/
* http://atlassian.com/softwa...
* http://jetbrains.com/teamcity/
* http://fastlane.tools

## Setup production/staging environment

If your application is communication with any sort of a backend API, you definitely should prepare you app for easy switching between staging and production servers. Best solution is to create separate project scheme for each of your configurations. 

## Crash reporting tool

* Crittercism
* Crashlytics
* Bugsense
* TestFlight (iTunesConnect)
* HockeyApp

Comparison: http://www.raywenderlich.com/33669/overview-of-ios-crash-reporting-tools-part-1

## Mobile CRM

* Apptentive

## Tasks management service

* Pivotal
* Gira
* Git issues
* Trello

