Description
-------------

Use this CM Demo application to test the CM SMS module and the CM Number Verifier module. After installing the application you will have a fully functional web app which you can use as an example for your own Mendix projects.

####  Typical usage scenario
Number verification helps to keep your database clean, reduce human errors, improve the communication between you and your audience and reduce fraud risks.
Typical usage of Number Verification:

-  Use Number validation to validate the user input for mobile or fixed numbers in web forms
-  Use Number validation to categorize numbers in your database as mobile or fixed
-  Use Number lookup to clean up your database and remove invalid or unavailable numbers
-  Use Number lookup to prevent ATM card cloning fraud by checking the current location of a mobile number

#### Features Number verifier
-  Validate phone number format
 - Check if a number is mobile, fixed, voip, and more
 - Check if a number has a valid format
-  Lookup mobile phone network
 - Check if a mobile number is active or not
 - Check if a mobile phone is roaming or not
 - Check the time zone of the (roaming) country


#### Dependencies
- Mendix modeler 7.3.0 and above
- Rest services module


#### Installation and Configuration

- Set constant ProductToken for the module NumberVerifier with a token of the CM platform.
In case you don’t have a CM account yet, get one at [https://register.cmtelecom.com](https://register.cmtelecom.com) and get 10 test credits for free.
- Use the microflow `SUB_PhoneNumberLookup` and `SUB_PhoneNumberValidation`