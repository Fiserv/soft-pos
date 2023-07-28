# Tap to Pay on iPhone SDK by Fiserv
​
## Purpose
This Package is an SDK that facilitates enabling Apple's Tap To Pay on iPhone functionality in your own app.  With just a bit of configuration and a few lines of code, your iPhone app will be able to securely accept contactless payments on a supported iPhone without any additional hardware (e.g. POS terminal, external card reader device, etc.)  
​
Currently this functionality is only available in the U.S.
​
By using this Package, you will *not* need to certify your app.   We have taken care of that for you.
​
​
## Pre-requisites
​
​
### Device Requirements 
Apple Tap to Pay on iPhone requires iPhone XS or later, running iOS 16 or later
​
### Tap to Pay Entitlement
You must request a special entitlement from Apple to enable Tap To Pay.  Log-into your Apple Developer Account and then [click here](https://developer.apple.com/contact/request/tap-to-pay-on-iphone) to request the entitlement.  In the text box titled 'PSP, enter 'Fiserv' as the value.
​
Follow the instructions here to [add the entitlement to your app's profile](https://developer.apple.com/documentation/proximityreader/setting-up-the-entitlement-for-tap-to-pay-on-iphone)
​
### Obtain Fiserv Credentials
You can obtain test credentials for your app on [Fiserv's Developer Studio](https://developer.fiserv.com) by following these directions:
​
1. Create an account by clicking the orange button in the upper right of the page
2. Log-into [Developer Studio](https://developer.fiserv.com) with your email address/password
3. Click the Workspaces option in the top toolbar
4. Tap the button 'Add New Workspace'
5. Create a workspace of type 'CommerceHub'.  Provide a name and description, then select 'CommerceHub' from the 'Product' drop-down list
6. Click the 'Create Button'
7. In the Workspace, click the 'Credentials' tab
8. Click the 'Create API key'. You will need to select a Merchant Id from the drop-down, provide a name for the API Key, click the 'Sandbox' radio button from the 'API Key Type' list, and select 'Payments' in the 'Features' checkboxes.  Click the 'Create' button.
9. Important!  Copy the full API Key and Secret and store them __securely__.  Or, you can click the 'Save to File' button to download them into a file.   You will need these credentials to access the Fiserv SDK and back-end API's.  Protect these credentials in your code and in your app.
​