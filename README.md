![UI5Lab Ecosystem](https://github.com/UI5Lab/UI5Lab-central/raw/master/docs/UI5LabLogoPhoenix.png)

# What is it

UI5Lab is a community driven repository for UI5 custom control libraries. Your contributions will drive our vision: A place where custom controls, templates, helper classes, and other code artifacts related to UI5 technology can be discovered and shared with the community.

# Get started

#### Browse libraries and samples
Have a look at the [UI5Lab browser](https://ui5lab.io/browser), where all current UI5Lab libraries and controls can be viewed

#### Use a UI5Lab library in your app
Follow the instructions in [this guide](https://github.com/UI5Lab/UI5Lab-central/blob/master/docs/ConsumeLibrary.md) or take a look at the [UI5Lab-app-simple](https://github.com/UI5Lab/UI5Lab-app-simple) project

#### Contribute to UI5Lab
Have a look at our [contributing guide]((https://github.com/UI5Lab/UI5Lab-central/blob/master/CONTRIBUTING.md) to help us with our mission

# UI5Lab-control-simple

This repository contains a simple square control that can be used for testing custom controls.

#### Setup

Run the following commands to test or develop this project:

1. Install node.js (get it from [nodejs.org](http://nodejs.org/)).

	> **Note:** If working behind a proxy, you need to configure it properly (HTTP_PROXY / HTTPS_PROXY / NO_PROXY environment variables)

2. Clone the repository and navigate into it
	```sh
git clone https://github.com/UI5Lab/UI5Lab-app-simple
cd UI5Lab-control-simple
	```

3. Install all npm dependencies (also installs all bower dependencies)
	```sh
npm install
	```

4. Start a local web server

	```sh
npm run serve
	```

	> **Note:** you can run the control tests with ```npm test```

10. Choose one of the following entry points to open the app

 * [Control page](src/ui5lab/control/index.html) An HTML page instantiating the control
 * [Test page](test/ui5lab/control/Square.qunit.html) A simple QUnit test

# Directions

* [Project Overview](https://github.com/UI5Lab/UI5Lab-central/blob/master/docs/Overview.md) - introduction to UI5Lab and information on all related repositories
* [Documentation](https://github.com/UI5Lab/UI5Lab-central/tree/master/docs) - detailed description on all UI5Lab topics and tutorials
* [Homepage](https://ui5lab.io) - the single point of entry for UI5Lab
* [Browser](https://ui5lab.io/browser) - lists all libraries and examples in once central place
* [Demo](https://ui5lab.github.io/UI5Lab-app-simple/index.html) - an example app consuming simple UI5Lab controls

# Troubleshooting
Issues can be created either in this repository or in any of the contributor repositories depending on where the error came from.
Be sure to include enough details and context to reproduce the issue and follow up with you.

# Contact
We organize this project in [Slack Channel #UI5Lab](https://openui5.slack.com/messages/UI5lab).
If you are interested in what we do and discuss, join with this [invitation link](http://slackui5invite.herokuapp.com/).

*The UI5Lab Community*