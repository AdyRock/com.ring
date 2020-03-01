# Ring for Homey
Connect your Ring products with Homey.
Two-Factor Security Authentication (2FA) is now supported.

## Instructions:
* Download the app and extract it to your PC.
* Open the CLI for Homey and cd to the Ring.com folder on you PC. (see https://community.athom.com/t/how-to-cli-install-method/198 for instructions on using the CLI)
* Install the app.
* Select Configure app from the App details screen.
* Enter your email address and password but leave the authentication code empty.
* Hit the Authenticate button. You will see an error message (402) but ignore that. You receive and email or SMS with an authentication code from Ring.
* Enter the code into the the app configuration page and authenticate again.

Some users have reported that they had to remove and add the devices again to get them to work.
## Currently supports:
* Ring Chime (Pro)
* Ring Stick Up Cam
* Ring Video Doorbell (Pro)

## Licensing:
* This application is subject to [these terms](https://github.com/denniedegroot/com.ring/blob/master/LICENSE).
