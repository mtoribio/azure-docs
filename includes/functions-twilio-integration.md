This sample involves using the [Twilio](https://www.twilio.com/) service to send SMS messages to a mobile phone. Azure Functions already has support for Twilio via the [Twilio binding](https://docs.microsoft.com/azure/azure-functions/functions-bindings-twilio), and the sample uses that feature.

The first thing you need is a Twilio account. You can create one free at https://www.twilio.com/try-twilio. Once you have an account, add the following three **app settings** to your function app.

| App setting name | Value description |
| - | - |
| **TwilioAccountSid**  | The SID for your Twilio account |
| **TwilioAuthToken**   | The Auth token for your Twilio account |
| **TwilioPhoneNumber** | The phone number associated with your Twilio account. This is used to send SMS messages. |