---
layout: post
title: Digital Asset Fragility
subtitle: How securing digital assets properly also protects against losing digital assets
---



## A common scenario will be presented, that demonstrates this point.

### Poor security posture
A great vacation has begun, where you have both your cellphone and laptop.
#### Current Technical posture:
Already signed into email on the laptop with passwords saved to the browser's built in password saver (the latter being highly insecure).
No dedicated app for a password manager.
Your email and bank 2FA codes are sent to the phone number tied to your physical SIM card in the phone.

##### Event 1:
Your travel bag, containing both devices, is on a table next to a pool and is bumped, landing your bag in the water. Both devices are rendered useless.

##### Or Event 2, 3, or 4:
Bag is stolen.
Ran damage.
Only have just the cellphone and it suddenly won't power on and is now unusable. Maybe the battery got hot using it as a hotspot in the sun and the circuitry was fried.

##### Recovery attempt:
Purchase another cellphone, but that physical SIM card from the old phone is also damaged or is not available due to theft. This means that you won't be able to log into your bank app because many banks refuse to modernize their 2FA codes away from SMS. You now hope you still have your ID, for receiving a friend’s kind Western Union cash transfer.
Try to log into your Google account and gain access to email. You may remember that password or not, but either way cannot sign in, because Google will prompt for the 2FA code on the new device sign-in. This means no password sync, no email.
You may have been using a Password Manager, like Keepass and cloud-synced over Dropbox. Same scenario with Google account access - this is another lock-out scenario because Dropbox will send you an email for logging into a new device. No access to that email account and so no access to that Keepass File.

##### Summary:
Simply losing your daily device results in a total lock-out scenario of all your digital assets. This includes your contacts (phone numbers of your support system), email, banking and all others. This can be an inconvenience or a significant security risk. Maybe you have another old laptop at home that is still logged into your email or maybe not.


### Excellent security posture (Vonvoo Method)
A great vacation has begun, where you have both your cellphone and laptop.
#### Current Technical posture:
Already signed into email on the laptop with password (and all others) saved to the Password Manager Bitwarden
Your email 2FA is configured to 1) a device prompt on your current phone and 2) the Authenticator App (Authy) and 3) Backup email account Recovery Codes (saved to Bitwarden).
Bank 2FA codes are sent to your Primacy Virtual Phone Number (Google Voice).

##### Events from above are the same.

##### Recovery process:
Purchase a cheap cellphone with the Emergency Cash in your travel belt. Create a burner Google Account to log into the phone. 
Log into Bitwarden and as expected, it is prompting for a 2FA code. Since this is the planned Disaster Recovery Scenario, you have the Bitwarden Recovery Code printed on the back of your laminated Emergency Card in your wallet and travel belt. Log into Bitwarden in the browser and enter the Recovery Code to temporarily disable 2FA. Now log into Bitwarden on the phone. Re-enable 2FA in the browser for Bitwarden. Log into Authy, Google Voice and email. Bonus, you also download the eSIM and now also have access to this phone number and data plan as well. Or if you have no eSIM, any physical SIM can be inserted into the phone, because your Critical Digital Assets, like Banking, are associated to the Google Voice phone number.

##### Summary:
You have now completely recovered your Critical (and all) Digital Assets and can continue with the great vacation.

## **This is how digital security, when properly implemented, guards against Digital Asset Fragility.**

*Plan for the worst and have the best of times.*

