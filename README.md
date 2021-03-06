![IoTConference_logo.JPG](https://bitbucket.org/repo/xbqy9a/images/107497857-IoTConference_logo.JPG)
# Node-RED Bluemix IoT 2016 Base Installation for the Tutorial on: #

## IoT Platforms: Rapid Development of IoT Applications ##
------------------------------------------------------------
### Node-RED in BlueMix prepared for the tutorial at IoT 2016

This repository is an example Node-RED application that can be deployed into
Bluemix with only a couple clicks. Just click on the Button below to start the deployment to your IBM Bluemix account.

[![Deploy to Bluemix](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?%20repository=https://github.com/sebastianmantsch/IoTBluemixTutorialNode.git)

### How does this work?

When you click the button, you are taken to Bluemix where you get to pick a name
for your application at which point the platform takes over, grabs the code from
this repository and gets it deployed.

It will automatically create an instance of the Cloudant DB service, call it
`iot-cloudant-cloudantNoSQLDB` and bind it to you app. This is where your
Node-RED instance will store its data. If you deploy multiple instances of
Node-RED from this repository, they will share the one Cloudant instance.

Additionally the Watson Internet of Things Platform is added to your application as service `iot-iotf-service`.
There you will be able to create a Device Type and add a device which will be connected to the platform.

Node-RED includes a simple default flow which we customized to work with the configured IoT Device.

The corresponding part for your mobile device is located in following repository:

[HTML5 Phone Repository](https://github.com/sebastianmantsch/IoTBluemixTutorialPhone)


Tutorial based on:

[Link 1](https://github.com/jeancarl/node-red-labs/tree/master/lab-mobile-accelerometer-sensor)

[Link 2](https://github.com/ibmets/node-red-bluemix-starter)
