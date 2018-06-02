# Ramadan Code Challenge #1

This is quick demo to push a simple webpage to IBM Cloud via the command line interface.


### Prerequisites
Before starting this demo make sure you have done the following:
* Register to IBM Cloud from [here](https://ibm.biz/BdZzCd).
* Download and install [IBM Cloud CLI](https://console.bluemix.net/docs/cli/reference/bluemix_cli/download_cli.html).


### Let's get started!

1. Download or clone this repository
2. Open the command line or Terminal if you're using mac.
3. Log-in to IBM Cloud by typing `bx login -a "api-endpoint"`.
_api-endpoint_ is the region you want to deploy your app to, say the want to deploy to United Kingdom then you have to type in
`bx login -a https://api.eu-gb.bluemix.net `

4. Select your organization and space that will contain the app  `bx target -o "your-organization" -s "your-space" `. your organization by default is your account. you might need to create a space using the [IBM cloud dashboard](http://console.bluemix.net/).
5. If you have downloaded the repository, navigate to the path where you stored the file by `cd <project-path>`.
6. Now push the app to cloud by typing `bx push  <app-name>`
give it a name and wait a minute for it to deploy, once it says **App started** copy and paste the app URL into your browser.
7. Tweet us your link! ;)

[![finalstep.gif](https://s33.postimg.cc/cao44intb/finalstep.gif)](https://postimg.cc/image/qh3uzqyob/)


#### Congrats! you've successfully pushed an app to the cloud :tada:
Stay tuned for the next challenge! for more details visit [ IBM Cloud Saudi](https://www.meetup.com/IBM-Cloud-KSA/) page on meetup.
