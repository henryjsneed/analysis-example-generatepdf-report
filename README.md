## What this does
Get variable "temperature" from bucket and generate a pdf file to send via email.

## How to run the script on Tago
Do your own modifications if you want.<br>
Upload to Tago analysis, in the admin website.<br>
Add the environment variable `email` with an email.

## How to run the script from my computer
Make sure you have npm and node installed in your machine.<br>
Add the environment variable `device_token` with the device token of your choice, to the analysis configuration, in the admin website.<br>
Open the analysis.js, change `MY-ANALYSIS-TOKEN-HERE` line for your analysis token.<br>
Open the terminal and run:

`npm install`<br>
`node .`

