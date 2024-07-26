---
layout: post
title: Migrate away from 2FA app Authy by Twilio
subtitle: Why Vonvoo no longer recommends Authy
---

#### Critical Apps require resiliency.

Resiliency includes guarding against:
* Losing your digital devices and being able to recover your data
* The app provider having an outage, data loss or disappearing
* The app provider becoming hostile to users

Authy was the first solution - for a long time - to offer cloud-synchronized 2FA (via TOTP). For this reason, Vonvoo recommended the solution in the past.

Now we have something much better with [Ente Auth](https://ente.io/blog/auth/ "Ente Auth").

Enty Auth also supports cloud sync, and are so much better:
* Open source
* Do not hold your encryption keys (they cannot access your data)
* Support importing and exporting your tokens (you can export the full list of your 2FA accounts to leave the app, to use any other app you wish)

The dethroned app Authy became increasingly hostile over time, by:
* Sending aggressive telemetry to 3rd parties (not private)
* Decommissioning their desktop apps (this was the only place to export your 2FA tokens)
* Decommissioning those apps ahead of schedule
* Offering no path for leaving the app (except for manually migrating 2FA from every account that used it)

Vonvoo recommends secure solutions that are friendly to the widest audience. It is a serious consideration to change a critical app. But for all the reasons above, it is recommended to migrate away from Authy.

Check out the [Vonvoo 2FA Tutorial](https://docs.vonvoo.com/en/latest/2%20factor%20authentication.html "Vonvoo 2FA Tutorial"). to guide the process. 

If this is your first time here, it is recommended to follow all [Vonvoo Essentials Tutorials](https://docs.vonvoo.com/en/latest/index.html "Vonvoo Essentials Tutorials") to secure your digital assets.

<p style="text-align: center;"> <i>Prepare for the worst and have the best of times. </i></p> 
