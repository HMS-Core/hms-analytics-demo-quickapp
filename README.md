# HMS AnalyticsKit Demo for QuickApp

## Table of Contents

* [Introduction](#introduction)
* [Installation](#installation)
* [Configuration](#configuration)
* [Environment requirements](#Environment-requirements)
* [Sample Code](#sample-code)
* [License](#license)

## Introduction

HmsAnalyticsKitDemo is a QuickApp client that applying HUAWEI Hianalytics SDK used for showing how to collect user engagement and user preference.
[Read more about Hianalytics](https://developer.huawei.com/consumer/en/doc/development/HMSCore-Guides-V5/introduction-0000001050745149).

## Installation

1. Use HUAWEI QuickApp IDE to open the decompressed project, we provide two demos:
   1. quickapp.hmsanalyticskitdemo: this is a completed code for the sample app.
   2. quickapp.hmsanalyticskitdemo-start: this is a starting code that you'll build upon during this codelab.
2. Use the "Npm -> Start Npm Library" to generate "package.json" file.
3. Run the following command to install the AnalyticsKit SDK for QuickApp:
  
   ```bash
   npm install --save @hmscore/analytics-sdk-quickapp
   ```

## Configuration

Create a QuickApp in AppGallery Connect and obtain the project configuration, then copy it to your QuickApp project.

## Environment requirements

Hardware requirements:

1. A computer
2. An Android phone

Software requirements:

1. The [HUAWEI QuickApp IDE](https://developer.huawei.com/consumer/cn/quickApp-ide/)
2. The package manager [npm](https://www.npmjs.com) , which typically comes with [Node.js](https://nodejs.org/en)
3. The codelab's sample code
4. A terminal/console

## Sample Code

After running the app you should see a screen like this:

![screen_0](screenshot/screen_0.png)

Click the button TRUE or FALSE to answer the question; Click the NEXT, show the next question; Click POST SCORE, log the score user got. All the infomations will be upload to Hianalytics, and you can see these infomations in real time using Real-time.

Click button SETTINGS:

![screen_1](screenshot/screen_1.png)

You will be asked what your favorite sport is. This choice will be logged to Hianalytics as a User Property.

## License

HmsAnalyticsKitDemo is licensed under the [Apache License, version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
