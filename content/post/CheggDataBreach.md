+++
author = "Hugo Authors"
title = "Chegg Data Breach: A Case Study of Weaponizing Exposed Credentials"
date = "2019-09-30"
description = "Looking into the effects of the Chegg Data Breach."
+++

When a company has been breached or leaked credentials to their users’ accounts, the typical first step is to reset all their users’ passwords. However it poses a serious risk for other institutions as most users reuse passwords so these credentials could be valid for their other financial, social, or educational accounts.

One of the many breaches in the last several years was Chegg, an online textbook rental and educational service, whom was breached in 2018. Chegg stated that as many as [40 million credentials](https://techcrunch.com/2018/09/26/chegg-resets-40-million-user-passwords-after-data-breach/) were exposed.

This data has been systematically used by a bad actor or group to use the exposed credentials against university accounts, hoping some of the users reused their passwords from Chegg and have not changed it since last year. Upon gaining access to a university account, the attacker can pivot and try to gain access to other platforms or send phishing emails campus wide appearing as a trusted member of campus.

A Florida college and various other higher education institutions have experienced this attack firsthand. Beginning on Sept. 17th, 2019 at 18:26 EST, one Florida university reported logins were being attempted every five minutes and disabled by their implementation of Okta due to maximum login attempts. From the start of the attack, 834 students had Okta lockouts and 790 of those were on the Chegg data breach list. The other 44 students can be attributed to typical lockouts from people mistyping their password or forgetting their two factor authentication. They were able to pull a list of all * @university.edu users that were exposed on the Chegg data breach from [HaveIBeenPwned](https://haveibeenpwned.com/), showing several thousand users could be at risk.

The attackers were successful with accessing several alumni student accounts, as the students are currently able to retain their email accounts for life. As soon as an attacker gained access to an alumni account, the IT Security Administrator was able to disable their account. The logons were from many suspicious IP addresses which Microsoft Outlook Security flagged. An array of IP ranges were used in the attack including but not limited to Palestine, Brazil, China, Russia, and the Ukraine. Once a user’s account was disabled, the user had to call the university’s Help Desk and reset their password and set up two factor authentication with the Okta mobile application.

This was just an example of one institution dealing with the weaponization of Chegg’s data exposure.  It is an issue facing many educational organizations as the targeted attacks continue. The use of Chegg’s user credentials are better than others for two reasons:

1. Students are often not required to change their password every 90 days like employees of the organization
2. Alumni users would not notice if their university email was compromised, giving the attacker longer to pivot and gain information.

The use of Chegg’s data demonstrates the high risk of user password re-use and also why colleges are just as vulnerable as other organizations. It is vital for organizations to be aware of other breaches in case it leads to targeting of their users.

***Information gathered via personal interview and documentation provided by CampusGuard and HaveIBeenPwned
