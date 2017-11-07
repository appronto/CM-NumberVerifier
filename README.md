Description
-----------

Number verification helps to keep your database clean, reduce human errors, improve the communication between you and your audience and reduce fraud risks. The number format validator is updated daily with new and changed number ranges globally. The number lookup performs a real-time lookup on the home carrier network.

**Typical usage of Number Verification:**
Use Number format validation to

 - Validate the user input for mobile or fixed numbers in web forms
 - Categorize numbers in your database as mobile or fixed

**Use Mobile phone number network lookup to**

 - Clean up your database and remove invalid or unavailable numbers
 - Prevent ATM card cloning fraud by checking the current location of a mobile number

**Detailed feature overview**

Number format validation:

- See if a number has a valid format
 - Valid (true/false)
- Get detailed information about the number (example)
 - Country code (44)
 - Country ISO (GB)
 - Format e164 (+447911111111)
 - Format international (+44 7911 111111)
 - Format national (07911 111111)
 - Region (Guernsey)
 - Region code (GG)
 - Time zone (Europe/London)
 - Carrier (GB - Jersey Telecom – 23450)

-	Get number type information (True/False) 
 - Is Mobile?
 - Is Fixed line?
 - Is Fixed line or mobile?
 - Is Voip?
 - Is Toll free?
 - Is Voicemail?
 - Is Emergency?
 - Is  Premium rate?
 - Is  Standard rate?
 - Is  Shared cost?
 - Is  Personal?
 - Is  Pager?
 - Is  Short code?
 - Is  Unknown?

**Mobile phone number network lookup:**

The same information as the number format validation

-	See if the number is active
	- Active number (true/false)
-	Get information from the carrier network:
	- Carrier mcc (234)
	- Carrier mnc (50)
	- Ported (true/false)
	- Roaming (true/false)
	- Get information from the roaming carrier network:
	- Roaming country ISO (NL)
	- Roaming country prefix (31)
	- Roaming carrier (T-mobile)
	- Roaming mcc (204)
	- Roaming mnc (16)


#### Dependencies
- Mendix modeler 7.3.0 and above

#### Installation and Configuration

In case you don’t have a CM account yet, get one at [https://register.cmtelecom.com](https://register.cmtelecom.com) and get 10 credits on top to send SMS for free. Get the CM Product token at [https://gateway.cmtelecom.com](https://gateway.cmtelecom.com) and store this key in the constant ProductToken of th eNumberVerifier module. You’re ready to go!
Use the microflow `SUB_PhoneNumberLookup` and `SUB_PhoneNumberValidation`

#### Demo
The CM Demo application allows you to test the SMS module and Number Verifier module of CM. The demo has both modules fully integrated in a fully functional app so you can actually test every functionality to see how it works.

#### Pricing
The Number format validator can be used for free in combination with a monthly subscription of other CM products. Without such subscription, a fee of 0.002 EUR per number query is charged.
For the Mobile phone network lookup a fee per transaction is applicable starting at 0.011 EUR depending on your total number of lookups per month. You will receive an addendum from CM about handling privacy sensitive information. 
To start, share your use case along with an indication of the amount of lookups per month at [plugins@cm.nl](mailto:plugins@cm.nl) and get a customized offer.