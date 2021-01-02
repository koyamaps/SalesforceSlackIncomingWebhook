# Salesforce Slack Incoming Webhook Plugin
 
This source code is a rough draft, but I wrote it so that you can easily use Slack's webhook from the Process Builder. When using it, there are some things that should be avoided in a production environment, such as how to store the URL of the webhook. Currently, the safest and most efficient way to integrate Slack and Salesforce is to use the official application available on the AppExchange.

## How To Use

It is very easy to use. Since the code coverage is already 100%, you just need to create two Apex class files in the Sandbox environment and deploy them together from the Sandbox environment to the production environment. If you are familiar with it, you will be able to start using it in the production environment within 10 minutes.

Also, although this Apex class is designed to be used in both Flow Action and Process Builder, we recommend using it in Process Builder.

## Disclaimer

The author is not responsible for any damage, including information leakage, that may occur by using this source code. The safety of the source code can be used at the user's discretion.
